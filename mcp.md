**Add AWS Knowledge MCP Server**
```
q mcp add --name aws-knowledge-mcp-server --command npx --args mcp-remote --args https://knowledge-mcp.global.api.aws
```

**Add AWS Documentation MCP Server**
```
q mcp add --name aws-documentation --command uvx --args awslabs.aws-documentation-mcp-server@latest --env AWS_DOCUMENTATION_PARTITION=aws --env FASTMCp_LOG_LEVEL=ERROR
```

**Add AWS Architecture Diagram MCP Server**
```
q mcp add --name aws-diagram --command uvx --args awslabs.aws-diagram-mcp-server --env FASTMCP_LOG_LEVEL=ERROR
```
