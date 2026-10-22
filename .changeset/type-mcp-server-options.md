---
"mcp-handler": patch
---

Type `McpHandlerOptions` as the `McpServer` constructor options instead of the SDK's `ServerOptions`, so `createMcpHandler` accepts `maxToolInputElements` (added in `@modelcontextprotocol/server` 2.3.0 for GHSA-46jr-4wx8-v453). Type-only; `createMcpHandler` already passes these options to `new McpServer()`.
