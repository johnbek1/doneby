# Changelog

All notable changes to DoneBy. Format loosely follows Keep a Changelog; versions use semver.

## [0.1.0] - 2026-06-28

Initial tracked version of the prototype.

### Added
- 3D spinning ring of **jobs** — one card per job with cover photo, name, and photo count
- Tap a job to open it; swipe (or ‹ › arrows) through that job's photos
- Curved cylinder "room" behind the ring, shaded to curve away left/right
- Ring radius auto-scales with job count so cards keep an even gap
- 7 room color themes + custom photo-on-the-wall
- Public/private toggle per photo
- One video clip on the ring
- Music picker, profile (name/avatar/about), WhatsApp + Call, share link, watermark export
- In-app text input (replaces browser prompts that are blocked in sandboxed previews)

### Fixed
- Spinning cards no longer pop/jump in front of each other (now true 3D depth sorting)
- Could only create one job — job naming now works inside sandboxed previews and on mobile
