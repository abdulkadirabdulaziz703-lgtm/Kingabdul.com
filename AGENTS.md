# Base44 Setup Notes

## Project
Single static HTML page (`HTML.COM`) — "King Abdul - Official Website". No backend, no framework, no build step, no dependencies.

## Running
Served by `nginx:alpine` via `docker-compose.base44.yml` on host port 3000.
`nginx.base44.conf` sets `index HTML.COM` so the file is served at `/`.

## Editing
Edit `HTML.COM` directly. Changes appear on browser refresh (call `reload_preview` after edits — nginx has no live-reload).

## Secrets
None required.
