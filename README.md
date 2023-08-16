# shairport-sync-docker-compose-orange-pi-zero-3
Using Docker Compose to host Shairport-sync on Orange Pi Zero 3 with Orange Pi Expansion Board.

# Environment
- Shairport-sync:latest (Current Version: 4.2)
- Docker Compose
- Debian 11 XFCE Desktop Environment(Orange Pi offcial image)
- Orange Pi Zero 3(4GB RAM) with Orange Pi Expansion Board.
- Orange Pi Expansion Board's 3.5mm audio jack as audio output.

# Issue
Audio will heavly delay causing audio stutter.

# Fix
Follow the [TROUBLESHOOTING](https://github.com/mikebrady/shairport-sync/blob/master/TROUBLESHOOTING.md#stuttering-audio-on-certain-usb-dacs-such-as-the-creative-soundblaster-mp3) guide to create **asound.conf** file and supply it into the container.
