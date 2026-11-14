# GLP-1 Buyer Guide Prices — public MCP feed

Month-to-month GLP-1 prices checked by GLP-1 Buyer Guide, with sources and check dates.
The server is hosted and read-only — no account, no API key.

Endpoint: https://prices.glp1buyerguide.com/mcp (Streamable HTTP)
Registry: com.glp1buyerguide/glp1-prices (official MCP Registry)
Guide: https://glp1buyerguide.com

## Tools
- find_glp1_prices — checked prices by medication
- find_provider_glp1_prices — all prices for one provider
- list_glp1_medications — medications covered by the feed

## Connect a client
Add the endpoint as a remote MCP server:
{ "mcpServers": { "glp1-prices": { "url": "https://prices.glp1buyerguide.com/mcp" } } }

This repo also carries the directory manifests for this server: gemini-extension.json (Gemini CLI), lhm.plugin.json (LobeHub), .cursor-plugin/plugin.json and mcp.json (Cursor).
