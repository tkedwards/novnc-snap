# novnc-snap
Snap Package for noVNC

**Build**
# Edit snap/snapcraft.yaml or whatever needs to be edited
snapcraft snap --use-lxd
sudo snap remove novnc; sudo snap install --dangerous novnc_*amd64.snap

**Test and Upload Snap to the Store**
- test Snap
- upload to store: snapcraft push /path/to/novnc*.snap
- Put the uploaded release in channel latest/stable: https://snapcraft.io/novnc/releases
