# CLAUDE.md — surfn-tela-ubuntu

## Project overview

Standalone repo for the **Surfn-Tela-Ubuntu** folder-icon theme, a colour variant of the base
`erikdubois/surfn` icon set. Folder (places) icons sourced from `vinceliuice/Tela-icon-theme`.

## Current state

Ships one theme: `usr/share/icons/Surfn-Tela-Ubuntu/` — **places only**. Packaged as `surfn-tela-ubuntu-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/surfn-tela-ubuntu/`), `depends=('surfn-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits Surfn. Size-first layout (`<size>/places`) with
  @2x/@3x dir symlinks. `icon-theme.cache` gitignored. Bash scripts follow the Kiro template.
