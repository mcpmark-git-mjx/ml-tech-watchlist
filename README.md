# ML Tech Watchlist

Technologies surfaced from our shared ML study-group playlist and resolved to their canonical GitHub repositories.

- **Playlist:** https://www.youtube.com/playlist?list=PLyzTA8cetPdHtlGw1X8Kt7Ea4bd27ApR7 ("MCP-youtube" — 52 entries, of which 40 are currently retrievable; the other 12 are hidden or deleted and expose no metadata)
- **Catalog:** [`ml_tech.md`](./ml_tech.md) — 6 projects, one row per project, ordered A→Z by technology
- **Audit trail:** every playlist video that did not become a catalog row, with the reason, is recorded in `skipped_videos.md` next to the catalog

## Claiming a review

One review task is open per catalog row. **They are opened as pull requests rather than issues** because this repository is a fork whose issue tracker is switched off: GitHub rejects every issue-creation request with `410 Issues has been disabled in this repository`, and the `administration` permission needed to switch the tracker back on cannot be granted to a workflow's `GITHUB_TOKEN` (see `.github/workflows/enable-issues.yml`, which keeps trying). Each pull request carries exactly what the issue would have carried — a title that starts with the technology name and the project's GitHub URL in the body — and adds a `reviews/<technology>.md` stub to review against.

| Technology | Repository |
| --- | --- |
| Claude Code | https://github.com/anthropics/claude-code |
| FlashAttention | https://github.com/Dao-AILab/flash-attention |
| Gemini CLI | https://github.com/google-gemini/gemini-cli |
| OpenAI Codex CLI | https://github.com/openai/codex |
| OpenHands | https://github.com/OpenHands/OpenHands |
| Qwen3-Coder | https://github.com/QwenLM/Qwen3-Coder |

## Why some ML talks are not in the catalog

Claude Opus 4.1, GitHub Copilot and OpenAI o1 all get dedicated playlist videos, but none of them has an official GitHub repository of its own (closed model / closed product), so they are documented as skipped rather than given a row. Devstral appears alongside OpenHands but is published as model weights only, so the OpenHands row covers that video.
