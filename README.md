# Hunter Seeker AI MCP Server

A [Model Context Protocol](https://modelcontextprotocol.io/) (MCP) server for Hunter Seeker AI.

## Installation

```bash
npm install @hunter-seeker-ai/mcp-server
```

## Usage

### As a stdio MCP server

```json
{
  "mcpServers": {
    "hunter-seeker-ai": {
      "command": "npx",
      "args": ["@hunter-seeker-ai/mcp-server"]
    }
  }
}
```

### From source

```bash
npm install
npm run build
npm start
```

## Tools

- **ping** - Check if the server is running

## Development

```bash
npm install
npm run dev
```

## License

MIT
