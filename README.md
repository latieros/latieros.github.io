# Latieros's Content Tools

The home page for all my browser tools, served by GitHub Pages at https://latieros.github.io/.
Each tool lives in its own repo and is served under its own path (for example
https://latieros.github.io/HSR-Chat/).

It's one self-contained `index.html`: no build step, no dependencies.

- **Change a square's picture:** put the image in `logos/` (see `logos/README.md`).
- **Change names, links, order or colors:** edit the `SECTIONS` list at the top of the
  script in `index.html`.
- **Social links:** edit the `SOCIAL` list right below it.

Search engines are asked to stay out: every page carries `noindex, nofollow` and `robots.txt`
disallows everything. The site is still reachable by anyone who has the link.
