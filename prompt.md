# Record

```powershell
cd "D:\D drive\products\octen\1-octen"
agent
```

Paste one prompt. Wait until its file is on screen, then start a new `agent` session for the next round.

## Round 1

```
Follow AGENT.md. Round 1 only. Use Octen search only.

Compare Cursor, GitHub Copilot, and Claude Code. For each one, run a separate search for price, free tier, where it works, recent features, speed, context size, and reliability. 21 searches. Official pages only.

Write outputs/round1_comparison.md as a table. Every cell has the fact and its source URL. If the page does not say it, write: Not found on an official page.

Log every call in outputs/search_log.jsonl. End with the search count and any failures.
```

## Round 2

```
Follow AGENT.md. Round 2 only. Use Octen image_search only.

Find reference images for the latest MacBook (ports, keyboard, body) and the current Claude Code screen (terminal, diff or tool call, overall UI). At least 3 searches per subject. apple.com for the MacBook. claude.com, code.claude.com, or anthropic.com for Claude Code.

For each image write the image URL, the page URL, a caption, and why it is a good reference. Save to outputs/round2_images.md.

If image_search returns 403 or a billing error, stop and write that error. Do not use another tool.

Log every call in outputs/search_log.jsonl. End with the call count and any failures.
```
