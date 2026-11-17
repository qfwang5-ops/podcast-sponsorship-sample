# Podcast Sponsorship Sample

A free, masked sample of a **podcast sponsorship database** covering **2,526 shows** — built for solo founders who want to get sponsorships (or sell a sponsorship-adjacent product) — plus **10 four-dimension business teardowns** scraped from public TikTok build-in-public videos.

> ⚠️ **Status: sample pack. The emails here are intentionally masked** (`s***@optimallivingdaily.com`). The full database — 2,526 shows with unmasked owner emails — is on sale now: **$99 one-time, 14-day refund** → **[www.pixlgrub.com](https://www.pixlgrub.com/)**. Questions? Email Wang Xiaoming at 38505042@qq.com or open a GitHub Issue.

## Contents

- [What's in this repo](#whats-in-this-repo)
- [Why these 25 rows are interesting](#why-these-25-rows-are-interesting)
- [Why the teardowns file is interesting](#why-the-teardowns-file-is-interesting)
- [Data provenance & caveats](#data-provenance--caveats)
- [FAQ](#faq)
- [License](#license)

## What's in this repo

| File | What it is |
|---|---|
| `data/podcast_sponsorship_sample_25.csv` | 25 shows from the 2,526-row database: niche, episode count, last-episode date, website, masked contact email |
| `insights/teardowns_10.csv` | 10 solo-dev business teardowns: tech stack, traffic tactic, monetization numbers, source video |

## Why these 25 rows are interesting

Every row is an **active** podcast (last episode within ~2 weeks of collection) with a scraped contact email. Long-running shows (500–2,000+ episodes) are the ones that sell sponsor slots — which makes them perfect ad inventory *and* perfect partners for barter deals.

Filter by `niche`, sort by `episodes`, check `last_episode` — that's the whole workflow.

## Why the teardowns file is interesting

Each row is one creator's business, decomposed into four dimensions: **tech stack · traffic tactic · monetization numbers · what you can copy**. Numbers are the creators' own claims (flagged per row) and every row links back to the source video ID so you can verify.

Highlights: a $36K outsourced MVP funded by agency profits; a height-prediction page doing a self-reported $100K/mo from TikTok comment replies; a boilerplate repo whose users report $3K/mo; and one 2.1M-view "subscription math" video that turns out to be a free-zone agency ad (yes, we flag those too).

## Data provenance & caveats

- Podcast metadata: public iTunes/Apple Podcasts directory + each show's public RSS feed. Emails extracted from RSS `<itunes:owner>` and show websites.
- Teardowns: transcribed from public TikTok videos; figures are **self-reported by creators**, not independently confirmed. Sponsored content is flagged in the `notes` column.
- This is a **sample**. The full dataset (2,526 rows, unmasked) is not included in this repo — it's the paid product at [www.pixlgrub.com](https://www.pixlgrub.com/) ($99 one-time, 14-day refund).
- Masking: first character of the local part is kept, rest replaced with `***`.

## FAQ

**What is a podcast sponsorship database?**
A filterable CSV of shows that sell sponsorship slots, with the contact email each show publishes in its own RSS feed. This repo is the free sample: masked rows from the full 2,526-show database.

**Where do the podcast sponsor emails come from?**
Each show's official RSS feed — the `itunes:email` field Apple's feed spec asks every publisher to declare. We never guess addresses or scrape data brokers; the full database ships the unmasked emails, this sample masks them.

**How much does the full database cost?**
$99 one-time with a 14-day refund if the data is materially wrong — no subscription, no commission. Get it at [www.pixlgrub.com](https://www.pixlgrub.com/). The sample in this repo stays free.

**Do you include listener or download numbers?**
No — Apple does not publish them for long-tail shows, and we won't fake them. What you get instead: episode count, last publish date, and niche tags, so you can tell a live show from a dead one before you pitch.

## License

- Data: CC BY 4.0 — cite "podcast-sponsorship-sample" and link back.
- Any code: MIT.

---

*Built by Wang Xiaoming — a solo founder documenting the whole process (database building, pricing tests, and all) on TikTok and in blog posts. Questions: 38505042@qq.com, GitHub Issues, or [www.pixlgrub.com](https://www.pixlgrub.com/).*
