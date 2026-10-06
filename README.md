# MyChat
Deployable browser video chat with private 2-person rooms, shareable room links, random matching, WebRTC video/audio, and text chat.

## Run
Node 20+: `npm install` then `npm start`, open `http://localhost:3000`.

## Public deployment
Deploy the folder to a Node/WebSocket host such as Render, Railway, Fly.io, or your own server. Build/install: `npm install`; start: `npm start`. Use HTTPS in production so browsers permit camera/microphone access. A TURN server is recommended for reliable connectivity across restrictive networks.

## Important
This is a functional starter, not a production moderation system. Before public stranger chat, add age gating, report/block tools, rate limits, abuse prevention, privacy/terms pages, monitoring, and TURN infrastructure.
