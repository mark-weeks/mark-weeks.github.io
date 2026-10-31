# Enfolded landing page

Public introduction to [Enfolded](https://github.com/mark-weeks/hello-nested-worlds-adventure), the open-source nested-scale world.

GitHub Pages publishes [`index.html`](index.html) from this repository. That file has no front matter, so Jekyll copies it unchanged and the page bypasses the theme. The page’s `<head>` holds the title and description.

GitHub Pages applies its default Primer theme when this repository does not set one, and the Pages build includes that theme’s assets. `index.html` does not use them. The page file has no JavaScript, no tracker, and no external font.

[`_config.yml`](_config.yml) excludes this README from the site build, and it excludes `CNAME` the way the Pages defaults do. Add a `CNAME` file when `enfolded.world` should point here, and keep `CNAME` in that exclude list.

The hosted world is not deployed. Claims on the page come from the Enfolded README and `docs/`.
