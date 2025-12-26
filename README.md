# Installation instructions
To install the adder mcp server, add the following command in the config file for Claude:

```json
{
  "mcpServers": {
    "adder": {
      "command": "C:\\Users\\Giris\\.local\\bin\\uvx.EXE",
      "args": [
        "--from",
        "git+https://github.com/gganesan74/mcp-server",
        "mcp-server"
      ]
    }
  }
}