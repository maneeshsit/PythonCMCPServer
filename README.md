# PythonCMCPServer
Building a Custom MCP Server using Python
# Install UV
https://docs.astral.sh/uv/getting-started/installation/#installation-methods
# Install UV for Windows
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
# Install Claude Desktop
https://claude.ai/download
# Edit Config 
claude_desktop_config.json
{
  "mcpServers": {
    "Demo": {
      "command": "uv",
      "args": [
        "run",
        "--with",
        "mcp[cli]",
        "mcp",
        "run",
        "C:\\Users\\User\\Desktop\\MCPServerTutorial\\main.py"
      ]
    },
    "AI Sticky Notes": {
      "command": "uv",
      "args": [
        "run",
        "--with",
        "mcp[cli]",
        "mcp",
        "run",
        "C:\\PythonCMCPServer\\main.py"
      ]
    }
  }
}
