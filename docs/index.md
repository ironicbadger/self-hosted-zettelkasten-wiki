# Self-hosted Zettelkasten Wiki

Link to blog post - link.

## Overview

A big claim, I know. But using [Obsidian.md](https://obsidian.md/),  [mkdocs](https://www.mkdocs.org/) (with the [material theme](https://squidfunk.github.io/mkdocs-material/)), [Gitea](https://gitea.io/en-us/) and [drone.io](https://www.drone.io/) we can get pretty close to what [Notion.so](https://www.notion.so/) offers. With this stack though, you own 100% of the data *and* it's 100% self-hosted!

This is not a turn-key solution like Notion, some assembly is required. You will need a Raspberry Pi, [VPS](https://www.linode.com/lp/podcasts/?ifso=ssh), or some other always on system to host these services. We'll be using containers to host everything as usual around here but this is a complex project with a lot of moving parts - set your expectations accordingly.

## Build process

![[gitea-mkdocs-obsidian-build.png]]

## Guide steps in order

1. Create / choose a place to [[Hosting Overview|host]] the services.
2. 