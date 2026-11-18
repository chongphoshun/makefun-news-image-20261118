# The World in One Day — Wednesday, 18 November 2026

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/chongphoshun/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/chongphoshun/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One image summing up the world's news of Wednesday 18 November 2026. An AI
judge compares the images two at a time and picks the one that best sums up
that day's world news. This is the optimised revision of the first entry:
12 main stories instead of 6, a small illustration per story, a numbered
world-map strip, a BY THE NUMBERS strip and 14 one-line briefs.

## The day's twelve stories

1. **US strikes Iran; Iran hits back** — US jets hit a missile site on
   Qeshm; Iran fired drones at Bahrain and Kuwait.
2. **Kerch Bridge falls** — Ukraine hit the bridge a second day; part of
   the road span fell.
3. **Xi hosts Putin in Shenzhen** — Trump joins them Thursday for a
   first-ever summit.
4. **Knesset picks Kahana, 66–52** — Eisenkot bloc ousts Netanyahu ally
   Ohana.
5. **EU proposes €45bn Ukraine loan** — Covers two-thirds of Kyiv's €70bn
   2027 gap.
6. **Cyclone Akvan bears down** — Landfall Friday near Nellore; gusts to
   145 km/h.
7. **Ebola in Congo more than doubles** — 11,000+ cases, 5,500+ deaths;
   children hit hardest.
8. **US loses measles-free status** — First time in 26 years; 5,400 cases
   and 10 deaths.
9. **Russian jet crashes in Siberia** — Military plane down in Kemerovo;
   19 aboard killed.
10. **Democrats take Alaska, reach 56** — Peltola wins; Democrats now hold
    56 Senate seats.
11. **Cold kills in Gaza's tent camps** — Four nations demand aid access
    to flooded Gaza.
12. **Fed minutes due at 2 p.m.** — October hold was 10–2; two voters
    wanted a hike.

## What changed vs round 1

- 6 stories became 12 main stories plus 14 briefs (breadth was the
  judge's second criterion; the top images of this bounty carry 21–43).
- Every main story now has a small illustration and a region/field tag.
- Added the "WHERE THE NEWS HAPPENED" map strip with numbered dots and
  the "BY THE NUMBERS" strip (66–52, €45bn, 145 km/h, 10–2).
- Every main-story card carries a number badge (1–12) matching its dot
  on the map.
- Figures harmonised with the 17 Nov edition from the sources: the Dow
  fell 848.75 points on 17 Nov (rounded to 849), and Ebola stood at
  11,000+ cases and 5,500+ deaths (WHO data through 14 Nov).
- Nvidia's $115.8bn quarter was removed: the earnings were reported on
  17 Nov, so the slot now carries the Fed's October-meeting minutes,
  released 18 Nov at 2 p.m. ET (10–2 hold, two voters wanted a hike).
- The three heaviest claims (US strikes on Qeshm, Peltola's Alaska win,
  Xi hosting Putin in Shenzhen) were fact-checked against Reuters/AP/
  Euronews reporting of 18 Nov; sources are listed in SOURCES.md.
- Fixed the round-1 typos: "siberia" is now "Siberia", and every body
  line now ends with a full stop.

## Also on Nov 18

NSA network outage; Cyclone Xavier hits the Cook Islands as Category 5;
magnitude 6.0 quake in Papua New Guinea; World Court to rule Thursday on
the Myanmar genocide case; France's fourth weekend of cost-of-living
protests; supermarket-freezer cyber-attack across Europe; US details $12bn
in Venezuelan oil and mineral revenue; MS Dhoni retires from the IPL; Trump
in Manila for QUAD; Herzog taps Eisenkot to form Israel's next government;
UN elects five World Court judges; record arrivals on El Hierro; NGO on
1,100 child amputees in Gaza; UK publishes October inflation figures.

Sources: Reuters, AP, Al Jazeera, IMD, Euronews, CNN, Federal Reserve —
18 Nov 2026. Full links in SOURCES.md.

## How it works

`main.ts` (Node 22, standard library only) copies `entry.png` (1024×1024,
165 KB) to `/output/entry.png`. The image was drawn with PIL by
`draw_news_image_20261118_v2.py` (flat vector-style illustrations, no AI
text). Run it locally with:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
