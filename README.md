# Hyperion Client website

Public information for the Hyperion Client Windows launcher, published at
[wolfiy044.github.io/hyperion-client](https://wolfiy044.github.io/hyperion-client/).
This repository contains the static website, not the launcher source or binaries.

- `index.html`: current profile, modpack, social, server and launcher features;
  authentication, requirements, protected-session behavior and availability.
- `privacy.html`: local and backend data, recipients, retention, user controls
  and private contact information, including conditional anti-cheat checks.
- `terms.html`: Minecraft licensing, third-party distribution rules, community
  features and protected-session requirements.
- `style.css`: shared Hyperion theme, responsive navigation and keyboard focus.

The in-game client mod is temporarily disabled. Loader compatibility depends on
the selected Minecraft version. A Microsoft Store submission is being prepared;
this website does not currently offer a public download.

## Preview

No build step or package installation is required. Serve this directory with a
static HTTP server, for example `python -m http.server 8080`, then open localhost.
GitHub Pages publishes the root directory of `main`.

Use GitHub issues for public bug reports. Send account and privacy requests to
nicklinke.12434@gmail.com; do not post credentials or private account details in issues.
