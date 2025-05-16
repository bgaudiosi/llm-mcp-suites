# llm-mcp-suites
Combinations of MCP servers I find useful.

## What is MCP?
See [the MCP documentation](https://modelcontextprotocol.io/introduction).

See also [the news release from Anthropic announcing MCP](https://www.anthropic.com/news/model-context-protocol).

## List of all MCPs I find interesting

### Git
* [github/github-mcp-server](https://github.com/github/github-mcp-server) - Official GitHub server for integration with repository management, PRs, issues, and more.
* [modelcontextprotocol/git](https://github.com/modelcontextprotocol/servers/tree/main/src/git): Provides tools for Git

### Debugging Tools
* [modelcontextprotocol/sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Retrieving and analyzing issues from Sentry.io
* [livehybrid/splunk-mcp](https://github.com/livehybrid/splunk-mcp) - A FastMCP-based tool for interacting with Splunk Enterprise/Cloud through natural language. This tool provides a set of capabilities for searching Splunk data, managing KV stores, and accessing Splunk resources through an intuitive interface.
* [winor30/mcp-server-datadog](https://github.com/winor30/mcp-server-datadog) - Provides a mechanism to leverage key Datadog monitoring features, such as incidents, monitors, logs, dashboards, and metrics, through the MCP server.
* [modelcontextprotocol/postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - A Model Context Protocol server that provides read-only access to PostgreSQL databases. This server enables LLMs to inspect database schemas and execute read-only queries.

### AWS
* [modelcontextprotocol/aws-kb-retrieval-server](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-kb-retrieval-server) - An MCP server implementation for retrieving information from the AWS Knowledge Base using the Bedrock Agent Runtime.
* [awslabs/terraform-mcp-server](https://github.com/awslabs/mcp/tree/main/src/terraform-mcp-server) - MCP server for Terraform on AWS best practices, infrastructure as code patterns, and security compliance with Checkov.
* [awslabs/dynamodb-mcp-server](https://github.com/awslabs/mcp/blob/main/src/dynamodb-mcp-server/README.md) - The official MCP Server for interacting with AWS DynamoDB
* [awslabs/git-repo-research-mcp-server](https://github.com/awslabs/mcp/tree/main/src/git-repo-research-mcp-server) - Model Context Protocol (MCP) server for researching Git repositories using semantic search. This MCP server enables developers to research external Git repositories and influence their code generation without having to clone repositories to local projects. It provides tools to index, search, and explore Git repositories using semantic search powered by Amazon Bedrock and FAISS.

### Coding assistance
* [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) - The JetBrains MCP (Model Context Protocol) Proxy Server acts as a bridge between AI assistants like Claude and JetBrains IDEs. It allows AI assistants to connect to your IDE, gathering useful information about code.

### Information
* [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) - MCP server for Atlassian products (Confluence and Jira). Supports Confluence Cloud, Jira Cloud, and Jira Server/Data Center. Provides comprehensive tools for searching, reading, creating, and managing content across Atlassian workspaces.
* [modelcontextprotocol/slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - MCP Server for the Slack API, enabling Claude to interact with Slack workspaces.
* [modelcontextprotocol/brave-search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - An MCP server implementation that integrates the Brave Search API, providing both web and local search capabilities.
* [modelcontextprotocol/server-google-drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - Google Drive integration for listing, reading, and searching files
* [Bigsy/maven-mcp-server](https://github.com/Bigsy/maven-mcp-server) - An MCP (Model Context Protocol) server that provides tools for checking Maven dependency versions. This server enables LLMs to verify Maven dependencies and retrieve their latest versions from Maven Central Repository.

### Other
* [modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Direct local file system access.
* [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) - Connect any HTTP/REST API server using an Open API spec (v3)
* [modelcontextprotocol/time](https://github.com/modelcontextprotocol/servers/tree/main/src/time) - A Model Context Protocol server that provides time and timezone conversion capabilities. This server enables LLMs to get current time information and perform timezone conversions using IANA timezone names, with automatic system timezone detection.

## Setup

### Claude Desktop
Copy `mcp-config.json` to...

### Cursor
Copy `mcp-config.json` to...

## Prompt Ideas

### Disclaimer
This list and corresponding descriptions are in part sourced from 
[awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers).
