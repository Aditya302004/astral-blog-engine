# Astral Blog Engine

**AI-Powered Automated Content Distribution System**

Built for [heyastral.ai](https://heyastral.ai) a fully automated content engine that publishes 14 unique SEO blog posts per week across 5 platforms with zero manual effort.

## The Problem

Astral had a broken 34-node n8n workflow that wasn't working. Their blog was dead no consistent content, no SEO presence, and every post had to be written and distributed manually. For a trading/fintech platform trying to build authority, that's a huge missed opportunity. No backlinks, no organic traffic, no brand visibility.

## The Solution

I rebuilt the entire workflow from scratch and turned it into a fully automated content engine that runs twice a day without anyone touching it. Real market data goes in, finished blog posts come out published across 5 platforms, SEO-optimised, and logged for the team to review.

**The result:** 14 posts/week, 5 platforms, 14 weekly backlinks, zero manual effort.

## How It Works

An n8n workflow that runs twice daily (9am & 4pm) and handles the entire content pipeline:

1. **Live Market Data Collection** Pulls real-time data from Alpha Vantage, CoinGecko, and Fear & Greed Index simultaneously
2. **Market Research Processing** Picks the most interesting market story, generates a unique angle from 10 rotating topics so morning and afternoon posts never overlap
3. **Claude AI Writes the Blog** Produces a 1400-word SEO article with real numbers, hooks, quant deep-dive, feature showcase, disclaimer, and CTA
4. **Multi-Platform Distribution** Formats and posts to all 5 platforms automatically, respecting each platform's character limits and formatting

## Platforms

| Platform | What Gets Posted |
|----------|-----------------|
| Dev.to | Full article with canonical URL → heyastral.ai for SEO authority |
| WordPress | Full HTML post with tags + CTA, Google indexed |
| Discord | Rich embed with clickable link in Astral server |
| Telegra.ph | Teaser post with CTA link back to heyastral.ai |
| Bluesky | Optimised hook under 290 chars for trading/finance audience |

## Results

- **14 unique SEO blog posts per week** fully automated
- **14 new backlinks to heyastral.ai per week**
- Every post grounded in real live market data different every run
- 10 rotating angles no two posts cover the same topic
- Full SEO structure on every post title, meta, slug, tags, canonical URL
- Google Sheets log so the client team can read every post with live URLs

## Technical Highlights

- Full audit and rebuild of a broken 34-node workflow
- WordPress OAuth API integration built from scratch
- 3-layer JSON parser handles any Claude response format without errors
- Duplicate URL prevention date + hour appended to every canonical URL

## Tech Stack

`n8n` `Claude API` `Alpha Vantage API` `CoinGecko API` `WordPress API` `Dev.to API` `Telegra.ph API` `Discord Webhooks` `Bluesky API` `Google Sheets`

## 🎥 Video Walkthrough

[▶ Watch the full walkthrough (14 min)](https://drive.google.com/file/d/138qir7kKkgaIC88--9P0NlKqSH7zapOM/view?usp=sharing) every node explained, all platforms demonstrated live.

---

*Built by Aditya AI Automation & Voice Agent Development*
