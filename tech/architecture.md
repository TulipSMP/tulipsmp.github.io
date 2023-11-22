# Architecture

- [Back](/tech)

This page outlines the overall setup of Tulip SMP's infrastructure, piece by piece.

#### Contents

- [Networking](#networking)
- [Minecraft Server](#minecraft-server)

## Networking

![SVG Diagram of networking layout](src/Tulip_SMP_Networking.drawio.svg)

Synopsis: When you connect to any of my services, you connect through the proxy server, which is accessible by the open internet. The proxy server then connects through to the backend server over Tailscale.

Definitions:
- [PufferPanel](https://www.pufferpanel.com/): A software that can host a web panel for managing and run game servers
- [Nginx](https://nginx.org/): A web server and reverse proxy software
- [GitHub Pages](https://pages.github.com/): A service by GitHub that automates rendering markdown into HTML via Jekyll, and hosts the resulting static site for you
- [Tailscale](https://tailscale.com): A VPN service to connect multiple devices securely, peer-to-peer, over the internet reliably, without opening ports on the devices tailscale is installed on on either end
- ISP Firewall: the basic firewall set in place by your ISP so your devices are not accessible by the entire internet
- Stem: Tulip SMP's instance of [Tiramisu](https://github.com/TulipSMP/Tiramisu)


## Minecraft Server

- See [Minecraft Server Plugins](plugins)

Otherwise, the software itself is [Purpur](https://purpurmc.org/), a more-configurable fork of [Paper](https://papermc.io/software/paper).

The server itself runs Fedora Linux, Server edition currently version 37.

## Proxy

As per the [Networking](#networking) section above, the proxy is what connects YOU to the backend Tulip SMP Server. It currently runs in an `e2-micro` "Compute Engine" on Google Cloud.

- [Velocity](https://papermc.io/software/velocity): The proxy software that your minecraft client connects through to access the minecraft server

Plugins:
- CommandWhitelist: Hides all proxy commands from the player
- Geyser: Allows bedrock players to connect
- floodgate: Authenticates bedrock players
- maintenance: Adds ability to turn stop players from connecting to the backend server entirely
- Velocitab: customisation for the TAB menu
- PAPIProxyBridge: fetches placeholders from the proxy, for prefixes/suffixes in the TAB menu
- spark: performance profiler

The server itself runs Debian linux.