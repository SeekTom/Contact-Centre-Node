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
- Outbound calling
- Optional assignment_callback url implementation

This training application will need a public url, we recommend using ngrok to provide a tunnel to your local machine: 

const ngrok_url = "https://123454678910.ngrok.io"; //add your ngrok url

server.js line 31
