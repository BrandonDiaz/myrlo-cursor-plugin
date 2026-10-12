# Myrlo plugin

Agent plugin for [Myrlo](https://myrlo.app): create and edit your characters, stories, and worlds from Cursor (and other Agent Plugins–compatible clients).

## What's inside

- `plugin.json`: Agent Plugins manifest
- `mcp.json`: connects to the remote Myrlo MCP server at `https://myrlo.app/mcp`
- `skills/myrlo-authoring/SKILL.md`: teaches the agent the Myrlo authoring flow (open a session, read context, stage changes, review, then apply). It also says to confirm before generating photos, because that spends fragments.

## Install

- **Cursor Marketplace:** install "Myrlo" once it's listed.
- **Local:** clone this repo into `~/.cursor/plugins/local/myrlo` and reload Cursor.

## Authentication

You need a Myrlo account. The first time the MCP server is used, Cursor opens Myrlo's OAuth sign-in. This plugin stores no API keys or secrets.

## License

MIT
