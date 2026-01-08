# README

## Lunchbreak
An easy-to-configure countdown/timer.

## Description
A simple countdown/timer that can be used in full screen mode in online training sessions, meetings, or webinars to display the remaining time during breaks. It can be configured to count down from a specified number of minutes or to a specified time.

## Installation
Simply clone the repository and run `docker compose up -d`. The web app itself is located in the `public` folder. If you want to change the background image it can be customized in `style.css`.

If necessary, the port can be adjusted in the `Caddyfile`. The `compose.yaml` file is already configured for use behind an Nginx Proxy Manager; if necessary, the network configuration may need to be adjusted here.

## License
Mozilla Public License Version 2.0
