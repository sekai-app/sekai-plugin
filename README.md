# Sekai plugin

Connect your coding agent to [Sekai](https://sekai.ai) and ship playable games without leaving the conversation. The plugin points your agent at the hosted Sekai MCP server (`https://mcp.sekai.ai/mcp`): search Sekai's asset library, upload a single-file HTML game as a private draft, and publish it to sekai.ai. Sign in with your Sekai account when the agent asks (OAuth).

Docs: https://mcp.sekai.ai/docs · Landing page: https://sekai.ai/mcp

## Claude Code

```
/plugin install sekai --marketplace sekai-app/sekai-plugin
```

Then `/mcp` → `sekai` → Authenticate.

## Codex

```
codex plugin marketplace add sekai-app/sekai-plugin
codex plugin add sekai@sekai-plugin
```

## Cursor

One click: [Add Sekai to Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=sekai&config=eyJ1cmwiOiJodHRwczovL21jcC5zZWthaS5haS9tY3AifQ==)

Or place this repository under `~/.cursor/plugins/local/sekai` and reload Cursor.

## VS Code

[Install in VS Code](vscode:mcp/install?%7B%22name%22%3A%22sekai%22%2C%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.sekai.ai%2Fmcp%22%7D)

## Any MCP client

Add a remote (streamable HTTP) server at `https://mcp.sekai.ai/mcp`. The server supports OAuth 2.0 with dynamic client registration and PKCE.

## Privacy and terms

https://sekai.ai/privacy · https://sekai.ai/terms · support@sekaiapp.com
