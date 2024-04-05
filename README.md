# SpotiPi E-Ink

## Overview

This project is to display information on a 5.7" e-ink using the [Spotify web api](https://developer.spotify.com/documentation/web-api), check out a demo on [YouTube](https://www.youtube.com/watch?v=uQYIAYa27ds).

---

## Quick Start

### Create Spotify Developer Account

- Create a new application within the [Spotify developer dashboard](https://developer.spotify.com/dashboard/applications)
- Edit the settings of the application within the dashboard
  - Set the redirect uri to any local url such as http://localhost/redirect

### Configure RaspberryPi

- Enable `SPI` and `I2C` under "Interface Options"

```sh
sudo raspi-config
```

- Download the install script

```sh
wget https://raw.githubusercontent.com/ryanwa18/spotipi-eink/main/setup.sh
chmod +x setup.sh
```

- Install the software

```sh
sudo bash setup.sh
```
