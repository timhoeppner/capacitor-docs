---
title: Splash Screens and Icons
description: Use cordova-res to generate resource images for native projects
contributors:
  - dotNetkow
slug: /guides/splash-screens-and-icons
---

# Creating Splash Screens and Icons

Initial support for splash screen and icon generation is now available. For complete details, including command options, see the [capacitor-assets docs](https://github.com/ionic-team/capacitor-assets).

First, install `@capacitor/assets`:

```shell
npm install @capacitor/assets
```

Create a single `logo.png` or `icon.png` with an optional `logo-dark.png` in `assets/` (the tool also supports using SVG files as source images, substitue `.svg` as needed):

```
assets/
├── logo.png
└── logo-dark.png
```

Then, generate the assets.

```shell
npx capacitor-assets generate
```
