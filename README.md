# The Blowtorch of Parma — Simple Public Site

Static GitHub Pages version with no admin login, member login, Supabase, database, or build system.

Pages:
- Home
- About
- Library
- Solar & Propagation
- Contact

## Publish
Upload the contents of this folder to the root of a GitHub repository, enable GitHub Pages from the main branch, and point the custom domain to it if desired.

## Library
Place only public documents in `docs/` and add links in `library.html`.

## Solar data
`solar.html` retrieves public NOAA SWPC JSON endpoints directly in the visitor's browser. If an endpoint is unavailable, the page keeps direct NOAA links as a fallback.
