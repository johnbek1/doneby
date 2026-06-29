# DoneBy

A mobile-first **pocket portfolio** for hands-on service workers — stylists, food-van operators, flooring contractors, and anyone whose work is best shown in photos.

Each person gets a page where their work spins in a 3D ring inside a curved "room." Photos are grouped into **jobs** (one card per job); tap a job to flip through its photos. Built to be created on the spot, from the worker's own phone photos.

## Status

Working HTML/JS prototype (single file). In-person sales validation phase — validating the paid/pro wedge with real service workers before building consumer features.

## Features

- 3D spinning **ring of jobs** inside a curved cylinder room
- One card per job (cover photo + name + count); tap to open and swipe the job's photos
- Ring auto-spaces so cards never touch, however many jobs you add
- 7 room color themes + put-your-own-photo-on-the-wall
- Public / private toggle per photo (private stays off the spinning page)
- One short video clip supported on the ring
- Add background music (picker UI)
- Profile (name, avatar, what-you-do), WhatsApp + Call buttons, share link
- Export a photo with a name + doneby.com watermark
- Everything saved locally on the device (localStorage)

## Run it

It's a single file. Either:

- Open `index.html` directly in a browser, **or**
- Serve the folder: `python3 -m http.server 8000` then visit `http://localhost:8000`

## Hosting (free, live link)

This repo is ready for **GitHub Pages**. Once pushed, enable Pages on the `main` branch and your page is live at `https://<username>.github.io/doneby/`.

## Versioning

Changes are tracked with git tags (semver). See [CHANGELOG.md](CHANGELOG.md).

## Roadmap (v2, starred)

- Custom uploaded background (auto-dimmed), optional muted music
- Plan tiers: Free (~10 photos + 1 video) vs Paid (50–100+ photos, 5–10 clips)
- Social export with watermark
- Consumer expansion: personal spinning slideshows castable to TV
