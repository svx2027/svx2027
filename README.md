# Hi, I'm Shivam Vashisth

**YouTube strategist who ships automation.**

I run growth and content strategy for education channels at million-plus views
a month scale, and I build the tooling myself: data pipelines, competitive
intelligence systems, and AI-assisted workflows that turn platform data into
publishing decisions.

## What I build

- **Creator script ops**: brief 15+ education creators at once from per-creator
  voice profiles, a locked SEO brief format, and a drafted-to-published ledger
- **Channel trackers**: weekly reporting pipelines (YouTube Data API + yt-dlp)
  that independently re-derive every number before anything ships
- **Competitive intelligence**: automated daily scans of 40+ channels with
  opportunity scoring, comment mining, and a live dashboard
- **Metadata at scale**: a safety-gated bulk SEO pipeline that re-optimized
  384 videos on a live channel, with snapshot-and-revert insurance and
  canary-then-batch rollouts
- **Media automation**: local Whisper clip cutters, caption-to-cutsheet
  builders, thumbnail and outlier analysis

## Stack

Python, TypeScript/Next.js, YouTube Data API v3, yt-dlp, Whisper (MLX),
Claude and Gemini APIs, Supabase/Postgres, Vercel, MCP and agentic workflows.

## Domains

EdTech, FinTech, AI. Media background, data-engineering habits.

---

## The full tool index

15 public repos, one real working pipeline or product each, shipped roughly
one meaningful commit a day since Jul 2026. Every README states what's
verified versus what's honestly unproven — no invented metrics.

**YouTube pipelines**
- [yt-daily-brief](https://github.com/svx2027/yt-daily-brief): a scheduled
  agent that writes a daily brief on what's overperforming in tech/AI YouTube
- [yt-mastersheet-kit](https://github.com/svx2027/yt-mastersheet-kit):
  config-driven channel tracker on yt-dlp, verified paste-ready reporting,
  zero API quota
- [yt-competitor-swipe](https://github.com/svx2027/yt-competitor-swipe):
  daily competitive intelligence across dozens of channels, opportunity
  scoring, and a live dashboard
- [yt-competitor-outlier-pipeline](https://github.com/svx2027/yt-competitor-outlier-pipeline):
  single-competitor outlier analysis with channel-tab discovery and a
  verification layer that independently re-derives every result
- [yt-competitor-research-playbook](https://github.com/svx2027/yt-competitor-research-playbook):
  a copy-and-go playbook that turns competitor research into a proven,
  cycle-anchored content calendar for any niche
- [yt-playlist-seo-pipeline](https://github.com/svx2027/yt-playlist-seo-pipeline):
  the safety-gated bulk pipeline that re-optimized 384 videos on a live
  channel: titles, descriptions, tags, and chapters grounded in each
  video's own transcript
- [yt-bulk-metadata-kit](https://github.com/svx2027/yt-bulk-metadata-kit):
  bulk-updates titles, descriptions, tags, and comments across a playlist via
  OAuth and the Data API v3, with snapshot/revert and independent verification
- [playlist-extract-pipeline](https://github.com/svx2027/playlist-extract-pipeline):
  turns your own playlists into a structured dataset (metadata, thumbnails,
  transcripts) with a resumable extract-then-repair loop — newest addition
- [yt-transcript-translator](https://github.com/svx2027/yt-transcript-translator):
  paste a YouTube URL, get the transcript in fluent English (FastAPI + Claude)

**Content production & clipping**
- [livestream-clip-cutter](https://github.com/svx2027/livestream-clip-cutter):
  turns a long bilingual livestream into a vertical-clip cut-list, with a
  per-window language recheck that catches code-switched audio
- [podcast-repurposing-engine](https://github.com/svx2027/podcast-repurposing-engine):
  turns one podcast into a batch of goal-targeted short-form reels
- [multi-creator-script-engine](https://github.com/svx2027/multi-creator-script-engine):
  runs script production for 15+ creators at once from per-creator voice
  profiles, a locked SEO brief format, and a production ledger

**Other platforms**
- [ig-taste-engine](https://github.com/svx2027/ig-taste-engine): turns your
  own saved Instagram reels into a structured taste dataset (capture,
  transcribe, OCR on-screen text) — read-only, human-paced

**Web products**
- [the-toolshed](https://github.com/svx2027/the-toolshed): my site plus a
  shed of tiny share-first web tools, live at shivamvashisth.com
- [shivam-download-files](https://github.com/svx2027/shivam-download-files):
  Spotlight-style public file vault with Postgres full-text + typo-tolerant
  search and signed-URL downloads, live at files.shivamvashisth.com

## Next up

- Case studies on shivamvashisth.com walking through the harder pipelines
  end to end
- **youtube-intel-mcp**: packaging the competitor-intelligence engine as an
  MCP server

🔗 [shivamvashisth.com](https://shivamvashisth.com)
