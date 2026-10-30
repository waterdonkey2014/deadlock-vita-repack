# Deadlock for PS Vita: the repack app (unofficial)

**Status: planning. Nothing released yet.** The first public build, V1, will be the first one that boots and loads a map.

An unofficial fan project. The repack app turns **your own** installed copy of Deadlock (PC or Mac) into a pack for the PS Vita,
played on our own Vita engine.

- **This repo only ever holds our code:** the repack app and the Vita engine. It never contains Valve's files, or anything converted
  from them. You need your own install; the app reads it on your computer.
- **Not affiliated with or endorsed by Valve.** Deadlock is a trademark of Valve Corporation.

## How releases will work
- From V1 on, a new build comes out with every kit (roughly one a week). Each release has notes, a "what to test this week" list and
  known issues.
- The repack app updates itself from this repo's Releases and tells you when a new Vita build is ready.
- **You** copy the pack to the Vita (USB or VitaShell FTP) and install it in VitaShell. The Vita never downloads or installs anything
  by itself.
- When there's online play, it is against bots, Vita-to-Vita, and servers run by this project.

## What you'll need (once V1 is out)
- A PS Vita running homebrew (HENkaku / Ensō) with VitaShell.
- `libshacccg.suprx` extracted on your own Vita with ShaRKF00D (the app's guide walks you through it).
- Your own Deadlock install on PC or Mac.

## Reporting bugs
Open an issue with the **Debug report** form. The repack app makes the report zip for you.

Reports are **public**. The app removes personal details from its logs and shows you exactly what will be posted. Please don't add
personal info yourself, and never attach game files.
