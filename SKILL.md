---
name: resolve-workflow
description: Automates full DaVinci Resolve workflows with natural language. Import footage into organized bins, create properly configured timelines, apply LUTs to clips, and render/export — all via plain English commands in OpenClaw or Claude Code. Supports Windows 10/11 and macOS 12+, Resolve 17-19 (Free & Studio). Use when you want to speed up editing without endless GUI clicking.
version: 1.0.0
platforms: [windows, macos]
category: video-editing
tags: [davinci-resolve, video-editing, automation, lut, timeline, render, openclaw, claude-code]
---

# resolve-workflow

Control **DaVinci Resolve** using plain English commands through OpenClaw / Claude Code.

No more manual clicking through menus — just describe what you want done.

### Core Capabilities
- **Import footage** into clean, organized bins (supports `--dry-run` preview)
- **Create timelines** automatically from bins (with correct resolution, fps, etc.)
- **Apply LUTs** to all clips on a timeline (or specific ones)
- **Render & export** timelines in common formats (H.264, ProRes, DNxHD, etc.)

### Example Commands You Can Say
- "Import all footage from D:/Raw into a bin called Day1_Shoot"
- "Import footage from ~/Projects/MyShoot with dry-run first"
- "Create a 1920x1080 25fps timeline from the Day1 bin"
- "Create a 4K 24fps timeline named MainEdit from latest import"
- "Apply the REC709 LUT to every clip on the current timeline"
- "Apply cinematic film LUT to all clips in timeline MainEdit"
- "Export the current timeline as H.264 to D:/Exports"
- "Render all timelines as ProRes 422 HQ with date in filename"

### How It Works
This skill translates your natural language request into the actions needed inside DaVinci Resolve.  
It uses your existing skill code/logic (the integration with Resolve scripting or OpenClaw tools).

**Safety note**: Many commands support preview or dry-run mode before making changes.

### Installation (Free Tier)
1. Clone or download this repository: `https://github.com/markjoseph772/resolve-workflow`
2. Place the folder in your OpenClaw / Claude Code skills directory (usually `~/.openclaw/skills/` or `~/.claude/skills/`)
3. Restart OpenClaw/Claude Code
4. Try a simple command: **"Import footage from D:/Raw into a bin called TestImport"**

For the easiest setup + detailed PDF guide with screenshots + 30 days email support, get the paid version on Gumroad (link added after launch).

### Supported Platforms
- Windows 10/11
- macOS 12+
- DaVinci Resolve 17, 18, 19 (Free and Studio)

### Tips for Best Results
- Use specific folder paths when importing
- Name your bins and timelines clearly
- Start with `--dry-run` on new projects to verify

Start testing now with one of the example commands above!
