# Web to Markdown Clipper (Manifest V3) - FastLLM

Working **Manifest V3 Chrome Extension** replacement for legacy Manifest V2 web clippers (such as MarkDownload) that converts any article, documentation page, or blog post into clean Markdown with live **word + LLM token counts** in one click (`Alt+Shift+C`).

- **Install Free on Chrome Web Store:** https://chromewebstore.google.com/detail/fbkcdpjndneocipnafbhofcnnkoaobac
- **MarkDownload MV3 Migration Comparison:** https://neoninnovationlab.com/alternatives/markdownload
- **Live Web Scanner & Docs:** https://neoninnovationlab.com/tools/aeo-audit

## Why This Exists

After Chrome retired Manifest V2 extensions, classic clippers like `deathau/markdownload` stopped loading in modern Chromium browsers. **FastLLM** runs natively on **Manifest V3** using minimal click-only permissions (`activeTab`, `storage`, `scripting`) so it never reads background browsing history.

## Key Capabilities

1. **1-Click Web to Markdown (`Alt+Shift+C`):** Strips navbars, cookie banners, and ads from documentation pages and articles, preserving headings, Markdown tables, lists, and fenced code blocks.
2. **Live LLM Token & Word Counter:** Displays exact word count and estimated token budget before pasting into Claude, ChatGPT, Cursor, Obsidian, or Notion.
3. **AI Crawler & Structured Data Inspector:** Checks `robots.txt` rules for `OAI-SearchBot`, `GPTBot`, `ClaudeBot`, `PerplexityBot`, and `Google-Extended`, plus `Schema.org` JSON-LD blocks and `/llms.txt`.
4. **32 Browser Languages Supported:** Localized across 32 Chrome Web Store locales.

## Need to Export ChatGPT, Claude, or Gemini Conversations Instead?

Check out **[ThreadShelf](https://github.com/neon-innovation-lab/export-claude-chatgpt-markdown)** for 100% local browser folders, offline search, and speaker-formatted Markdown export across `claude.ai`, `chatgpt.com`, and `gemini.google.com`.

## License & Privacy

Client clipping runs locally inside your active browser tab. Privacy Policy: https://neoninnovationlab.com/privacy-extensions
