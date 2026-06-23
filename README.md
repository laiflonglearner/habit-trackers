# Habit Trackers

A running log of habit tracking apps I've tried.

## Format

Each tracker gets its own section with:

- **Website**: link to the app
- **Tried for**
- **Repository**: link to source, if available
- **Tech stack**: for the curious
- **What it does well**
- **What needs improvement**
- **Rating**: `x/10`
- **Would I recommend it**: yes / no / depends on who
- **Review note**: how current this review is, last time I actually checked in

---

## Habitica

- **Website**: [habitica.com](https://habitica.com)
- **Tried for**: Consistently from Sept 2021 to Feb 10, 2022 (about 5 months, 155 check-ins), then stopped actively using. Still check in occasionally to review old data and follow community updates.
- **Repository**: https://github.com/HabitRPG/habitica
- **Tech stack**: Website built on Node.js, Express, Tailwind CSS, hosted on Google Cloud (hosting + CDN). More details soon.
- **What it does well**:
  - The RPG layer (levels, HP, gold, party) made daily habit tracking genuinely fun. Completing your habits and tasks earns potions, pet eggs, and gold (the amount depends on your class). The gold you get can be spent on items in the market or on an enchanted armoire, which works like a gacha system. The gamification is well-designed.
  - The damage/redness indicator gives an intuitive, immediate signal of how badly a habit is being neglected.
  - The party system adds real social accountability. Missing dailies hurts your party too, since you'll do less damage to monsters, which means the quest takes longer to finish. I remember getting kicked from a party because I dealt good damage to the boss, but also took a lot of damage from missed dailies. A party needs a good healer who are willing to spend their mana to cast their blessing skills to cover that kind of damage and without one, that imbalance becomes a liability for the rest of the party :) the feature to look for a party on the platform seems to have already been removed, and there's a new group feature for premium users instead. So to progress while slaying monsters, you now need to invite your friends manually to your party or join theirs.
  - User-hosted Challenges are one of my favorite features. I won 2 of them. The back-and-forth with one of the hosts turned this app into something genuinely memorable <3
  - It lowered the barrier to entry for someone new to self-development journey. Bettering yourself can feel overwhelming and Habitica reframed that into something artistic, fun and enjoyable.

- **What needs improvement**:
  - No built-in long-term progress view. Even the unofficial Habitica User Data Display Tool, which pulls history via user ID and API key, only shows some of your habit logs instead of the entire history. Because of this, I'm no longer able to see my habit data for the 5 months I was active, since I lost my old screenshots and this tool's data doesn't go back that far either.
  - To me personally, the reward/damage system reflects "are you currently on track?", which is useful, but it lacks "are you actually getting better at this habit over time?" I tracked consistently for 5 months straight but had no idea how well or poorly I was doing with the habit. How many days did I miss per week? When was my peak day or low day? Did I do well this month? This gap is what eventually made me leave the app and move to Notion at the time.
  - Skills and stat buffs can mask the real consistency you made. A habit can look fine on the surface because a buff softened the damage (especially if your class is Rogue), not because the habit itself improved. This is fine, since those gamified items are part of the fun, but I wish there was a feature showing the real percentage, how many times you missed a habit vs. how many times you completed it.

- **Rating**: 8.5/10 (this app helped me a lot at the beginning of my self-development journey. It made me believe I don't need to suffer while improving myself, that bettering myself can be fun too. But the progress-tracking gap is still there and it's one of the reasons I moved to another app)
- **Would I recommend it**: Yes, specifically for people who find productivity overwhelming and thrive with gamification. Not ideal if long-term progress visibility is your main drive to keep going since the data model is built for daily and social accountability, not long-term insight. If that's what you're after, Notion or Google Sheets will likely serve you better.
- **Review note**: Based on active use from Sept 2021 to Feb 2022. Habitica continues to evolve, and the paywall structure and feature availability may differ now. Occasional check-ins I do since then suggest the core mechanics remain similar.
