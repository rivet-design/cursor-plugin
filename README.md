# Rivet for Cursor

Rivet is a tool for visual web development with AI-powered code modification. This
plugin adds the hosted Rivet MCP server to Cursor with one-click install and
browser-based sign-in.

## What you get

- Rivet's identity and integration tools inside Cursor's agent.
- Native Connect / Login / Logout via Cursor's MCP UI (OAuth in the browser, same
  Google account as the Rivet dashboard).

## Install

Install from the Cursor Marketplace (Settings → Tools & MCP), or add the hosted
server manually:

```json
{
  "mcpServers": {
    "rivet": {
      "url": "https://rivet-proxy.onrender.com/mcp"
    }
  }
}
```

On first use, Cursor opens the browser to sign in. No CLI auth or token pasting is
required.

## Links

- Website: https://rivet.design
- MCP endpoint: https://rivet-proxy.onrender.com/mcp

## License

GPL-3.0-or-later. See [LICENSE.md](LICENSE.md).
