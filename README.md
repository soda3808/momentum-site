# Momentum — Notion templates

Static marketing site for the Momentum range of Notion templates. Plain HTML, no build step, served by GitHub Pages.

**Live site: https://soda3808.github.io/momentum-site/**

## Guides

Free step-by-step walkthroughs that work on Notion’s free plan:

- [How to Track Habits in Notion (Step-by-Step, Free Plan)](https://soda3808.github.io/momentum-site/how-to-track-habits-in-notion.html)
- [How to Track Expenses in Notion (Free Plan, No Bank Sync)](https://soda3808.github.io/momentum-site/how-to-track-expenses-in-notion.html)

## Template pages

- [Notion Habit Tracker Template with Streaks](https://soda3808.github.io/momentum-site/notion-habit-tracker.html)
- [Notion Finance Tracker Template — Budget & Expenses](https://soda3808.github.io/momentum-site/notion-finance-tracker.html)
- [Notion Life OS Template — Tasks, Habits, Finance in One](https://soda3808.github.io/momentum-site/notion-life-os.html)

Each page links to its Gumroad listing. Checkout, delivery and refunds are handled by Gumroad.

## Repository layout

| Path | What it is |
| --- | --- |
| `index.html` | Homepage and product index |
| `how-to-*.html` | Organic guides, one per target query |
| `notion-*.html` | Per-template landing pages |
| `sitemap.xml` | All published URLs, submitted via IndexNow |
| `robots.txt` | Crawl rules for this project path |
| `og-cover.png` | 1200×630 social card |
| `kensho-chart-toolkit/` | [Separate project](https://soda3808.github.io/momentum-site/kensho-chart-toolkit/) sharing this Pages host |

## Conventions

- Every page carries a self-referential canonical, `index,follow`, Open Graph and Twitter tags.
- Outbound CTAs are tagged `utm_source=seo&utm_medium=<page>&utm_campaign=momentum`.
- JSON-LD `offers.url` stays on the bare product URL, with no tracking parameters.
- New URLs go into `sitemap.xml` in the same commit that publishes them.

Sitemap: https://soda3808.github.io/momentum-site/sitemap.xml
