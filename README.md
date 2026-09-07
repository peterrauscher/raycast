# Raycast extensions

Extensions I built for myself. Each folder is a separate Raycast extension.

## [Aria2](aria2/)

Raycast front-end for a local [`aria2c`](https://aria2.github.io/) daemon.

Add magnets or `.torrent` files, pause/resume/remove downloads, and (if you want) install a small macOS helper so clicking a magnet in a browser sends it to aria2 instead of opening Transmission or whatever macOS picked last week.

Install aria2 first (`brew install aria2`). The extension can start the RPC daemon on first use. Setup notes live in [aria2/README.md](aria2/README.md).
