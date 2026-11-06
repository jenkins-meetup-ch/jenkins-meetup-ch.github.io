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

## Contributions

Contributions are welcome!
See the guidelines [here](./CONTRIBUTING.md)
