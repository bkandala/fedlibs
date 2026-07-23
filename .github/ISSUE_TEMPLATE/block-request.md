---
name: New shared block request
about: Request a new block be added to fedlibs instead of forking it locally
title: "[block request] "
labels: block-request
---

**Which site needs this?**

**What should the block do?** (attach a design/content example if you have one)

**Does something close already exist in the catalog?**
Check `https://main--fedlibs--{org}.aem.live/blocks-catalog.json` first —
if something's 80% of the way there, propose extending it instead of a
net-new block.

**Is this genuinely site-specific, or would other sites likely want it too?**
If it's genuinely one-off (unique brand treatment, one-time campaign),
say so — that's a legitimate reason to keep it local via
`blocks/local-overrides.json` in the site's own repo, and you don't need
this template. This template is for anything with reuse potential.
