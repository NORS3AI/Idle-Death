# Idle-Death

An idle game like LARP TYCOON richman idle

## Play

**🎮 https://nors3ai.github.io/Idle-Death/**

> Note: GitHub Pages URLs are case-sensitive. The username subdomain is
> always lowercase (`nors3ai`), but the repository path must match the repo
> name exactly — `Idle-Death` — so `/idle-death/` will **not** work.

## About

Idle Death is a clicker game that becomes idle over time. Tap the reaper to
collect souls, then spend them on reapers and upgrades that harvest souls on
their own — even while you're away. Progress saves automatically to your
device.

It plays great on iOS: double-tap zoom and text selection are disabled so
tapping never accidentally zooms the page or highlights text.

## Features

- **Tap to reap** souls, with a global multiplier that scales everything.
- **9 businesses**, each with **10 upgrades** that double its output.
- **Vehicles** — bicycles, motorcycles, cars, sports cars, speed boats,
  mega yachts, helicopters, private jets and a death rocket — each a
  permanent income multiplier.
- **Real estate** — apartments through to a whole necropolis city.
- **Museum & Stock Exchange** — priceless artifacts (vase, masterpiece,
  cursed crown, dino fossil, Hope Diamond, soul meteorite) that trade like
  stocks with fluctuating prices; holding shares also boosts income.
- **Spin to Win** — a prize wheel with a free spin every 30 minutes (or pay
  souls), giving cash, temporary income boosts, free vehicles, reaper coins
  and a jackpot.
- **Prestige** — reset for permanent prestige points (+3% income each).
- **Achievements** — 24 milestones, each granting a permanent reward.
- **Idle & offline progress** — your empire keeps earning while you're away.
- Buy in **×1 / ×10 / ×100 / MAX** amounts, with export/import save codes.

## Run locally

The game is a single self-contained `docs/index.html` (GitHub Pages serves
from the `/docs` folder on `main`). Just open it in a browser, or serve it:

```bash
python3 -m http.server 8000 --directory docs
# then visit http://localhost:8000
```
