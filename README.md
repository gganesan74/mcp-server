# Installation instructions
To install the adder mcp server, add the following command in the config file for Claude:

```json
{
  "mcpServers": {
    "adder": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/gganesan74/mcp-server",
        "mcp-server"
      ]
    }
  }
}