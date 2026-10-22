# Beijing Offsite — Venue Research (from the Wangfujing office)

**Date:** 2026-10-22
**Starting point:** our Wangfujing office (Wangfujing Station area, Dongcheng District — 39.9080, 116.4114)
**Travel mode:** public transit (Beijing Subway)
**Companion workbook:** `beijing_offsite_plan.xlsx` (sheets: `Venues`, `Shortlist` — shared separately)

---

## Candidate list from our last sync

| Venue | District | Status |
|---|---|---|
| Jingshan Park | Xicheng | Active |
| Purple Bamboo Park | Haidian | Renovating |
| Temple of Heaven | Dongcheng | Active |
| Beijing Ancient Observatory | Dongcheng | Active |
| Beihai Park | Xicheng | Backup |

**Two candidates were dropped before the shortlist:**

- **Purple Bamboo Park** (Haidian) — currently **renovating**, so it is treated as unavailable.
- **Beihai Park** (Xicheng) — **backup only**, and per our sync decision it must not be shortlisted.

That leaves the three Active venues compared below.

---

## Three-venue comparison

| Venue | Address (Google Maps) | Transit from the office | Elevation |
|---|---|---|---|
| Jingshan Park | 44 Jingshan West St (景山西街44号), Xicheng District, Beijing 100009 | ~30 min | 50.79 m |
| Temple of Heaven | 1 Tiantan East Rd (天坛东路1号), Dongcheng District, Beijing 100061 | ~25 min | 46.04 m |
| Beijing Ancient Observatory | 2 Dongbiaobei Hutong (东裱褙胡同2号), Dongcheng District, Beijing 100005 | ~15 min | 40.68 m |

> **Data provenance:** Addresses and elevations are direct Google Maps outputs (Places / Elevation APIs); elevation is ground-level terrain at the venue. Transit routing could **not** be pulled from the Google Maps API for Beijing (the service returns `ZERO_RESULTS` for transit mode in this region — only driving and walking are served here). The transit times above are therefore **estimates** assembled from the Beijing Subway network (lines and interchanges) plus walking legs measured via Google Maps walking mode (e.g. Jianguomen Station → observatory: 3 min / 194 m). Treat them as planning estimates rather than API-verified door-to-door times.

---

## Recommendation: Beijing Ancient Observatory (北京古观象台)

**Address:** 2 Dongbiaobei Hutong (东裱褙胡同2号), Dongcheng District, Beijing 100005
**Phone:** +86 10 6524 2202 · **Hours:** daily 09:00–17:00 · **Rating:** 4.5
**Transit time from the office:** ~15 min — the shortest of the three
**Elevation:** 40.68 m

**Why it wins:** it is the closest Active venue to our Wangfujing office by transit, by a clear margin (15 vs 25 vs 30 min). It sits right beside Jianguomen Station, which is a straight two-stop ride on Line 1 from Wangfujing — no transfers at all — followed by a 3-minute (194 m) walk. It is a compact, well-rated historic site (observatory with beautifully preserved 15th–17th-century astronomical instruments; roughly 45–60 minutes to see, plus the 60-step tower climb), which suits a half-day session with a wander and a view.

**Route summary (subway):**

1. Walk to **Wangfujing Station** and take **Line 1 eastbound**.
2. Ride **2 stops** — alight at **Jianguomen** (passing Dongdan).
3. Exit on the north side and walk ~194 m (~3 min) to the observatory entrance at 2 Dongbiaobei Hutong.
4. Total door-to-door: **~15 minutes**.

*For reference — the runner-up routes: Temple of Heaven = Line 1 two stops to Dongdan, transfer to Line 5 southbound three stops to Tiantandongmen, then a walk to the East Gate (~25 min total). Jingshan Park = Line 8 northbound two stops to the National Art Museum of China station, then ~1 km on foot to the park's south gate (~30 min total).*

---

*All address/elevation data: Google Maps. Please comment on this PR with any corrections or a +1 for the pick.*
