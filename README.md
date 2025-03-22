# Cursor MCP Server

A GitHub server integration for Cursor IDE using MCP (Multi-Cloud Protocol).

## Overview

This repository contains the configuration and implementation for a GitHub server integration with Cursor IDE. It enables seamless interaction with GitHub repositories and features directly from within the Cursor IDE environment.

## Features

- GitHub API integration
- Repository management
- Issue tracking
- Pull request handling
- File operations
- Code search capabilities

## Getting Started

1. Ensure you have Cursor IDE installed
2. Configure your GitHub credentials in the MCP configuration file
3. Set up your Personal Access Token (PAT) with appropriate permissions

## Configuration

The MCP configuration should be placed in `~/.cursor/mcp.json`:

```json
{
  "github": {
    "server": {
      "url": "https://api.github.com",
      "token": "your-github-pat",
      "username": "your-github-username"
    }
  }
}
```

## Usage

- Use Cursor IDE's integrated commands to interact with GitHub
- Manage repositories, issues, and pull requests directly from the IDE
- Perform code searches across your GitHub repositories
- Handle file operations seamlessly

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.