# Pair Oscillator

A single-page browser tool for comparing images two at a time. Drop in a set of images (or zip files of images) and they pair up in order: the first with the second, the third with the fourth, and so on. Each pair flips back and forth so the differences jump out.

## Features

- Drop images or zips anywhere on the page; each zip stays its own batch so pairs never straddle two sources
- Adjustable cycles per pair, play/pause, and previous/next pair controls
- Pair strip for jumping around the set
- Save groups of pairs to a local library and bring them back later
- Images are kept in the browser (IndexedDB), with small thumbnails and preloading of the next pair
- Keeps the screen awake while playing

## Running it

Open `index.html` in a modern browser. No build step, server, or account needed. Everything stays on your device.
