# Refyner for Claude Code

Turn Claude into a companion for your **[Refyner](https://refyner.me) second
brain**: research grounded in what you've already saved, plus capture new
insights with your confirmation. This plugin bundles the Refyner MCP server and
a skill that teaches Claude the workflow.

Requires a free Refyner account: https://refyner.me

## Install

```
/plugin marketplace add buidly/refyner-claude
/plugin install refyner@refyner
```

Then connect your account once (OAuth):

```
/mcp
```

Select **refyner → Authenticate** and complete the browser login.

## Use it

Just ask naturally — the `second-brain` skill activates automatically:

- "Research context engineering — check my second brain too."
- "What have I saved about pricing?"
- "Save this thread to my second brain."

Claude will search your vault, read the most relevant entries, combine them with
web search, and — when you want to save something — show you a preview and only
write after you confirm.

## What it does (transparency)

This plugin connects to `https://refyner.me/api/mcp` and exposes these tools:

- `search_vault` — search your saved knowledge (read-only)
- `get_vault_entry` — read one saved entry in full (read-only)
- `propose_to_vault` — preview a capture with duplicate detection (does NOT write)
- `confirm_vault_capture` — save an entry (only after you confirm)

Authentication is OAuth — no API key is stored in this plugin.

## License

MIT © Dragos Rebegea / Buidly
