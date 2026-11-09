# Podcast Sponsorship Sample

A free, masked sample of a **2,526-podcast database** built for solo founders who want to get sponsorships (or sell a sponsorship-adjacent product) — plus **10 four-dimension business teardowns** scraped from public TikTok build-in-public videos.

> ⚠️ **Status: sample pack. The emails here are intentionally masked** (`s***@optimallivingdaily.com`). The full database — verified contact emails included — is being prepped for release. **Join the waitlist: email Wang Xiaoming at 38505042@qq.com** (one line is enough — say hi and which niche you're in).

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
- Teardowns: transcribed from public TikTok videos; figures are **self-reported by creators**, not independently verified. Sponsored content is flagged in the `notes` column.
- This is a **sample**. The full dataset (2,526 rows, unmasked) is not included and is not currently for sale — product page: [pixlgrub.com](https://www.pixlgrub.com); waitlist by email (above).
- Masking: first character of the local part is kept, rest replaced with `***`.

## License

- Data: CC BY 4.0 — cite "podcast-sponsorship-sample" and link back.
- Any code: MIT.

---

*Built by Wang Xiaoming — a solo founder documenting the whole process (database building, pricing tests, and all) on TikTok and in blog posts. Waitlist & questions: 38505042@qq.com or GitHub Issues.*