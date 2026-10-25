# Hi, I'm Shivam Vashisth

**YouTube strategist. Journalist by training. Self-taught builder.**

I run YouTube strategy for a large exam-prep education brand in India: research,
packaging, script briefs for 13 faculty, and the numbers management reads every week.

I have no computer science degree. When the team needed data nobody was producing,
I learned to build it, with Claude Code as my pair. Every repo below started as a
problem at work that had no tool yet. If I don't know how to do something, I figure
it out, and I own it until it works.

**Portfolio: [yt.shivamvashisth.com](https://yt.shivamvashisth.com)** (results, how I work, and how to work with me)

## What I build

- **Creator script ops**: briefs for 13 faculty plus guest creators from per-creator
  voice profiles, a locked SEO brief format, and a drafted-to-published ledger
- **Channel trackers**: weekly reporting pipelines (YouTube Data API + yt-dlp)
  that re-derive every number a second way before anything ships
- **Competitive intelligence**: daily scans of 40+ channels with opportunity
  scoring, comment mining, and a live dashboard
- **Metadata at scale**: a safety-gated SEO pipeline that re-optimized 384 videos
  on a live channel, with snapshot-and-revert and canary-then-batch rollouts
- **Media automation**: local Whisper clip cutters, caption-to-cut-sheet builders,
  thumbnail and outlier analysis

## How I got here

- **Journalist by training**: TV, print and digital, behind the camera on scripts
  and in front of it on ad campaigns
- **Sales and client servicing** in fintech and finance ed-tech, with real money
  on the line
- **Builder by necessity**: learned Python, APIs and agentic workflows on the job,
  one shipped pipeline at a time

## Stack

Python, TypeScript/Next.js, Astro, YouTube Data API v3, yt-dlp, Whisper (MLX),
ffmpeg, Claude Code, Codex, Claude and Gemini APIs, MCP servers,
Supabase/Postgres, Vercel, OBS Studio.

## Domains

EdTech, FinTech, AI. Media background, data-engineering habits.

---

## The full tool index

17 public repos, one real working pipeline or product each, shipped roughly
one meaningful commit a day since Jul 2026. Every README states what's
verified versus what's honestly unproven. No invented metrics.

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
- [youtube-intel-mcp](https://github.com/svx2027/youtube-intel-mcp): packages
  the competitor-intelligence engine (opportunity score, demand gap, topic
  tagging) as an MCP server, so any MCP client can call it as tools
- [playlist-extract-pipeline](https://github.com/svx2027/playlist-extract-pipeline):
  turns your own playlists into a structured dataset (metadata, thumbnails,
  transcripts) with a resumable extract-then-repair loop
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
- [creator-ai-skill-system](https://github.com/svx2027/creator-ai-skill-system):
  AI skills for carousels, posts, replies and podcast openings, each output
  checked against its source and a list of AI tells before anyone sees it

**Other platforms**
- [ig-taste-engine](https://github.com/svx2027/ig-taste-engine): turns your
  own saved Instagram reels into a structured taste dataset (capture,
  transcribe, OCR on-screen text), read-only and human-paced

**Web products**
- [the-toolshed](https://github.com/svx2027/the-toolshed): my site plus a
  shed of tiny share-first web tools, live at shivamvashisth.com
- [shivam-download-files](https://github.com/svx2027/shivam-download-files):
  Spotlight-style public file vault with Postgres full-text + typo-tolerant
  search and signed-URL downloads, live at files.shivamvashisth.com

## Case studies

Two write-ups on shivamvashisth.com walk through the harder pipelines end to
end: [the daily-competitive-intelligence scan](https://shivamvashisth.com/case-studies/daily-competitive-intelligence/)
(yt-competitor-swipe) and [verify-before-deliver](https://shivamvashisth.com/case-studies/verify-before-deliver/)
(yt-mastersheet-kit). More are landing as the underlying repos are ready for
the traffic.

[How this portfolio builds itself](https://shivamvashisth.com/how-this-portfolio-builds-itself/)
walks through the process behind every repo above: the four-step port and the
three-role gate that has to agree before anything here goes public.

[yt.shivamvashisth.com](https://yt.shivamvashisth.com) (portfolio) and [shivamvashisth.com](https://shivamvashisth.com) (tools and case studies)
