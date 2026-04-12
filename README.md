# GD3 Plugin Store

Plugin distribution repository for [GamesDownloader V3](https://github.com/60plus/GamesDownloader).

This repo contains **only** what the Plugin Store UI needs:
- `store.json` - plugin manifest (versions, download URLs, changelogs)
- ZIP attachments on releases - installable plugin packages

## Available Plugins

| Plugin | Type | Version | Description |
|--------|------|---------|-------------|
| **NEON HORIZON** | Theme | 1.2.5 | Cyberpunk theme with Big Picture library, Colorful Pop couch mode, 8 skins, gamepad support, i18n |
| **PPE.pl Metadata** | Metadata | 1.0.2 | Polish game metadata, ratings, and screenshots from PPE.pl |
| **Description Translator** | Tools | 1.0.2 | Translate game descriptions between 26 languages via Google Translate |

## How to use

In GamesDownloader, go to **Settings > Plugin Store** and add this source URL:

```
https://raw.githubusercontent.com/60plus/gd3-plugin-store/main/store.json
```

The app will fetch the manifest, show available plugins with versions and changelogs, and let you install or update with one click.

## For plugin developers

This repo is for **distribution only**. If you want to create your own plugins, see:

- [gd3-plugin-template](https://github.com/60plus/gd3-plugin-template) - documentation, starter templates, hook reference, and working examples with full source code
