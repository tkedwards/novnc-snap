# novnc-snap

Unofficial Snap Package for noVNC. As of 1.2.0 the official Snap package is not working, this mini-project provides a working Snap package until the official one can be fixed.

## Build

```bash
# Edit snap/snapcraft.yaml to specify the latest releases of novnc and websockify
snapcraft snap --use-lxd
sudo snap remove novnc; sudo snap install --dangerous novnc_*amd64.snap
```

## Test and Upload Snap to the Store

- test Snap
- upload to store: snapcraft push /path/to/novnc*.snap
- Put the uploaded release in channel latest/stable: https://snapcraft.io/novnc-snap/releases
