<h1 align="center">Legacy Fosscord Server</h1>

## About

This repository contains:

-   [Fosscord HTTP API Server](/api)
-   [WebSocket Gateway Server](/gateway)
-   [HTTP CDN Server](/cdn)
-   [Utility and Database Models](/util)
-   [RTC Server](/rtc)
-   [WebRTC Server](/webrtc)
-   [Admin Dashboard](/dashboard)

## Setup

Download Spacebar
git clone https://github.com/spartanoah/fosscord-legacy.git

Navigate to project root
cd fosscord-legacy

Install javascript packages
npm i

Build and generate schema. Separately, they are `build` and `generate:schema`.
npm run setup

Start the bundle server ( API, CDN, Gateway in one )
npm run start
