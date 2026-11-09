# YouTube Trends — Tableau Dashboard

Interactive Tableau Public dashboard analyzing which YouTube video categories trended most often across five regions (France, India, Japan, Russia, United States) between November 2017 and June 2018.

TripleTen Data Analyst program project — Mara Torres Blanco.

## Dashboard

**[View the interactive dashboard on Tableau Public](https://public.tableau.com/views/YouTubeTrendsAnalysis_17778719969020/DashboarddeTendenciaYoutube)**

The dashboard has date and region filters and three main views: trending history by number of videos, trending history as a percentage, and distribution by category.

## What this project does

Built for the advertising agency Sterling & Draper, this project answers the team's recurring questions:

- Which video categories trended most frequently?
- How were those categories distributed across regions?
- Which categories were especially popular in the United States, and how did the US differ from other regions?

## Tools

- Tableau Public (interactive dashboard)
- Data: CSV (`trending_by_time.csv`)

## Data

`trending_by_time.csv` — **12,343 daily records**, November 14, 2017 – June 14, 2018, covering 5 regions. Columns: `record_id`, `region`, `trending_date`, `category_title`, `videos_count`.

The dataset **is included in this repository** (`trending_by_time.csv`).

## Key findings

### Most frequent trending categories (all regions)

- **Entertainment** dominates with **95,008** trending videos — more than double the second category.
- Followed by **People & Blogs** (44,700), **Music** (34,390), and **News & Politics** (34,202).

### Distribution by region

| Region | Total videos | % of total |
|---|---|---|
| United States | 80,758 | 24.1% |
| France | 75,404 | 22.5% |
| Russia | 73,694 | 22.0% |
| India | 73,372 | 21.9% |
| Japan | 36,762 | 11.0% |
| **Total** | **340,990** | **100%** |

The four largest regions are very close (22–24% each). Japan has notably lower trending activity (11%), which may reflect different content-consumption behavior in that region.

### United States vs. other regions

- Entertainment also leads in the US (19,638), but **Howto & Style** (8,280) and **Science & Technology** (4,722) carry proportionally more weight in the US than elsewhere — a differentiated opportunity for campaigns targeting the US market.
- In other regions, People & Blogs and News & Politics are relatively more important.

## Conclusions

- Entertainment is the safest bet for mass-reach campaigns in every region.
- Music and People & Blogs have large, consistent audiences everywhere — good for branding and awareness.
- For US-focused campaigns, Howto & Style and Science & Technology are key categories.
- Strategies for Japan should adapt to local consumption patterns rather than copy the Western model.

## Project structure

```
youtube-trends-tableau-dashboard/
├── trending_by_time.csv          # Source dataset (12,343 records)
├── youtube_trends_analysis.pdf   # Written presentation with findings (in Spanish)
├── README.md
└── .gitignore
```

## Notes

- This project has no Python notebook — the analysis and visualization were done entirely in Tableau Public.
- The presentation PDF is in Spanish; the dashboard itself is the main deliverable.
