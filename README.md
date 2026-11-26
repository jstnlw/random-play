## 1. Overview

A noncommercial fan game set in the world of **Zenless Zone Zero**, centered on **Wise and Belle** managing **Random Play**, their video rental store on **Sixth Street, New Eridu**.

The primary experience is a relaxed, menu-driven **idle business tycoon**. Players manage rentals, recommendations, memberships, customer relationships, inventory, staff, and upgrades. A secondary **Proxy** system lets players accept commissions and guide agents through Hollow investigations using automated expeditions and occasional decisions.

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

## VIP Agents

VIPs are obtainable banner characters from Zenless Zone Zero who occasionally visit Random Play. Players can build relationships with these characters through store interactions and randomized requests.

Reaching **100% relationship unlocks the VIP as a recruitable agent for Proxy Hollow missions**.

### Relationship Progression

Each VIP has an individual relationship meter ranging from **0% to 100%**.

| Activity | Relationship Gain |
|---|---|
| Initial relationship | 0% |
| Casual store interaction | +1% |
| Small request | +3% |
| Standard quest | +5% |
| Special quest | +10% |
| Maximum relationship | 100% |

Relationship progress is permanent and does not decay.

### VIP Visits

VIP appearances follow a combination of scheduled preferences and randomized visits.

- Each VIP has preferred visiting days or times.
- Higher relationship levels slightly increase visit frequency.
- VIPs who have not appeared for several days receive an increased chance of visiting.
- Active quests may trigger guaranteed appearances.
- Each VIP can offer one new request per in-game day.

This ensures players have regular opportunities to build relationships without relying entirely on random appearances.

### Randomized Quests and Requests

VIPs occasionally offer randomized requests based on their personalities and preferences.

| Request Type | Example | Relationship Reward |
|---|---|---|
| Small | Recommend a movie matching their preferred genre | +3% |
| Standard | Reserve several specific movie tapes | +5% |
| Special | Acquire a rare movie for the VIP | +10% |

**Request rules:**

- Requests vary in objectives, difficulty, and rewards.
- Request generation considers each VIP's personality and preferences.
- Failed or expired requests do not reduce relationships.
- Players simply miss the relationship reward.
- Requests can reappear in future visits.
- Completed requests may also reward Dennies, items, or materials.

### Relationship Milestones

Relationship progression unlocks additional interactions and benefits.

| Relationship | Unlock |
|---|---|
| 0% | First encounter |
| 25% | Additional character dialogue |
| 50% | Character-specific requests |
| 75% | Special relationship event |
| 100% | Permanent recruitment for Hollow missions |

Milestones provide meaningful progression before reaching maximum relationship.

### VIP Recruitment

Upon reaching **100% relationship**, the VIP becomes available for recruitment into Proxy Hollow missions.

**Recruitment rules:**

- Recruitment is free.
- Recruited agents are permanently unlocked.
- Agents become selectable in the Proxy expedition roster.
- Agents can participate in one expedition at a time.
- Completed expeditions trigger a short recovery period.
- Investigation upgrades can reduce recovery time.
- Relationships remain at 100% after recruitment.
- Recruitment does not introduce direct character control or combat.

Relationship progress and recruitment status are preserved in save data.

### Post-Recruitment Activities

Recruited VIPs continue visiting Random Play and interacting with the player.

Once their relationship reaches 100%:

- Randomized requests remain available.
- Requests reward Dennies, materials, or exclusive tapes instead of relationship points.
- Special character interactions remain accessible.
- VIPs may unlock additional store events.

### VIP Loyalty Bonuses

Each recruited VIP may provide a small passive bonus to Random Play.

Possible bonuses include:

- Increased popularity for specific movie genres.
- Higher customer visit frequency.
- Improved customer satisfaction.
- Increased chances of discovering rare tapes.
- Additional rewards from movie recommendations.

Bonuses should reflect each character's personality and remain relatively small to avoid making VIP recruitment mandatory for business success.

### Progression Balancing

The relationship system should reward consistent interaction without excessive grinding.

**Recommended targets:**

| Mechanic | Recommendation |
|---|---|
| Starting relationship | 0% |
| Casual interaction | +1% |
| Small request | +3% |
| Standard quest | +5% |
| Special quest | +10% |
| First VIP recruitment | Approximately 10 to 15 in-game days |
| Typical recruitment | Approximately 15 to 20 meaningful interactions |
| Request cooldown | One in-game day per VIP |
| Relationship decay | None |
| Failed request penalty | None |
| Expired request penalty | None |
| Recruitment cost | Free |

These values are initial balancing targets and may be adjusted during playtesting.

### Gameplay Interaction Loop

1. VIP visits Random Play.
2. Player interacts with the VIP.
3. VIP offers a randomized quest or request.
4. Player accepts and completes the objective.
5. Relationship percentage increases.
6. Relationship milestones unlock additional interactions.
7. At 100%, the VIP becomes recruitable.
8. Recruited VIP becomes available for Hollow expeditions.
9. Future visits and requests provide additional rewards.

### Design Principles

1. **Permanent progression:** Relationships never decrease.
2. **Relaxed gameplay:** Missing requests does not punish players.
3. **Predictable opportunities:** Random visits should not prevent progression indefinitely.
4. **Character identity:** Requests should reflect individual VIP personalities.
5. **Meaningful milestones:** Players receive rewards throughout relationship progression.
6. **Permanent recruitment:** Agents remain unlocked after reaching 100%.
7. **Continued interaction:** Recruited VIPs remain relevant to store management.
8. **Balanced rewards:** VIP bonuses enhance the business without becoming mandatory.

**Core objective:** Build relationships with familiar characters through everyday interactions at Random Play, eventually earning their trust and unlocking their assistance in Hollow investigations.

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
