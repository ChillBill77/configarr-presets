
# Configarr with Presets

Configarr is a powerful configuration and synchronization tool designed specifically for Sonarr v4 and Radarr v5. It streamlines the process of managing custom formats and quality profiles by automatically synchronizing settings from TRaSH-Guides while supporting additional customizations.

## What does it do?

- Quality Profiles use Custom Formats to score and select release
- Sonarr/Radarr use these profiles to make download decision
- TRaSH-Guides provides optimized configurations for bot
- Configarr helps manage and synchronize all these components

This script creates an easy to read configuration profile for [Radarr](https://github.com/2Tiny2Scale/ScaleTail/tree/main/services/radarr) and [Sonarr](https://github.com/2Tiny2Scale/ScaleTail/tree/main/services/sonarr).

## Configuration Overview

This is a simple and single run script which configures a predefined optimized UHD/FHD profile in both [Radarr](https://github.com/2Tiny2Scale/ScaleTail/tree/main/services/radarr) and [Sonarr](https://github.com/2Tiny2Scale/ScaleTail/tree/main/services/sonarr). Fromm the .env file you will need to provide:

- **xxxARR_URL**: This environment variable is where you insert your DNS/IP with port.
- **xxxARR_API**: The API key to allow the creation and updating of the download profile.

This configuration provides xxARR is set up correctly, allowing UHD/FHD quality downloads with an optimal file size and download - at least, to someones interpretation.

## To Run

```bash

>./docker-configarr.sh

```

This script is created on MacOS with Docker Desktop installed.
It was also tested on a Linux environment with Docker installed.

## Some Love

[![Star History Chart](https://api.star-history.com/svg?repos=ChillBill77/configarr-presets&type=Date)](https://api.star-history.com/svg?repos=ChillBill77/configarr-presets&type=Date)

- [ScaleTail](https://github.com/2Tiny2Scale/ScaleTail) Best source for Tailscale enabled Applications
- [Tailscale](https://www.tailscale.com/) The VPN Zero Trust Solution of the next generation
