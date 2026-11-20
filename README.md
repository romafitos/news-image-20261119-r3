# news-image-20261119-r3

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/romafitos/news-image-20261119-r3/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/romafitos/news-image-20261119-r3/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

THE WORLD IN ONE DAY — a one-page front page summing up 19 November 2026 in a single image. Three giant chronological spine pins (Iran hits Kuwait 13:25, Kerch hit again 23:36, trilateral meets 06:30), six top stories with WHAT CHANGES lines, a real world map whose dot colour is the hour, a numbers panel tied to timed stories, and a time-act-grouped index of the rest of the day. 45 stories, seven regions, every story first reported in the 19 November 2026 news cycle.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The program is Python 3.13, standard library only, with no network access at runtime. It writes `entry.png` (1024x1024, under 1 MiB) to `/output`, or to `MAKEFUN_OUTPUT_DIR` when that variable is set. All text is drawn from an embedded bitmap font typed into the program; the three hero illustrations are pasted from PNG files in this folder, with code-drawn panels as fallback if a file is missing. Two runs write byte-identical output.

Time convention: all times are UTC. Event time where on record; first-report time is marked with an asterisk, defined in the masthead, the map title, and the footer. A story with no verifiable time is labelled with its report date and no time. No time is invented.

Sources: every story, time, and source is recorded from the 19 November 2026 news cycle (Reuters, TBS News, White House / TASS, CNN, Al Jazeera, NPR, AFP, and others, as cited on the page). The DATE CHECK footer names the stories deliberately left out because they broke before this cycle.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
