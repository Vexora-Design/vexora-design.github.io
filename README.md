# VEXORA — compiled GitHub Pages website

This repository contains the **built static site only**. The editable React project lives in [Vexora-Design/pages-source](https://github.com/Vexora-Design/pages-source).

- Official source: [pages-source](https://github.com/Vexora-Design/pages-source)
- Website repository: [vexora-design.github.io](https://github.com/Vexora-Design/vexora-design.github.io)
- Custom domain is defined by the preserved `CNAME` file.

## Rebuilding the site

Open **Actions → Rebuild VEXORA from official source → Run workflow**.

The workflow checks out the two repositories into sibling folders, installs the actual npm dependencies, runs validation, builds into the *separate* website checkout, and commits the resulting HTML/CSS/JS/images to this repository. It preserves `.git`, `.github`, `CNAME` and README.

## Stack

React, Vite, GSAP, ScrollTrigger and original React Bits components. Persian is the default language, with English toggling persisted in a cookie.

**Do not commit editable source code into this repository. Do not use `emadgh/emadgh.github.io` for VEXORA.**
