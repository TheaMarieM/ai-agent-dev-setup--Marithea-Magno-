# ai-agent-dev-setup--Marithea-Magno-
Marithea M. Magno, Full Stack Web Dev with AI Agentic SPUP
✅ Node.js installed (screenshot of 'node --version' command) <img width="491" height="50" alt="image" src="https://github.com/user-attachments/assets/dac5f440-624d-43e8-92f2-e4e4c23feeec" />
✅ Git installed (screenshot of 'git --version' command)<img width="305" height="100" alt="image" src="https://github.com/user-attachments/assets/4d951259-666d-4054-98dd-4d30376c57cc" />
✅ VS Code Insider running with GitHub Copilot enabled (screenshot)<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/92dca97b-7468-41cd-a91e-7d89e1e1553c" />
✅ Claude Desktop open with all 4 MCP servers connected (screenshot)<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0cfde700-c0b0-4f85-89dd-872afd7f8081" />

MCP Server Purpose & Functionality
rolldice-mcpserver

Purpose: Provides a Model Context Protocol (MCP) server and web interface for rolling dice, designed for integration with Claude Desktop and web users.
Functionality:
Accepts dice roll requests (e.g., d6, d20, custom) via HTTP API endpoints and the MCP protocol.
Validates and processes requests using shared logic (lib/dice.ts), ensuring consistent results and schema validation.
Offers a modern web UI for manual testing, setup instructions, and result display.
Supports multiple transport protocols (SSE, stdio, etc.) for flexible integration.
Can be deployed locally or to Vercel for public access.
Troubleshooting Notes
Issue:

"git is not recognized as the name of a cmdlet..."
Cause: Git was not installed or not in the system PATH.
Solution:

Downloaded and installed Git for Windows from https://git-scm.com/download/win.
Ensured the option to add Git to the system PATH was selected during installation.
Restarted the terminal to recognize the git command.
