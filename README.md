<p align="center"><img src="readme/avo_logo.png" width="72" alt="AVO"></p>

# ตำโมจิ (Mochi Pound) — gift commands

![ตำโมจิ](cover.jpg)

**An AVO game** · free in the **AVO Play** app · © 2026 AVO (AOTGTR). All rights reserved.

A TikTok live rhythm game: the streamer pounds mochi on the beat; viewers' gifts order mochi (prank) or send help. This repo is the
command page only — each gift command with a short clip of what it does in the game.

**Page:** https://command-by-avo.github.io/mochi-commands/ (also opened by the "คำสั่ง + คลิป" button in AVO Play)

| สั่ง (แกล้ง) | สุ่มแกล้ง | ช่วยตำ | x2 เร็ว |
|---|---|---|---|
| ![order](media/order.jpg) | ![random order](media/r_order.jpg) | ![help](media/help.jpg) | ![speed](media/speed.jpg) |

## Commands
- `order N` — a viewer orders N mochi (prank: the streamer has to pound them)
- `random order LO HI` — สุ่มแกล้ง: a pink card rolls LO..HI pieces
- `help N` — a helper pounder makes N pieces
- `random help LO HI` — สุ่มช่วย: a gold wheel lands on N helper pieces or x2 for N seconds
- `speed N` — x2: the turner turns twice as fast for N seconds
- Combo bonus: every 50 of the same gift in a row rolls +1..100 pieces (no command needed)

Gift → command mapping is the AVO Play web preset `avoMochi` (edited in the AVO Play app).

Part of [Command BY AVO](https://github.com/Command-BY-AVO) — one page per game, gift commands + clips.
