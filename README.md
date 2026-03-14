# Eigenlayer MCP Server

MCP server for Eigenlayer. Agent-ready API for Eigenlayer.

Hosted at [eigenlayer.mcp.junct.dev/mcp](https://eigenlayer.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "eigenlayer": {
      "url": "https://eigenlayer.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Eigenlayer API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Eigenlayer
- **Endpoint:** `https://eigenlayer.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [eigenlayer.mcp.junct.dev/llms.txt](https://eigenlayer.mcp.junct.dev/llms.txt)
- **Server card:** [eigenlayer.mcp.junct.dev/.well-known/mcp/server.json](https://eigenlayer.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/eigenlayer)
- [llms.txt](https://eigenlayer.mcp.junct.dev/llms.txt)
- [agents.md](https://eigenlayer.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://eigenlayer.mcp.junct.dev/openapi.json)

## Keywords

Eigenlayer, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
