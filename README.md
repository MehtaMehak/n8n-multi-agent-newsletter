# Multi-Agent Newsletter Workflow

A learning project built with n8n to explore AI agents, tool calling, and MCP (Model Context Protocol).

## How it works

1. The AI Orchestrator coordinates the workflow.
2. The Research Agent finds useful information and links.
3. The Newsletter Agent prepares a newsletter.
4. The Newsletter MCP Server creates a Gmail draft.

**Note:** The workflow creates a Gmail draft. It does not automatically send the email.

## Project files

- `public/Newsletter Multiagent workflow1.json` — sanitized main workflow export.
- `public/Newsletter MCP Server.json` — sanitized MCP server workflow export.

## Importing into n8n

1. Import the MCP Server workflow into n8n.
2. Reconnect the required credentials and configure the necessary services.
3. Import the main workflow.
4. Configure its MCP connection and required credentials.
5. Test the workflow before using it.

Credential references are removed from the public exports, so setup may be required after importing.
