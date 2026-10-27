# Parked: tools, repos and skills to evaluate later

These are ideas we've found but haven't adopted yet. We'll review the list together, decide how far each one helps the Brain, and only then install or build it. **Nothing is installed without Srijan's explicit OK.**

| # | Item | Type | What it could do for us | Found in | Status |
|---|---|---|---|---|---|
| P1 | Meta TRIBE v2 (github.com/facebookresearch/tribev2) | Open-source model | Predicts the brain response to a video, so we can A/B compare two edits. CPU run works, about 2 min per second of video. Not proven to predict virality. CC BY-NC (non-commercial). | Virality check, Oct 2026 | Tested once in the scratchpad; parked |
| P2 | Higgsfield Virality Predictor | Web app | Quick hook score / hold rate / brain heatmap for clips ≤15 s. Free beta. | Srijan's screenshot | Parked: use manually in the browser |
| P3 | vidIQ connector | MCP connector (already connected) | Watches reels/TikToks/Shorts and gives scene breakdowns; Instagram outlier search; trending audio and keyword research | Study mode | In use (≈10 credits per reel) |
| P4 | Comment-to-DM automation (e.g. ManyChat) | SaaS | Auto-DMs a freebie when someone comments a keyword | Lesson 01 | Parked |
| P5 | **Real SFX** Claude Code skill (clipwing.pro/skills/real-sfx; github.com/Clipwing/skills) | Claude skill | Places real CC0 SFX on detected moments, ducks under voice, outputs MP4 + WAV + report | Lesson 02 | **Installed 27 Oct 2026** (approved by Srijan) |
| P6 | **earshot** (github.com/Leonxlnx/earshot) | CLI + MCP server + 2 skills | Lets me *listen*: mix/sync critique, listening timeline, makes whooshes in code. CPU, ~1.1 GB models, MIT | Lesson 02 | **Installed 27 Oct 2026** (approved by Srijan) |
| P7 | **Openverse API** | Free API (no key) | Search millions of CC-licensed sounds; filter to CC0 | Lesson 02 | Usable now (no install needed) |
| P8 | **faster-whisper** (SYSTRAN) | Python lib | Word-level transcription: word-by-word captions, cutting on words, transcribing reference reels | Lesson 04 | **Installed** in `/home/user/tools/media` (rebuilt by setup script); `transcribe.py` helper |
| P9 | **yt-dlp** | CLI | Download YouTube (and sometimes Instagram) references for free local analysis | Lesson 04 | **Installed** (same venv) |
| P10 | **OpenCV contrib (CSRT tracker)** | Python lib | Auto-follow a person when reframing a landscape clip to 9:16 | Lesson 04 | **Installed** (same venv) |
| P11 | **HyperFrames** (heygen-com/hyperframes, Apache-2.0) | Claude skills + Node CLI | Agent-built motion graphics from HTML: animated captions, counters, list cards, rendered to MP4 | Lesson 04 | **Skills stored** in `.claude/skills` (hyperframes, hyperframes-cli, hyperframes-registry, media-use). **CLI not run:** running `npx hyperframes` was blocked by Claude Code's safety check (code from external source). Needs Srijan to allow it |
| P12 | Puppeteer | Node lib | HTML → video/screenshots via headless Chrome | Lesson 04 | Skipped: HyperFrames + the preinstalled Chromium/Playwright cover this |
| P13 | Our own "Srijan editor" skill | Idea | Package Srijan's editing style (fonts, grade, easing, SFX, captions, face check) as one reusable skill, the "turn it into a skill" step | Lesson 04 | Idea parked: build after the knowledge dump is refined |
| P14 | Ugoki motion course | Paid course | The full easing/motion method | Lesson 03 | Reference only |
