# 3DS Audio Prep Station

A browser-based tool for preparing audio files for 3DS playback: preview audio, inspect/replace artwork, edit metadata, and convert to a 3DS-friendly M4A download entirely in the browser.

**Live:** https://ethanthatonekid.github.io/3ds-demo/

## Features

- Load an audio file in the browser
- Read embedded title, artist, and artwork metadata
- Replace cover art with a PNG or JPG
- Edit track title and artist live
- Convert to a 3DS-ready M4A using FFmpeg.wasm

## Usage

Open `index.html` in any browser. No server required.

## Notes

This project uses external CDN scripts for Tailwind, jsmediatags, and FFmpeg.wasm, so it can be hosted as a static GitHub Pages site with no build step.