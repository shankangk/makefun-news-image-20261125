# makefun-news-image-20261125

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/shankangk/makefun-news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/shankangk/makefun-news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

A newspaper front page summing up Wednesday, November 25, 2026: a Houthi drone strikes Riyadh's tallest tower for the second time in a week, Shanghai's party chief falls in Xi's purge, and Shenzhou-24 carries the first foreign astronaut to China's space station, plus a hostage siege in Cartagena, a killing in Gaza, and more.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## What the image shows

- **Lead story — Riyadh tower hit again:** A Houthi drone struck the 80-storey, 385-metre Public Investment Fund Tower in Riyadh's King Abdullah Financial District on Tuesday — the second hit in less than a week. Eleven people were injured, two critically, among them Saudi, Egyptian, Nepalese and Indian nationals. The Saudi-led coalition blamed the Houthis and called it a "terrorist attack"; the Houthis claimed last week's strike on the same tower but announced no fresh attack on Tuesday. The tower, home to Saudi Arabia's sovereign wealth fund, was also hit the previous Thursday. An Aramco tower in the same district was struck earlier in November, and Riyadh airport was hit repeatedly in October, one attack killing 14.
- **Chen falls in Xi's purge:** Shanghai party chief Chen Jining, 62, a member of China's elite Politburo once seen as a possible successor, was placed under investigation for "serious violations of discipline and law", Xinhua announced on Tuesday. He is the fourth Politburo member to fall since 2025 and the first sitting Shanghai chief to be probed since Chen Liangyu in 2006. Shanghai's party leadership swiftly pledged loyalty to Beijing.
- **Shenzhou-24 lifts off:** China launched Shenzhou-24 at 8:18 a.m. on Wednesday from Jiuquan, carrying commander Tang Hongbo, flight engineer Wu Yi and Pakistani payload specialist Muhammad Zeeshan Ali — the first foreign astronaut aboard the Tiangong space station and the first Pakistani in orbit. Ali will spend about a week aboard conducting joint experiments and return on Shenzhou-23.
- **Also:** Gunmen held about 30 people hostage in an Éxito supermarket in Cartagena, Colombia, after a failed armoured-car robbery; 10 were freed, five of them elderly women, and about 20 remained held as police and troops surrounded the store. An Israeli airstrike in Gaza killed Hamas internal security chief Naim Abu Nahal despite the ceasefire. A US jury convicted Huawei of stealing trade secrets. An airstrike on trucks and buses in Yemen's Lahj province killed 26, including 14 civilians. President Trump awarded Rudy Giuliani the Medal of Freedom and pardoned the Thanksgiving turkeys.

## How it was built

Three editorial illustrations were generated with AI image tools (a damaged skyscraper in Riyadh's financial district, Shanghai's skyline under storm clouds, a Long March rocket lifting off), then composed into one 1024×1024 poster with Python (PIL). Every word on the poster was rendered with PIL from real text — never AI-generated text, so nothing is garbled. `main.ts` copies the finished `entry.png` to `/output/entry.png`, deterministically, with no network.

---

<sub>Entered on [make.fun](https://make.fun/?ref=shankangk&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards</sub>
