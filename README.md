# ClipCrew for Claude

ClipCrew turns long videos in Tamil, Telugu, Hindi or English into short clips. This plugin adds three skills and connects Claude to ClipCrew's MCP server at `https://mcp.clipcrew.ai/api/mcp`.

## What you can do

- **Clip a video:** paste a YouTube link to see how long it is and how many credits a clip job would use. Then get the link to start the job on clipcrew.ai.
- **Check ad compliance:** check a sponsor script or caption for disclosure and claims. This is guidance, not legal advice.
- **Grow my channel:** see how often a YouTube channel has posted in the last 90 days, with a link to ClipCrew's full channel analysis.

## Requirements

- Claude on claude.ai, the desktop app or Claude Code.
- A ClipCrew account to start clip jobs on clipcrew.ai. The three skills above work without one.

## Install

- **Claude:** add ClipCrew from the Claude plugin directory.
- **Claude Code:** run these two commands.

```
/plugin marketplace add clipcrewai/clipcrew-plugin
/plugin install clipcrew@clipcrew
```

## What the plugin runs and sends

The plugin contains instructions (skills) and one remote MCP server. It runs no local code, scripts or hooks.

- Requests go only to `https://mcp.clipcrew.ai/api/mcp`.
- The plugin never asks you to sign in. It sends only the YouTube link, channel or text you give it.
- Clip jobs start only on clipcrew.ai. The assistant shares the link.

## Support and policies

- Help: hello@clipcrew.ai or [clipcrew.ai/about](https://clipcrew.ai/about)
- [Privacy policy](https://clipcrew.ai/privacy-policy)
- [Terms of service](https://clipcrew.ai/terms-of-service)

This repository is published automatically from a private source. Issues are welcome; pull requests are not accepted.

MIT license. ClipCrew is operated by Innoverse Media LLC.
