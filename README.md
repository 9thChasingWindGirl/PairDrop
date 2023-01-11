# Pairdrop 

[Pairdrop](https://pairdrop.net): local file sharing in your browser. Inspired by Apple's Airdrop. 

Developed based on [Snapdrop](https://github.com/RobinLinus/snapdrop)

## Differences to Snapdrop

### Device Pairing
* Pair devices via 6-digit code or QR-Code
* Pair devices outside your local network or in complex network environment (public wifi, company network, Apple Private Relay, VPN etc.).
* Paired devices will always find each other via shared secrets even after reopening the browser or the Progressive Web App
* You will always discover devices on your local network. Paired devices are shown additionally.
* Paired devices outside your local network that are behind a NAT are connected automatically via [Open Relay: Free WebRTC TURN Server](https://www.metered.ca/tools/openrelay/)


### Other changes
* node-only implementation (thanks [@Bellisario](https://github.com/Bellisario))
* automatic restart on error (thanks [@KaKi87](https://github.com/KaKi87))
* lots of stability fixes (thanks [@MWY001](https://github.com/MWY001) [@skiby7](https://github.com/skiby7) [@willstott101](https://github.com/willstott101))
* [Paste Mode](https://github.com/RobinLinus/snapdrop/pull/534)
* [Video and Audio preview](https://github.com/RobinLinus/snapdrop/pull/455) (thanks [@victorwads](https://github.com/victorwads))

## Screenshot
![test](/docs/pairdrop_screenshot_desktop.png)


## Snapdrop and Pairdrop are built with the following awesome technologies:
* Vanilla HTML5 / ES6 / CSS3 frontend
* [WebRTC](http://webrtc.org/) / [WebSockets](http://www.websocket.org/)
* [NodeJS](https://nodejs.org/en/) backend
* [Progressive Web App](https://wikipedia.org/wiki/Progressive_Web_App)


Have any questions? Read our [FAQ](/docs/faq.md).

You can [host your own instance with Docker](/docs/host-your-own.md).


## Support the Community
Pairdrop is free and always will be!

If you want to support me and my work you can [buy me a coffee](https://www.buymeacoffee.com/pairdrop) ☕

<br>

To support the original Snapdrop and its creator go to [his GitHub page](https://github.com/RobinLinus/snapdrop).

Thanks a lot for supporting free and open software!


## How to contribute

Feel free to [open an issue](https://github.com/schlagmichdoch/pairdrop/issues/new/choose) or a
[pull request](https://github.com/schlagmichdoch/pairdrop/pulls) but follow
[Contributing Guidelines](/CONTRIBUTING.md).
