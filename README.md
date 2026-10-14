# All SVG Icons for Claude

Claude Code plugin marketplace for [All SVG Icons](https://allsvgicons.com/mcp/): search and fetch 379,000+ free SVG icons and brand logos from 230+ open-source icon sets (Lucide, Material Design, Tabler, Heroicons, Phosphor, Font Awesome, flags, emoji and more), ready to paste into HTML, React, Vue, Svelte or a design file.

## Install

```
/plugin marketplace add thetechbasket/allsvgicons-skills
/plugin install allsvgicons@allsvgicons
```

Then run `/mcp`, pick `allsvgicons` and sign in with your email. The server needs an account so it can apply the daily limit.

Have an MCP Pro API key? Use `claude mcp add allsvgicons --transport http https://i.allsvgicons.com/mcp --header "Authorization: Bearer YOUR_API_KEY"` instead.

## Plans

- **Free:** every tool, 20 calls a day. `list_collections` does not count.
- **Pro:** the same tools with no daily cap. Pricing: https://allsvgicons.com/mcp/#pricing

No tool or feature is Pro-only.

## What you get

- **MCP server** `https://i.allsvgicons.com/mcp` with `search_icons`, `get_icon`, `find_brand_logo`, `list_collections` and `send_feedback`.
- **Skill** `allsvgicons`: tells Claude to use real icons from one consistent set instead of drawing SVG paths by hand.

Setup for other agents (Claude.ai, ChatGPT, Codex, Cursor): https://allsvgicons.com/mcp/

## Privacy and support

- Privacy policy: https://allsvgicons.com/privacy/
- Contact: hi@allsvgicons.com

## License

MIT. Icons keep the license of their own icon set, shown on each pack page.
