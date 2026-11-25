# Random Play: Video Store Tycoon

**Game Design Document**
**Status:** Concept and preproduction only. No game project has been built.
**Version:** 0.2 (26 November 2026)

## 1. Overview

A noncommercial fan game set in the world of **Zenless Zone Zero**, centered on **Wise and Belle** managing **Random Play**, their video rental store on **Sixth Street, New Eridu**.

The primary experience is a relaxed, menu-driven **idle business tycoon**. Players manage rentals, recommendations, memberships, customer relationships, inventory, staff, and upgrades. A secondary **Proxy** system lets players accept commissions and guide agents through Hollow investigations using automated expeditions and occasional decisions.

**Distribution:** Internal circulation only; not intended for commercial sale. This is an unofficial fan project, not affiliated with or endorsed by the rights holders. Internal-only distribution does not itself grant rights to copyrighted assets or characters; review permissions before sharing.

## 2. Creative Pillars

1. **Store first:** Running Random Play is the heart of the game; Proxy work is optional secondary progression.
2. **Observe and optimize:** Customers and staff act automatically; players make meaningful business decisions through menus.
3. **A living place:** Ambient animations and familiar visitors make the store feel active even when the player is idle.
4. **Relationships matter:** Recommendations, memberships, repeat visits, and VIP interactions build long-term attachment.
5. **Visible growth:** New tapes, furniture, Bangboos, and investigation upgrades should noticeably improve operations.
6. **Relaxed pacing:** Pause and speed controls, limited repetitive tasks, and automation keep management approachable.

## 3. Inspirations and Boundaries

| Reference | What it informs |
|---|---|
| Zenless Zone Zero | World, Random Play setting, Wise and Belle, Bangboos, agents, Hollow and Proxy themes |
| Kairosoft tycoon games | Menu-based management, idle simulation, unlocks, upgrades, business progression |
| Eastward | High-detail 2D pixel art, atmospheric environments, expressive animation, warm lighting |

**Important:** Kairosoft is a gameplay reference, **not** the target graphic fidelity. Eastward is the primary visual quality reference. Create original fan-game artwork rather than copying existing game assets.

## 4. Player Experience

- **Interaction:** Mostly mouse-driven menus and clickable objects; keyboard shortcuts may be added.
- **No direct movement:** Players do **not** control Wise or Belle walking around the store.
- **Main view:** A detailed top-down, slightly angled view of Random Play, with customers, Wise, Belle, and Bangboos animated in the environment.
- **Primary actions:** Manage the store, tapes, customers, Bangboos, and Proxy work through panels.
- **Time:** Day-based business simulation with accelerated in-game opening hours, pause, and speed options.
- **Offline idle progression:** Not committed. Initial design assumes simulation progresses while the game is running; offline earnings can be evaluated later.

## 5. Core Gameplay Loop

1. Review inventory, store performance, and available commissions.
2. Purchase or unlock tapes and configure store operations.
3. Open the store and observe automatic browsing, rentals, and returns.
4. Respond to recommendation requests and membership opportunities.
5. Build relationships with regular citizens and VIP agents.
6. Assign Bangboos and invest earnings in upgrades.
7. Optionally launch Proxy expeditions alongside store operations.
8. Review the daily report and plan the next day.

### Proposed day schedule (subject to balancing)

| Time | Activity |
|---|---|
| 8:00 AM | Preparation and management |
| 10:00 AM | Store opens |
| 10:00 AM to 9:00 PM | Automated customer visits and rentals |
| 9:00 PM | Store closes |
| End of day | Financial and operational summary |

## 6. Primary Systems

### 6.1 Rentals and Inventory

- Fictional in-game movie titles with genre, popularity, rarity, rental price, available copies, and rental duration.
- Customers choose tapes based on preferences, stock, and trends.
- Rentals generate Dennies; returned copies become available again.
- Expand the collection and unlock additional genres, rare tapes, and exclusive titles.
- Completing collections may unlock bonuses or events.

### 6.2 Recommendations

- Some customers request movie suggestions.
- Recommendations consider genre preference, rental history, and personality.
- Successful suggestions improve satisfaction and relationships; poor suggestions can lower them.
- This is an occasional meaningful decision, not a mandatory action for every rental.

### 6.3 Memberships

- Register returning customers as members.
- Candidate tiers: Regular, Silver, Gold, VIP.
- Possible perks include discounts, extended rental periods, and access to exclusive tapes.
- Exact prices, eligibility, and recurring revenue rules remain to be balanced.

### 6.4 Relationships and VIP Agent Recruitment

**Regular citizens**

- Recurring citizens have preferences, membership status, rental history, and relationship progression.
- Relationships unlock dialogue, personal requests, referrals, and events.

**VIP agents**

- VIPs are the obtainable banner characters from Zenless Zone Zero, appearing as special visitors to Random Play.
- Each VIP has an individual relationship meter from **0% to 100%**.
- VIP relationships increase through store visits and by accepting and completing **randomized quests and requests** from that VIP.
- Requests can vary in objective, difficulty, and reward, providing repeatable reasons to interact with each character.
- At **100% relationship**, the VIP becomes **recruitable for Proxy Hollow missions**.
- Recruitment unlocks the agent for selection in the Proxy expedition roster; it does not turn the game into direct combat.
- Relationship progress and recruitment status persist in save data.

**Proposed interaction loop:** VIP visits -> player interacts or accepts a randomized request -> completes the request -> gains relationship progress -> reaches 100% -> unlocks the VIP for Hollow missions.

**To determine during balancing:** Starting relationship values, points per request, whether visits alone grant points, request cooldowns, failed or expired request penalties, and whether recruited agents require any additional mission costs. Recruitment at 100% is the confirmed rule.

### 6.5 Bangboo Staff

- Hire Bangboos to automate cashier work, restocking, customer assistance, maintenance, and marketing.
- Assign and reassign roles through menus.
- Upgrade efficiency and account for maintenance or operating costs.
- Bangboo activity should be visible in the store.

### 6.6 Store Customization and Upgrades

- Grid-based placement of shelves, counters, and decorations.
- Improve capacity, checkout speed, customer comfort, inventory space, and reputation.
- Expand the floor plan as progression allows.
- Furniture footprints follow the grid, while artwork may extend beyond a footprint.

## 7. Secondary System: Proxy Commissions

- Wise and Belle continue their work as Phaethon.
- Accept commissions, select **recruited agents** (VIPs unlocked at 100% relationship), prepare equipment, and start automated Hollow expeditions.
- Expeditions run while the store continues operating.
- Occasional choices influence risk, duration, and rewards.
- Rewards may include Dennies, investigation materials, rare tapes, or relationship opportunities.
- Upgrade navigation, equipment, mission slots, expedition efficiency, and risk mitigation.
- **No direct action combat is planned.** Store management remains the main experience.

## 8. Interface Structure

### Persistent HUD

- Day and time
- Dennies
- Store reputation
- Customer satisfaction
- Active Proxy commission status
- Pause and simulation speed controls

### Primary menus

| Menu | Functions |
|---|---|
| Store | Layout, furniture, facilities, upgrades |
| Movies | Inventory, purchasing, collections, recommendations |
| Customers | Memberships, relationships, regulars, VIPs |
| Staff | Bangboo hiring, assignments, upgrades |
| Proxy | Commissions, agents, expeditions, investigation upgrades |

Clicking a shelf, customer, or Bangboo may open a contextual panel. The detailed layout and navigation flow are not yet finalized.

## 9. Visual and Technical Specifications

These are **accepted starting specifications**, subject to adjustment during prototyping before final art production.

| Property | Specification |
|---|---|
| Engine | Godot 4 |
| Scripting | GDScript |
| Primary target | HTML5 browser |
| Secondary target | Windows PC |
| Renderer | Compatibility |
| Web export | Single-threaded |
| Internal resolution | **640 x 360 px** |
| Environment placement grid | **32 x 32 px** |
| Character sprite targets | Approximately **32 to 48 px wide x 48 to 64 px tall** |
| Camera | Top-down, slightly angled, visible wall and furniture fronts |
| Texture filtering | Nearest neighbor |
| Scaling | Integer scaling where practical; responsive UI for browser windows |
| Art quality | Detailed, atmospheric 2D pixel art inspired by Eastward |
| Lighting | Warm interior light, restrained neon glow and ambient effects |
| UI | ZZZ-inspired visual identity, optimized for management readability |

### Asset consistency rules

- The **32 x 32 grid controls placement**, not the size of every sprite.
- Furniture can span multiple tiles; its art may extend above or beyond its footprint.
- Preserve consistent character proportions, camera angle, shading, outlines, and palette across assets.
- Avoid blurry texture filtering and excessive postprocessing that obscures pixel art.
- Use sprite sheets or atlases and limit simultaneous effects for browser performance.
- Start with functional placeholder art, then replace it with cohesive production assets.

## 10. Progression

**Store path:** Earn Dennies -> Expand inventory -> Attract customers -> Improve reputation -> Unlock facilities and Bangboo automation.

**Proxy path:** Accept commissions -> Earn materials -> Upgrade investigation systems -> Unlock harder missions and agent-related events.

The paths may intersect, but the player should be able to enjoy the game while focusing primarily on the store.

## 11. Proposed Development Milestones

| Version | Scope |
|---|---|
| 0.1 | Main store view, idle customer simulation, rentals, income, daily cycle, basic HUD |
| 0.2 | Movie inventory, purchasing, collections |
| 0.3 | Customer preferences and recommendations |
| 0.4 | Memberships, VIP relationships, randomized requests, and 100% recruitment unlock |
| 0.5 | Bangboo staffing and automation |
| 0.6 | Store upgrades and grid-based customization |
| 0.7 | Proxy commissions and automated expeditions |
| 0.8 | VIP agents, special events, Hollow upgrades |
| 0.9 | Pixel art polish, animation, audio, balancing, saves |
| 1.0 | Testing, optimization, browser and PC release preparation |

Milestones are provisional, not release commitments. Basic save support may need to be implemented earlier than 0.9 to support testing.

## 12. Development Workflow (When Authorized)

1. Finalize screen layout and core interaction flows.
2. Generate a Godot project with `project.godot`, `.tscn` scenes, `.gd` scripts, resources, data, and placeholder assets.
3. Package the project as a ZIP that can be imported into Godot.
4. Run available automated or headless checks; manually test interactions in the Godot editor and browser.
5. Iterate in small versions, preferably tracked in Git.
6. Replace placeholder graphics with consistent original pixel art.
7. Export and test HTML5 and Windows builds.

**Current instruction:** Do not build or generate the Godot project yet. This document records design decisions only.

## 13. Open Design Questions

- Exact main screen composition and panel behavior.
- Whether the store is a fixed recognizable Random Play interior, freely expandable, or a hybrid of both.
- Customer arrival rates, rental durations, income, expenses, and balancing.
- Whether membership tiers match the proposed four-tier model.
- VIP banner-character roster and availability rules, dialogue scope, randomized request pool, relationship gain rates, and event unlock rules.
- Proxy expedition decision frequency and failure consequences.
- Save format and browser persistence strategy.
- How much simulation continues while menus are open.
- Whether offline idle progress is desirable.
- Final pixel art palette, animation frame counts, and UI scaling rules.

## 14. Confirmed Scope Boundaries

- Noncommercial, internal-only fan project.
- No direct player control of Wise or Belle.
- Menu-first, Kairosoft-inspired management gameplay.
- Eastward-inspired pixel art fidelity rather than Kairosoft-style graphics.
- Store management is primary; Proxy missions are secondary.
- VIP banner characters become recruitable for Hollow missions only after reaching 100% relationship through visits and randomized requests.
- HTML5 compatibility is a core technical requirement.
- **No implementation work should begin until explicitly requested.**
