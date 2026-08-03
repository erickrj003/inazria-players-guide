# Inazria Player's Guide

Public Quartz site for the Inazria player's guide. Hosted on GitHub Pages.

## Source of truth

Player-facing Markdown is authored in the private [`inazria`](https://github.com/erickrj003/inazria) vault under `player/`. Do not treat this repository as the place to draft setting content.

Publish from the vault with:

```powershell
.\scripts\publish-players-guide.ps1
```

That script mirrors `player/` into `content/`, builds Quartz, and pushes this repo so GitHub Pages can deploy.

## Local preview

```bash
npm ci
npx quartz plugin install
npx quartz build --serve
```

Site URL: https://erickrj.tech/inazria-players-guide

## Attribution

Inazria is built on the D&D 5.1 System Reference Document (CC-BY-4.0). See the guide home page for the short attribution note.
