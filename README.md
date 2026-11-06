# Stashy releases

Builds of **Stashy**, a native macOS player for [Stash](https://github.com/stashapp/stash)
(libmpv playback, direct play for every codec). Source is kept private; this repo only hosts
release artifacts.

## Install / update (Apple Silicon)

```bash
curl -fsSL https://github.com/ricktap/stash-desktop-releases/releases/latest/download/install.sh | bash
```

The app updates itself afterwards (signed updates via `latest.json` in the latest release).

Uninstall:

```bash
curl -fsSL https://github.com/ricktap/stash-desktop-releases/releases/latest/download/install.sh | bash -s -- --uninstall
```
