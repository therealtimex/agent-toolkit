# un-datacommons-mcp

mcp-name: io.github.therealtimex/un-datacommons-mcp

Wrapper package that exposes a CLI for the Data Commons MCP server while delegating implementation to `datacommons-mcp`.

Usage
- stdio: `un-datacommons-mcp serve stdio`
- HTTP: `un-datacommons-mcp serve http --port 8080`

Required env: `DC_API_KEY` (from apikeys.datacommons.org).
Optional env: `DC_TYPE`, `CUSTOM_DC_URL`, `DC_ROOT_TOPIC_DCIDS`, `DC_SEARCH_SCOPE`.

