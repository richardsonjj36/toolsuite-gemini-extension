# Startup Ignition ToolSuite for Gemini CLI

Connects Gemini CLI to your [Startup Ignition ToolSuite](https://www.startupignition.com/toolsuite/) account through the ToolSuite MCP connector, so Gemini can read your ideas, canvases, personas, assumptions and interview findings, run the Startup Ignition validation steps, ask the mentor, edit canvases and assumptions (with undo) and export pages as PDFs.

## Install

```bash
gemini extensions install https://github.com/richardsonjj36/toolsuite-gemini-extension
```

Then start Gemini CLI and sign in:

```
/mcp auth toolsuite
```

Your browser opens the ToolSuite sign-in page. Choose the workspaces Gemini may use, the permissions (read, run tools, edit) and a daily usage limit, and approve.

## Requirements

A ToolSuite account at [app.startupignition.com](https://app.startupignition.com). Running tools spends the workspace's ToolSuite credits, within the daily limit you set when you connect.

## Documentation and support

Setup guide for every app: https://www.startupignition.com/toolsuite/connect/  
Support: toolsuite@startupignition.com  
Privacy: https://www.startupignition.com/privacy/ · Terms: https://www.startupignition.com/terms/
