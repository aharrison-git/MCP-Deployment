MCP Server Deepdive Deployment


To install the 'add_tool' MCP server, add the following:
```
{
    "mcpServers : {
        "add_tool": {
            "command": "uvx",
            "args": [
                "--from",
                "git+https://github.com/aharrison-git/MCP-Deployment.git",
                "mcp-server"
            ]
        }
    }
}
```


This will fetch and set up the 'mcp-server' from the specified Github repository.