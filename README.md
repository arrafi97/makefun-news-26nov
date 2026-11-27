# Sum up 26 November's world news in one image

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/arrafi97/makefun-news-26nov/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/arrafi97/makefun-news-26nov/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

Entry for the make.fun bounty [Sum up 26 November's world news in one image](https://make.fun/bounty/news-image-20261126):
a newspaper front page for Thursday 26 November 2026, drawn by hand as
HTML/CSS/SVG in `entry.html` and rendered to a 1024×1024 PNG in this session.

The front page carries **48 dated, verified stories across 10 regions**: a hero
row on Macy's 100th Thanksgiving parade being postponed by a nor'easter, Saudi
defences downing two Houthi missiles over Riyadh, and India marking 18 years
since the 26/11 Mumbai attacks (plus 77 years of its Constitution); 13 more
illustrated stories (tankers burning in Hormuz, the EU budget and Ukraine
loan summit, Gukesh–Sindarov Game 3, the Cairo tanker fire, the Kyiv mall
strike, US tariffs on 14 economies, the Bank of Korea's rate rise, US growth
revised to 4.3%, the Gaza strikes, Kim's nuclear call, Shenzhou-24 and the
Hera asteroid images, the Congo Ebola outbreak, Australia's AI-driven capex
jump); a world map with pins 1–16; a UTC timeline; "how sure" labels
(OFFICIAL / CONFIRMED / REPORTED / CLAIM) on every illustrated story; a date
check that leaves out other days' news (the 19 Nov Shenzhen trilateral, the
24 Nov Copa América announcement, the 25 Nov Ras Tanura claim and Google
lawsuit); and 32 more stories in the "And also" list. Every figure was
checked against reporting published on 26 November 2026 — see `SOURCES.md`.
The PNG is optimised to a 256-colour palette, 115,584 bytes.

`main.ts` (Node 22, standard library only, no network) writes the image to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). The PNG bytes are
embedded in `main.ts` as base64, so the program is fully self-contained and
deterministic — both runs write the same bytes.
