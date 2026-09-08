# Astral Blog Engine

**AI-Powered Automated Content Distribution System**

Built for [heyastral.ai](https://heyastral.ai) — a fully automated content engine that publishes 14 unique SEO blog posts per week across 5 platforms with zero manual effort.

## 🎥 Video Walkthrough

[![Watch the walkthrough](https://img.shields.io/badge/▶_Watch_on_Loom-14_min_walkthrough-blue?style=for-the-badge)](YOUR_LOOM_LINK_HERE)

Every node explained · All platforms demonstrated live · 14 minutes

## What It Does

An n8n workflow that runs twice daily (9am & 4pm) and handles the entire content pipeline automatically:

1. **Live Market Data Collection** — Pulls real-time data from Alpha Vantage, CoinGecko, and Fear & Greed Index simultaneously
2. **Market Research Processing** — Picks the most interesting market story, generates a unique angle from 10 rotating topics so morning and afternoon posts never overlap
3. **Claude AI Writes the Blog** — Produces a 1400-word SEO article with real numbers, hooks, quant deep-dive, feature showcase, disclaimer, and CTA
4. **Multi-Platform Distribution** — Formats and posts to all 5 platforms automatically, respecting each platform's character limits and formatting

## Platforms

| Platform | What Gets Posted |
|----------|-----------------|
| Dev.to | Full article with canonical URL → heyastral.ai for SEO authority |
| WordPress | Full HTML post with tags + CTA, Google indexed |
| Discord | Rich embed with clickable link in Astral Quants server (2000+ members) |
| Telegra.ph | Teaser post with CTA link back to heyastral.ai |
| Bluesky | Optimised hook under 290 chars for trading/finance audience |

## Results

- **14 unique SEO blog posts per week** — fully automated
- **14 new backlinks to heyastral.ai per week**
- Every post grounded in real live market data — different every run
- 10 rotating angles — no two posts cover the same topic
- Full SEO structure on every post — title, meta, slug, tags, canonical URL
- Google Sheets log so the client team can read every post with live URLs

## Technical Highlights

- Full audit and rebuild of a broken 34-node workflow
- WordPress OAuth API integration built from scratch
- 3-layer JSON parser — handles any Claude response format without errors
- Duplicate URL prevention — date + hour appended to every canonical URL
- Telegra.ph API integrated — works via server even when blocked regionally

## Tech Stack

`n8n` `Claude API` `Alpha Vantage API` `CoinGecko API` `WordPress API` `Dev.to API` `Telegra.ph API` `Discord Webhooks` `Bluesky API` `Google Sheets`

---

*Built by Aditya — AI Automation & Voice Agent Development*
