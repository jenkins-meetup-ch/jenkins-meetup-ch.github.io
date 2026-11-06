# Jenkins Meetup Switzerland

This repository contains an archive of the old meetup group.

## Building the site

The site uses Hugo Extended and its Go module support. With Hugo and Go installed,
run `hugo server` for a local preview or `hugo --gc --minify` for a production
build. The deployment workflow supplies the GitHub Pages base URL.

Event pages live in `content/en/events/`. Include the date, Swiss location,
original Meetup URL, and a short summary when adding an event. Check the Meetup
listing for its status and location; cancelled, online-only, and overseas events
are outside this archive's scope. The archive is incomplete because the full
past-events list on Meetup may require signing in.

Event covers are stored in `static/images/events/` and sourced from the original
Meetup listings' Open Graph images. Set `cover_image` to the path relative to
`static/` and `cover_alt` to a description in the event's front matter; these
are used both on the page and in its Open Graph metadata.

## Contributions

Contributions are welcome!
See the guidelines [here](./CONTRIBUTING.md)
