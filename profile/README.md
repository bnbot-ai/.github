# BNBot (Brand & Bot)

**AI-powered personal brand and social media automation.** Run your personal brand and social accounts from the terminal.

BNBot is a suite of tools — Chrome extension, CLI, and AI skill — that helps you discover trending topics, generate content, and publish across platforms.

## Products

| Project | Description |
|---------|-------------|
| **[BNBot Extension](https://chromewebstore.google.com/detail/bnbot-your-ai-growth-agen/haammgigdkckogcgnbkigfleejpaiiln)** | Chrome extension — AI sidebar for Twitter/X, built-in [OpenCLI](https://github.com/jackwener/opencli) bridge for 40+ platforms |
| **[BNBot CLI](https://github.com/bnbot-ai/bnbot-cli)** | Terminal tool for scraping & publishing tweets (`npm install -g bnbot-cli`) |
| **[BNBot Skill](https://github.com/jackleeio/bnbot-editor)** | Claude Code skill — discovers trends from 15+ sources, generates human-sounding drafts |
| **[BNBot MCP Server](https://github.com/jackleeio/bnbot-mcp-server)** | Model Context Protocol server for AI agent integration |

## How It Works

```
Terminal (bnbot-cli / opencli)
    ↓ WebSocket
BNBot Chrome Extension
    ↓ DOM / GraphQL / CDP
Twitter/X + 40 platforms via OpenCLI
```

Install the extension, then use the CLI or AI skill to automate your workflow:

```bash
npm install -g bnbot-cli
npm install -g @jackwener/opencli

# Scrape & publish
bnbot scrape user-tweets elonmusk -l 10
bnbot tweet post "Hello from BNBot!" --media image.png

# Cross-platform via OpenCLI (through BNBot Extension)
opencli tiktok explore --limit 10
opencli youtube search "AI agents" --limit 5
```

## Links

- Website: [bnbot.ai](https://bnbot.ai)
- Twitter: [@BNBOT_AI](https://x.com/BNBOT_AI)
- Chrome Extension: [Chrome Web Store](https://chromewebstore.google.com/detail/bnbot-your-ai-growth-agen/haammgigdkckogcgnbkigfleejpaiiln)
