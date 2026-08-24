# OPERATION RESCUE-LINK: MOBILE C2

A zero-dependency, portrait-first mobile rescue game built with one HTML file. It uses procedural Canvas 2D graphics, A* pathfinding, Web Audio synthesis, and mobile vibration feedback—no assets, packages, CDNs, or build step.

## Publish on GitHub Pages in 3 steps

1. Create a new GitHub repository and upload `index.html` plus `README.md` to its root.
2. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then click **Save**.
3. Open the Pages URL shown by GitHub on a smartphone in portrait orientation. Tap the map to route the UGV; use **Pulse**, **Boost**, and **Ascend** to reach the survivor.

## Controls

- **Tap the LiDAR map:** set an autonomous waypoint.
- **Thermal / LiDAR Pulse:** reveal a large area and acquire a life-sign reading; costs 8% battery.
- **Clear Debris / Boost:** destroy nearby brown rubble; costs 6% battery when debris is cleared.
- **Ascend Level:** activates when the UGV reaches the amber stairwell.

Audio begins after the first user interaction, as required by mobile browsers. Haptics require a device/browser that supports the Vibration API.
