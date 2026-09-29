# CallsReady agent plugin

CallsReady connects an inbound voice agent account to agents that support remote MCP. It lets an authenticated account owner inspect and configure voice agents, review calls and transcripts, check number setup, and see balance. CallsReady does not place outbound calls or sell phone numbers.

The plugin uses `https://api.callsready.com/mcp`. Each user signs in to CallsReady through OAuth when the host asks to connect. No API key or user credential is stored in this package. See the [CallsReady MCP setup guide](https://callsready.com/mcp/) for the current tool list and setup instructions.

Example tasks:

- List my voice agents and tell me which are ready to take calls.
- Show my recent calls and summarize the outcomes.
- Explain what my registered phone number still needs before an agent can answer it.

The package contains only the portable Agent Plugins manifest, remote MCP configuration, and CallsReady icon. It is intended for the OpenAI plugin upload and a separate public repository for Cursor Marketplace review. The server and CallsReady product source remain private.
