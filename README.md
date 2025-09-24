[![Add to Cursor](https://fastmcp.me/badges/cursor_dark.svg)](https://fastmcp.me/MCP/Details/1162/myip)
[![Add to VS Code](https://fastmcp.me/badges/vscode_dark.svg)](https://fastmcp.me/MCP/Details/1162/myip)
[![Add to Claude](https://fastmcp.me/badges/claude_dark.svg)](https://fastmcp.me/MCP/Details/1162/myip)
[![Add to ChatGPT](https://fastmcp.me/badges/chatgpt_dark.svg)](https://fastmcp.me/MCP/Details/1162/myip)
[![Add to Codex](https://fastmcp.me/badges/codex_dark.svg)](https://fastmcp.me/MCP/Details/1162/myip)
[![Add to Gemini](https://fastmcp.me/badges/gemini_dark.svg)](https://fastmcp.me/MCP/Details/1162/myip)

# MyIP MCP Server

## Tools

The server exposes a `get_ip_info` tool to retrieve your public ip address from ifconfig.me.

## Installation

```json
{
  "mcpServers": {
    "myip": {
      "command": "uvx",
      "args": ["mcp-myip"]
    }
  }
}
```
