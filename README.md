# Perplexity MCP Plugin

Custom MCP (Model Context Protocol) plugin for Perplexity AI integration.

## Overview

This plugin provides additional tools and capabilities for Perplexity AI through the Model Context Protocol.

## Installation

```bash
npm install
```

## Usage

```bash
npm start
```

## Configuration

To use this plugin with Perplexity or Claude Desktop, add it to your MCP configuration file:

```json
{
  "mcpServers": {
    "perplexity-plugin": {
      "command": "node",
      "args": ["/path/to/perplexity-mcp-plugin/index.js"]
    }
  }
}
```

## Available Tools

### example_tool
- **Description**: An example tool that demonstrates MCP functionality
- **Parameters**:
  - `message` (string, required): A message to process

## Development

This plugin is built using the [@modelcontextprotocol/sdk](https://github.com/modelcontextprotocol/sdk).

## License

MIT