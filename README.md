# MCP Server Deployment Application

## Description

This project explores the Model Context Protocol (MCP), its architecture, and practical implementation. The journey includes building an MCP client and server, integrating chatbot functionality, and incorporating prompt and resource features. It also includes experimentation with Claude desktop services and the final deployment of remote servers using robust communication methods.

We initially implemented server communication using stdio for simplicity, then upgraded to Server-Sent Events (SSE) to support production-ready performance and scalability.

## Features

- Designed and implemented MCP client-server architecture
- Integrated MCP chatbot with prompt and resource extensions
- Utilized Claude desktop services for local interaction
- Remote server creation and deployment workflow
- Migration from stdio to SSE for scalable deployment

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sherwaldeepesh/mcp_server_deployement.git
   cd mcp-server-deployment
   ```

2. (Optional) Set up a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch the MCP server:

   ```bash
   python mcp_server.py
   ```

2. Start the MCP client to connect and interact with the server:

   ```bash
   python mcp_client.py
   ```

3. Explore added chatbot and resource features by navigating through the CLI or web interface.

> Note: Update this section with exact usage examples once the application interfaces are finalized. [Needs to update.]

## Technologies Used

- Python
- Model Context Protocol (MCP)
- Server-Sent Events (SSE)
- Claude Desktop Services
- CLI / Jupyter (if applicable)
- Shell scripting (for deployment steps)
