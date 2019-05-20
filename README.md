# Contact-Centre Version 1.0

Inbound & outbound PSTN Contact Centre Powered by TaskRouter and Twilio Client

Languages: Node js

This implements:

- Single channel (Voice)
- Agent UI based on TaskRouter SDK for low latency
- Twilio Client WebRTC agent dashboard
- Conference instruction
- Call instruction
- Conference recording
- Call holding
- Call transfers
- Optional assignment_callback url implementation

It will need a public url, there are two ngrok_url parameters in the following files that you will need to enter your public root domain:

server.js line 31
agent_desktop: line 52
