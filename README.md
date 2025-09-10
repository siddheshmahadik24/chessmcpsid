INSTALL THIS MCP SERVER BY ADDING FOLLOWING JSON CODE TO YOUR JSON CONFIG FILE

```json
{
  "mcpServers": {
    "chesswebserver": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/siddheshmahadik24/chessmcpsid.git",
        "chess"
      ]
    }
  }
}
```

