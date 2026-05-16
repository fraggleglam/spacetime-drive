# SpaceTime Drive

A native macOS Finder extension that mounts Backblaze&nbsp;B2 buckets like local hard drives. Built for post-production teams handing off media to producers, clients, and freelancers.

**Landing page:** https://fraggleglam.github.io/spacetime-drive/
**Latest release:** https://github.com/fraggleglam/spacetime-drive/releases/latest

## What it is

SpaceTime Drive is the producer-facing companion to [SpaceTime Link](https://spacetime-link.web.app) (the editorial app for Avid/Premiere workflows). Where Link uses JuiceFS + macFUSE for high-throughput editorial mounts, Drive uses the native macOS File Provider framework — no kernel extension, no Recovery Mode, no reboot.

## Features

- **Mounts in Finder** — Each workspace appears as a Desktop drive.
- **Direct to B2** — Reads and writes straight to your Backblaze B2 bucket. No middle servers.
- **Per-user access** — Admins see everything; producers and freelancers see only the buckets they've been granted.
- **Notarized** — Apple-notarized .app inside an Apple-notarized .dmg.

## System requirements

- macOS 13 Ventura or later
- Apple Silicon or Intel (universal binary)
- An invited account (your team admin sets you up)

## Install

1. Download the DMG from the [latest release](https://github.com/fraggleglam/spacetime-drive/releases/latest).
2. Drag SpaceTime Drive to Applications.
3. Launch and sign in.

---

© 2026 Alter Ego Films
