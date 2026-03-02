# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a minimal static website — a single HTML page displaying a full-screen background image (`background.jpg`, 2400×3000px, by Michael Diolosa).

## Development

No build tools, package managers, or frameworks are used. Open `index.html` directly in a browser or serve with any static file server:

```sh
python3 -m http.server
# or
npx serve .
```

## Structure

- `index.html` — Single page with inline CSS; uses `background.jpg` as a full-viewport CSS background
- `background.jpg` — Source image asset
