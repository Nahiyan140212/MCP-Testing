# MCP Testing Suite

This repository contains test tools for Message Communication Protocol (MCP), providing client-server testing capabilities.

## Overview

The MCP Testing Suite allows developers to validate MCP implementations through dedicated client and server test modules. These test tools help ensure proper functionality, performance, and reliability of MCP-based communications.

## Contents

- `client_mcp_test.py` - Client-side test module for MCP
- `server_mcp_test.py` - Server-side test module for MCP
- `requirements.txt` - Python dependencies for the testing suite

## Requirements

Dependencies are listed in `requirements.txt`. Install them using:

```bash
pip install -r requirements.txt
```

## Usage

### Client Testing

Run the client test module to verify MCP client functionality:

```bash
python client_mcp_test.py
```

### Server Testing

Run the server test module to verify MCP server functionality:

```bash
python server_mcp_test.py
```

## Configuration

Both test modules can be configured through command-line arguments or configuration files. See the individual module documentation for specific options.

