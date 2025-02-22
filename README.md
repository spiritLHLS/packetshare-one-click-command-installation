# packetshare-one-click-command-installation

## Language

[English](README.md) | [中文文档](README_zh.md)

## **Introduction**

The packetshare is an option that allows users to earn money by sharing your traffic.

You'll receive $0.10 for the 1G traffic you share, and this script only supports residential bandwidth.

It has below features:

1. Automatically install docker based on the system, and if docker are already installed, it will not installed again.

2. Automatically select and build the pulled docker image according to the architecture, without the need for you to manually modify the official case.

3. Use Watchtower for automatic mirror update without manual update and re-entry of parameters.

(Watchtower is a utility that automates the updating of Docker images and containers. It monitors all running containers and related images, and automatically pulls the latest image and uses parameters when initially deployed to restart the corresponding container.)

## Notes

- Verified on AMD64 and ARM
- Try it if you are interested via my --> [referrals](https://www.packetshare.io/?code=D56687E3945939C7) <--, you will get 5 dollar.

## Install

### Interactive installation

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/packetshare-one-click-command-installation/main/packetshare.sh -o packetshare.sh && chmod +x packetshare.sh && bash packetshare.sh
```

After the registration link is registered, paste your Email and Password, and press Enter to start the installation.

### One command installation

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/packetshare-one-click-command-installation/main/packetshare.sh -o packetshare.sh && chmod +x packetshare.sh && bash packetshare.sh -m your_email -p your_password
```

At the end of this command, modify it to your Email and Password and run it with one click

## Uninstall

```shell
bash packetshare.sh -u
```

uninstall service

## Experience

Revenue is very stable, single IP basically consumes 148MB of traffic per day, equivalent to about $0.014 per day

## Disclaimer

This program is for learning purposes only, not for profit, please delete it within 24 hours after downloading, not for any commercial use. The text, data and images are copyrighted, if reproduced, please indicate the source.

Use of this program is subject to the deployment disclaimer. Use of this program is subject to the laws and regulations of the country where the server is deployed, the country where it is located, and the country where the user is located, and the author of the program is not responsible for any misconduct of the user.
