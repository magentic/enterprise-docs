

# Installation

To get the most out of FlowLens, you'll need to set up two components:

## Chrome Extension

The FlowLens Chrome extension is the primary tool for capturing user flows in your web applications.

### Installation Steps

1. **Download the Extension**: Visit the <a href="https://delfina-minio-api.magentic.ai/extension/flowlens-extension.zip" target="_blank" rel="noopener noreferrer">Delfina Bucket</a> and download the ZIP file.

2. **Unzip the File**: Extract the contents of the ZIP file to a folder on your computer.

3. **Load the Extension**:

   * Open **chrome://extensions** in your Chrome browser.
   * Enable **Developer mode** in the top right corner.
   * Click **Load unpacked** and select the folder you extracted.

4. **Pin the Extension**: Click the puzzle icon in your Chrome toolbar and pin FlowLens for quick access.

5. **Login**: Click the FlowLens icon and log in with your Gmail account.


> **Tip:** Make sure you're logged into the same Google account in both the extension and the FlowLens web app for seamless synchronization.

## MCP Integration

FlowLens integrates with AI coding assistants through the Model Context Protocol (MCP). This allows your AI assistant to query flow data and help with debugging directly from your IDE or CLI.

### FlowLens MCP Server
A local MCP server that fetches your recorded user flows and bug reports from the <a href="https://delfina-flowlens.magentic.ai/" target="_blank" rel="noopener noreferrer">Delfina FlowLens platform</a> and exposes them to your AI coding agents for *context-aware debugging*.


### [1] Prerequisites

Install pipx by following the <a href="https://pipx.pypa.io/stable/installation/" target="_blank" rel="noopener noreferrer">official installation guide</a>.

### [2] Install `flowlens-mcp-server` pypi package
```bash
pipx install flowlens-mcp-server
```

To upgrade to the latest version:

```bash
pipx upgrade flowlens-mcp-server
```

To check that the package is installed successfully:

```bash
flowlens-mcp-server
```
