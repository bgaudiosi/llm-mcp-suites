# Code Review
The idea behind this suite of MCP tools is provide tools that will be useful for a bot
whose purpose is to give code reviews.

## MCP Servers Used
* [github/github-mcp-server](https://github.com/github/github-mcp-server) - Official GitHub server for integration with repository management, PRs, issues, and more.
* [modelcontextprotocol/git](https://github.com/modelcontextprotocol/servers/tree/main/src/git): Provides tools for Git
* [modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Direct local file system access.

### Circumstanial 
* [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) - MCP server for Atlassian products (Confluence and Jira). Supports Confluence Cloud, Jira Cloud, and Jira Server/Data Center. Provides comprehensive tools for searching, reading, creating, and managing content across Atlassian workspaces.
* [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) - Analyze React code locally, generate docs / llm.txt for whole project at once
* [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) - Connect any HTTP/REST API server using an Open API spec (v3)
* [modelcontextprotocol/server-google-drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - Google Drive integration for listing, reading, and searching files
* [modelcontextprotocol/sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Retrieving and analyzing issues from Sentry.io
* [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) 📇 ☁️ 🏠 - MCP server for GitHub Enterprise API integration
* [modelcontextprotocol/brave-search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - An MCP server implementation that integrates the Brave Search API, providing both web and local search capabilities.

## Setup
First, run the docker-compose compose file.
`$ docker compose up -d`
This command will start all containers in [docker-compose.yml](./docker-compose.yml).

### Claude Desktop

### 

## Prompt Ideas
