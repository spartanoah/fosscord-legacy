<h1 align="center">Legacy Fosscord Server</h1>
opencollective link doesnt even work ¯\_(ツ)_/¯

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
*note that because of how the legacy version is built these instructions may not work properly*

*you might have to mess around in the bundle directory for setup*

```
#Download fosscord-legacy
git clone https://github.com/spartanoah/fosscord-legacy.git

#Navigate to project root 
cd fosscord-legacy

#Install javascript packages
npm i

#Build and generate schema. Separately, they are `build` and `generate:schema`.
npm run setup

#Start the bundle server ( API, CDN, Gateway in one )
npm run start
```

## I WILL NOT BE MAINTAINING THIS VERSION OF FOSSCORD AND IF YOU WANT A MAINTAINED VERSION GO TO THE LEGACY BRANCH ON THE spacebarchat/server REPO.
