---
title: Makerspace VPN
description: 
published: true
date: 2020-02-13T22:22:43.549Z
tags: 
---

# Makerspace VPN

The UTDesign Makerspace hosts several serivces on the public cloud, platforms-as-a-service and On-Site Servers. This means non-essential makerspace services are usually only accessible from inside the makerspace networks. These services include:

- Octoprint and other 3d printing related services
- Game services including our Minecraft Servers
- Membership Services
- Internal Git Repositories
- Video Rendering Servers
- Shared Internal Storage
- Virtual Machines

## Connecting to Makerspace Services outside of Makerspace Networks

For all Makerspace VPN needs we rely on [Zerotier](zerotier.com). Zerotier is a free service that allows us to create fast VPN networks for members to utilize.

Zerotier supports Windows, Mac and Linux and can be installed from Zerotier's website [zerotier.com/download](https://www.zerotier.com/download/). Once installed attempt to join our network with the following id: `b6079f73c65e2beb`. After
doing so send an email to [vpn@utdmaker.space](mailto://vpn@utdmaker.space) from your student/faculty email ending in `@utdallas.edu`. Include your Zerotier clientID and your join request should be approved within 1 business day.