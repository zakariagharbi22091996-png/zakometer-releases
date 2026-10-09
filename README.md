# Zakometer: a local DPS meter for Aion 2

> **⚠ Use at your own risk.** Zakometer is a third-party tool. It only *reads* the game's
> network traffic on your PC (like every DPS meter): it never touches the game, never
> injects anything, never automates anything. NCSoft has not banned personal meters; their
> warning (May 2026) was about tools that collect and publish other players' data without
> their consent. Zakometer shares your boss fights on its stats site with every player by
> their class only, never by their name (yours only if you choose). Still, no third-party
> tool is risk-free, and NCSoft can change its rules at any time.
> Not affiliated with NCSoft.

**[⬇ Download the latest Zakometer.exe](https://github.com/zakariagharbi22091996-png/zakometer-releases/releases/latest)**

![The overlay in a dungeon](screenshots/1_overlay.png)

## What it does

- **Live overlay**: you and your party, damage / healing / damage taken, boss HP and time
  left, your resurrection stones, where you are (dungeon and mode, Transcendence, Nightmare
  level, Abyss, arena). In the open world, random players are hidden, except on a field boss
  or an event.
- **Room check**: join a room and see who is in it before the run: class, item level,
  combat power, who leads. Anyone on your blacklist shows up in red.
- **Dungeon summary** when you leave: everyone's damage over the whole run, bosses, fights,
  skills, advice, and a **Deaths** tab: what killed each player in their last 10 s, and the
  damage everyone took from each boss skill (who keeps eating the mechanics). Nothing pops
  up during the run.
- **Why this DPS?**: right-click any player, or yourself: what holds them back, biggest first,
  each fix priced in % of DPS (rotation, skill levels, manastones, gear). Works for every class.
- **PvP logs**: each death / kill / assist with the 20 s before it, and the enemies' rotation
  skill by skill.
- **My progress**: item level, combat power, critical hit, your DPS week by week, one boss
  in detail.
- Optional: a soft sound when a skill is ready (you pick the skills, the sound and the
  volume), buff and debuff uptime, blacklist / whitelist with your own notes, copy the
  overlay as a picture for Discord.

Comparisons are always like for like: same boss, same difficulty, same level (Nightmare 10
is never set against Nightmare 1, Conquest never against Exploration).

| | |
|---|---|
| ![Room check](screenshots/2_room_check.png) | ![Dungeon summary](screenshots/3_dungeon_summary.png) |
| ![Deaths tab](screenshots/4_deaths_tab.png) | ![Why this DPS?](screenshots/5_why_this_dps.png) |
| ![PvP logs (example fight)](screenshots/6_pvp_logs.png) | ![My progress](screenshots/7_my_progress.png) |

*Player names in the screenshots are changed.*

## Install

1. Download `Zakometer.exe` and run it. If Windows says "Windows protected your PC":
   *More info* → *Run anyway* (the file is not code-signed).
2. The first time, Zakometer offers to install **Npcap** (free, needed to read the network
   traffic): *Install Npcap* → Yes → *I Agree* → *Install*.
3. Play Aion 2 in windowed or borderless mode. Your character is recognised the next time
   you change zone or teleport.

## Privacy and Zakometer Logs

Your **boss fights** go to **[Zakometer Logs](https://zakometer.pages.dev)**, the free stats site
(DPS of every class on every boss and level, rankings), when they end: damage, skills,
deaths, combat power rounded to 5K. **Every player by their class only, never by their name**;
your own name only if you turn it on (Settings → *Show my name on Zakometer Logs*). Turn the
sharing off at any time: Settings → *Share my boss fights*.

Nothing else leaves your PC. Zakometer also goes online to check this page for a newer
version (nothing about you is sent; you can turn it off) and when **you** search a character
(NCSoft's official site).

## Updates

When a newer version is out, the overlay says so: menu ☰ → **Update** downloads it, closes
Zakometer, replaces the file and starts it again.
