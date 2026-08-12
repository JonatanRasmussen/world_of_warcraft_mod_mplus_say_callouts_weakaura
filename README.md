
# /say Callouts M+ (by BudoBoy07)

---

### Highlights

This is an interface mod I developed for the WoW community and it ended up becoming quite popular (24.000 views / 1300+ downloads / 220 stars via the wago.io website, and an estimated 10.000+ additional in-game downloads via peer-to-peer WeakAura-sharing).

It uses event-driven logic to parse out dangerous spell casts from the combat log. I manually configured spell casting logic for 500+ spell_ids, and I did this for all 6 major game patches from 2023-2025 (DF season 2-4, TWW season 1-3), **[see my Wago.io page for more details](https://wago.io/6CDe7U7t6)**. This process included signing up for the beta or public test realm where I entered each upcoming dungeon to manually record the spell cast patterns of enemies (channeled/instant casts, duration, frequency, NPC-ID, etc.). To optimize for performance, I configured load-conditions based on zone_id and cast type in order to limit CPU-use.

This project was created via the WeakAura-framework (I used the in-game editor to generate Lua-code, so there's not much code to show here on GitHub). I did however have python code to test and validate the data I gathered in-game; this was done by cross-referencing my data with spell tables I scraped from the Wowhead website. These test- and scraping files are part of a separate repository: [LINK](https://github.com/JonatanRasmussen/wow_mythicplus_say).

**[See my Wago.io page for more details.](https://wago.io/6CDe7U7t6)**

---

### Website (link to Wago.io)

Like most other World of Warcraft Weakauras, my mod is hosted on **[this Wago.io page](https://wago.io/6CDe7U7t6)**.

---

### Showcase

This clip on YouTube shows the WeakAura's chat bubble functionality:

*[![(YouTube thumbnail screenshot, click to open on YouTube.)](https://img.youtube.com/vi/JSiVJAfD0WQ/0.jpg)](https://www.youtube.com/watch?v=JSiVJAfD0WQ)*

*(YouTube thumbnail screenshot, click to open video clip on YouTube.)*

If you are unfamiliar with World of Warcraft, this is what I want you to pay attention to:
Notice how my character at 0:02 says Swirls and at 0:11 my character says Traps.
These warnings happen 1-2 seconds before the harmful swirlie effects on the ground, which is obviously helpful.

---

### Features

It uses the WeakAura framework to automatically scan the combat_event_log for dangerous events. For each of its spell id configurations, it then creates a chat bubbles above your head when dangerous events and casts happen, warning you and your party members about important enemy abilities in World of Warcraft's Mythic+ dungeons.

Other Weakaura packs do a similar thing. However, this is an independant work, and I believe my package is pupular due to the increased focus on user experience. My weakaura creates chat bubbles instead of icons or sound alerts, and it is only triggered on the most dangerous abilities (I manually configure this for each dungeon). Also, each message is very short (only 1 or 2 words) and they are wrapped with raid markers, like this:
{cross} Dodge {cross}, {skull} Totem {skull}. These raid markers are displayed as a Skull or a Red X in-game, making them easy to parse visually in the middle of combat.

---

### How to Install

- Have World of Warcraft and the Weakaura addon installed.
- Go to the **[Wago.io page](https://wago.io/6CDe7U7t6)** and click "COPY IMPORT STRING".
- If the link goes down, check out the import_strings folder located inside this Github repo.
- Just like any other Weakaura import, type /wa while in-game and paste the string.

---

### Changelog

This Weakaura is distributed and managed on [Wago.io](https://wago.io/6CDe7U7t6).
Changelogs are visible there. My original (and now depracated) version of the Weakaura can also be found on Wago.io [using this link](https://wago.io/Zs6k2dJOt).

This WeakAura is a work-in-progress. I will update it for each new WoW M+ season, so stay tuned.

---

### Feedback and Comments

I am only responding to comments submitted at the [Wago.io](https://wago.io/6CDe7U7t6) page. Currently there are 50+ comments, and I reply to most questions and concerns.

---

### License

See the [LICENSE](./LICENSE) file for details.

