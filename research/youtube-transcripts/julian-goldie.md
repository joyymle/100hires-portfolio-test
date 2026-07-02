I pulled the full transcript from [**Claude AI SEO System Ranks Me #1 on Google**](https://www.youtube.com/watch?v=_qAjPM8874k) (Julian Goldie SEO, ~11 min). It’s a walkthrough of an automated SEO stack built with Claude, not a generic “AI SEO theory” talk — but the AI SEO takeaways are concrete.

## Summary

The creator claims multiple sites went from **0 to 29–275 clicks/day** using a modular **“Agent OS”**: every SEO idea becomes a reusable Claude workflow, stacked in one place and improved daily.

---

## Key takeaways about AI SEO

### 1. Think in systems, not one-off tasks
Instead of doing SEO manually each time, he turns each idea into a **repeatable agent workflow** (research → write → publish → index → track). The mindset shift: SEO should be **time-efficient and stackable**, like software.

### 2. Your own GSC data beats public keyword tools
A Claude-built **Google Search Console dashboard** finds:
- Keywords with **impressions but zero clicks** (new landing page opportunities)
- Pages to **re-optimize**
- Wins on one site to **replicate across other sites in the same niche**

The argument: this is **private first-party data**, unlike Ahrefs/SEMrush where everyone chases the same keywords.

### 3. Claude “skills” = consistent SEO content at scale
Content is generated via saved **Claude skills** that encode:
- SEO structure
- Tone of voice
- Step-by-step authoring rules

He says newer models (e.g. **Claude Opus 4.x**) can finally follow very detailed, technical writing procedures. You can ask Claude to **derive a skill from how you already write**, then reuse it across sites.

### 4. Publish without touching CMS dashboards
Deployment is automated via:
- **Netlify** (personal access token → Claude publishes)
- **WordPress REST API** (publish trending/news content in one click)

Goal: remove slow, distracting manual CMS work.

### 5. Trending news = Discover + low-competition keywords
A **Hermes Agent** workflow (integrated with **Grok** for X/Twitter trends) runs on a **24-hour schedule** to surface fresh news by category. Two use cases:
- **Google Discover** traffic from trending topics
- **Early keywords** with less competition (e.g. “Claude Fable 5 comeback,” “Grok 4.5”)

### 6. Indexing speed matters for new sites
New sites get crawled infrequently. He plugs in an **indexing API** (IndexNow-style tooling — he mentions “Index Exceptional”) so new posts get **indexed and categorized faster**, instead of sitting in a sitemap unnoticed.

### 7. Dual ranking: written content + video agent
For target keywords, he runs a **video agent** alongside articles so you get **two SERP opportunities** (page + video) for the same query. Example shown: ranking for a keyword with both formats.

### 8. Track AI search visibility too
He integrated **Open SEO** (open-source) to track rankings in **both traditional Google and AI search** — treating AI visibility as part of the same operating system.

### 9. Where this is headed
He teases a full **autonomous SEO team** of agents (CEO → keyword researcher → writer) running 24/7 — an experiment, not built yet in the video.

---

## Practical AI SEO framework (from the video)

| Layer | What it does |
|--------|----------------|
| **Research** | GSC-based opportunity finder |
| **Trends** | Hermes + Grok for news/Discover |
| **Creation** | Claude skills for structured content |
| **Publishing** | Netlify / WordPress API |
| **Indexing** | Indexing API for fast crawl |
| **Multimedia** | Video agent for same keywords |
| **Measurement** | Open SEO for Google + AI rankings |

---

## Caveats worth noting

- Results are **self-reported** (screenshots of Search Console growth).
- Much of the stack is tied to his **AI Profit Boardroom** community and paid tooling.
- It’s heavily **automation-first** — quality control, E-E-A-T, and Google policy compliance aren’t discussed in depth.
- The pitch is **workflow engineering with Claude**, not classic on-page/link-building SEO alone.

