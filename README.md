# RELICS OF THE ECLIPSE
## Game Design Document

**Project Overview**

A celestial-themed relic collection and case-opening game built around rarity, market economics, collection progression, challenges, and dramatic opening animations.

The experience combines randomized relic discoveries with a player-driven shard economy, collectible variations, competitive seeded challenges, and long-term progression.

---

# 1. Case Opening System

The case-opening experience is designed to feel dramatic, rewarding, and interactive.

### Opening Animations
- **Standard Opening:** Twelve relics orbit the screen before falling away one by one until the final relic is revealed.
- **Open Ten:** Opens ten cases instantly and presents all results in a results grid.
- **Fast Open:** A saved toggle that reduces opening animation time.
- **Tap-to-Speed:** Tapping the case during an opening accelerates the animation.
- **Near-Miss Drama:** When the runner-up relic is rarer than the winning relic, the animation slows down, accompanied by a heartbeat, screen crack, and shake effects.

### Available Cases

| Case | Cost | Special Mechanics |
|---|---:|---|
| Standard Case | 100 Shards | Standard relic odds |
| Hollow Moon | 32 Shards | Dust-heavy odds; no pity progress |
| Gilded Candle | 125 Shards | Variants are 4× more likely |
| Tidal Mercy | 120 Shards | Keeps the cleaner of two erosion rolls |
| Eventide Surge | 155 Shards | Improved rare relic odds |
| Eclipse Case | 500 Shards | Exclusive Eclipse relic pool |

### Live Chat
A simulated livestream chat reacts dynamically to:
- Case openings.
- Near-misses.
- Market sales.
- Special events.
- Rare relic discoveries.

---

# 2. Relic System

The game features **38 unique relics**, divided between standard relics and exclusive Eclipse relics.

### Relic Distribution

| Rarity | Standard Relics | Drop Chance |
|---|---:|---:|
| Dust | 6 | 60% |
| Ember | 8 | 25% |
| Nebula | 8 | 10% |
| Pulsar | 5 | 4% |
| Singularity | 3 | 1% |
| Eclipse Exclusive | 8 | Special |

**Total: 30 Standard Relics + 8 Eclipse Exclusives = 38 Relics.**

### Drop Odds and Pity
- Every standard case follows the listed rarity distribution.
- A Pulsar or higher rarity is guaranteed within 25 eligible opens.
- Hollow Moon openings do not contribute toward pity progress.

### Erosion System

Every relic receives an erosion value between 0 and 1.

**Lower erosion values indicate better condition and higher potential market value.**

| Condition | Description |
|---|---|
| Unmarked | Pristine condition |
| Lustrous | Excellent condition |
| Aged | Noticeable wear |
| Cracked | Significant wear |
| Fading | Heavily worn |

Each condition has corresponding visual scratches and deterioration effects.

### Relic Variants

Approximately 5% of drops receive a special variant.

There are four variants:
- **Gilded:** A golden visual effect.
- **Haunted:** A supernatural visual effect.
- **Echo:** An echo-themed visual effect.
- **Inverted:** An inverted visual effect.

Each variant has its own distinctive appearance and effects.

### Pattern Numbers

Every relic receives a randomly generated pattern number between **0000 and 9999**.

Certain patterns carry additional value:
- Mirror
- Uniform
- Low

### Relic Inspection

Players can inspect individual relics through a tilting foil interface.

The inspection view displays:
- Exact erosion value.
- Pattern number.
- Rarity.
- Variant.
- Current market value.

### Eclipse Relics

The Eclipse Case contains eight exclusive relics.

- Four of the eight exclusives rotate into the case each week.
- Features a distinct violet visual theme.
- Includes its own constellation.
- Exclusive relics contribute to Eclipse collection progression.

---

# 3. Shard Economy and Market

Shards are the primary currency used throughout the game.

### Starting Currency
- Every new player starts with 3,000 Shards.
- There are no free recurring refills.
- Opening cases consumes Shards.
- The Market is the primary method of recovering and earning Shards.

### Player Market

Players can sell unwanted relics in exchange for Shards.

- Standard sales include a 10% transaction fee.
- Bulk selling is available through a one-tap **Spare** option.
- Spare sales preserve the cleanest copy of each relic.
- All variants are automatically protected from bulk selling.

### The Sky

The Sky is a rotating market modifier that changes every three minutes.

At each rotation:
- One rarity becomes **Ascendant**, receiving a +50% value modifier.
- Another rarity becomes **Waning**, receiving a -25% value modifier.

### Market Events

Special market events periodically affect the economy.

| Event | Description |
|---|---|
| Meteor Shower | Special market-wide event |
| Market Crash | Market-wide value decrease |
| Collector's Craze | Increased collector activity |
| Variant Fever | Special focus on variant relics |

All market events operate on a shared timer.

### Daily Bounties

- Three daily bounties are available.
- Each bounty rewards significantly more Shards than the ordinary sale value of its required relics.

### Collector Offers

Limited-time collectors periodically appear with requests for specific relics.

- Collectors offer premium payouts.
- Collector transactions have no market fee.
- Offers expire after a limited period.

### Alms System

Players with fewer than 100 Shards can receive 300 Shards through the Alms system.

- Provides 300 Shards per claim.
- Available once every 30 minutes.
- Only available while holding fewer than 100 Shards.

### Additional Market Features
- **Quick Sell:** Instantly sell an individual relic directly from its results screen.
- **Trade-Up Contracts:** Exchange 10 relics of one rarity for one relic of the next rarity.
- Trade-up contracts carry forward the average erosion value of the submitted relics.

---

# 4. Collection and Progression

The collection system provides long-term goals beyond simply opening cases.

### Collection Grid

Players can browse their relic collection using the following filters:

- All
- Owned
- Missing
- Variants
- Eclipse

Each relic tile displays its current copy count.

### Codex

Every relic has an individual Codex entry containing:
- Relic lore and background information.
- A collection history line unlocked after obtaining three copies.
- A visual indicator for discovered variants.

### Star Chart

The Star Chart contains six constellations.

Completing each constellation rewards a one-time Shard bonus.

| Constellation | Completion Reward |
|---|---:|
| 1 | 300 Shards |
| 2 | 600 Shards |
| 3 | 1,000 Shards |
| 4 | 2,000 Shards |
| 5 | 5,000 Shards |
| 6 | 3,000 Shards |

**Total Possible Reward: 11,900 Shards.**

### Chronicle

The Chronicle contains six story chapters.

- Each chapter corresponds to a completed constellation.
- Completing a constellation unlocks the next chapter.
- Provides additional lore and progression context.

### Achievements

- 36 total achievements.
- Achievement unlock popups.
- Rewards and recognition for completing specific milestones.

### Player Statistics

The statistics interface tracks:
- Luck percentile.
- Actual pulls compared against stated drop odds.
- Average relic erosion.
- Complete Shard transaction ledger.
- History of the last 20 case openings.

---

# 5. Challenge System

Challenges provide separate gameplay modes with controlled rules and competitive opportunities.

### Available Challenge Modes

| Mode | Description |
|---|---|
| Gauntlet | Consecutive challenge-based openings |
| Ironman | Restrictive progression challenge |
| Pity Speedrun | Race to reach the pity guarantee |
| Clean Hunt | Challenge focused on obtaining low-erosion relics |

Each challenge mode uses a separate collection that is restored after the challenge ends.

### Seed System

Players can enter custom seeds or select:
- Random
- Daily

Players using the same seed receive identical relic pulls, allowing for fair comparisons and competitive challenges.

### Daily Gauntlet
- Daily challenge streak counter.
- First-clear Shard bonus.
- Repeatable challenge participation.

### Challenge Results

The results interface includes:
- Personal best records.
- Challenge performance summaries.
- A **Copy Result** button for sharing results.

---

# 6. Sharing and Content Creation

The game includes tools designed to make relic discoveries easy to share and record.

### Share Cards
- Generates a visual share card for individual relic discoveries.
- Supports downloading through a long press on the generated PNG.
- Includes a Copy Text button.

### Record Mode

A dedicated interface for recording gameplay.

- Hides unnecessary interface elements.
- Tap the screen to open a case.
- Press Space to open a case.

### Keyboard Shortcuts

| Key | Action |
|---|---|
| O | Open one case |
| T | Open ten cases |
| M | Open the Market |
| Space | Open a case in Record Mode |

---

# 7. Saving and Data Protection

Player progression must remain protected against accidental resets and corrupted save data.

### Save Codes
- Export player progress into a pasteable save code.
- Import save codes to restore player progress.

### Backup System
- Versioned saves.
- Automatic backups.
- One-tap backup restoration.

### Corruption Recovery

If a save becomes corrupted:
1. The game attempts to restore the most recent valid backup.
2. If recovery is unsuccessful, the game starts a fresh save.
3. The player receives a notification explaining what happened.

### Undo Protection
- Importing a save automatically creates a backup first.
- Resetting progress automatically creates a backup first.

### Reset System
- Resetting requires a two-tap confirmation.
- Prevents accidental deletion of player progress.

---

# 8. Settings and Accessibility

The game should remain accessible and comfortable across different devices and player preferences.

### Settings

Available settings include:
- Reduce Motion.
- Colorblind-Safe Rarity Shapes.
- Haptics.
- Volume Slider.

### Saved Preferences

The following settings persist between sessions:
- Fast Open.
- Chat.
- Sound.

### Accessibility
- Screen-reader labels for dialogs and relic tiles.
- Proper keyboard navigation.
- Keyboard focus management within popups.
- Distinct rarity shapes for colorblind accessibility.

### First-Run Guide

A short onboarding experience introduces new players to the game.

- Explains the primary mechanics.
- Introduces case opening and the Market.
- Explains relic rarities and collection progression.
- Can be reopened at any time through **How to Play**.

---

# 9. Visual Design and Technical Performance

### Visual Identity

The game uses a **Gilded Celestial** aesthetic.

Core visual elements include:
- Gold and violet accents.
- Celestial and constellation-inspired interfaces.
- Procedurally generated relic artwork.
- Distinct rarity visual effects.
- Synthesized sound effects.
- Atmospheric case-opening animations.

### Interface Layout

**Mobile Layout**
- Optimized phone interface.
- Sticky Open bar for easy access to case openings.
- Touch-friendly navigation and controls.

**Desktop Layout**
- Two-column interface.
- Expanded collection and market views.
- Keyboard shortcut support.

### Performance Optimization

The game should remain efficient, particularly on mobile devices.

- Idle animations operate at half speed.
- Animations pause when their elements are off-screen.
- Reduced unnecessary rendering helps conserve battery.
- Reduce Motion settings provide an additional accessibility option.

---

# 10. Core Game Design Goals

The overall experience is built around five primary pillars:

1. **Discovery:** Make every case opening exciting through animations, rarity reveals, and near-miss moments.
2. **Collection:** Give players long-term objectives through relics, variants, patterns, constellations, and achievements.
3. **Economy:** Create meaningful decisions around selling, collecting, trading up, and timing market transactions.
4. **Competition:** Encourage replayability through seeded challenges, daily gauntlets, and personal bests.
5. **Accessibility:** Deliver a polished experience across mobile and desktop while protecting player progress and supporting different accessibility needs.

**Project Vision:** Create a celestial relic-collecting experience where every discovery has value, every collection has a story, and every opening has the potential to become memorable.
