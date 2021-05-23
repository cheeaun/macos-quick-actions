My MacOS Quick Actions
===

This repo contains a list of macOS Quick Actions / Services that I use on my machine. They are Automator workflow scripts.

Requirements
---

- Shell: `zsh`
- OS: macOS 11 Big Sur
- [Automator](https://support.apple.com/en-gb/guide/automator/welcome/mac)

Installation
---

Copy scripts from `scripts` folder to `~/Library/Services`.

Scripts
---

### `Brotli file`

Creates a `.br` file of a selected file. Requires [brotli](https://formulae.brew.sh/formula/brotli)

![](screenshots/br-1.jpg) ![](screenshots/br-2.jpg)

### `Gzip file`

Creates a `gz` file of a selected file. Requires `gzip` (built-in).

![](screenshots/gz-1.jpg) ![](screenshots/gz-2.jpg)

### `Convert to JPEG`

Creates a oopy of an image file in JPEG format.

![](screenshots/jpg-1.jpg) ![](screenshots/jpg-2.jpg)

### `Resize images`

Creates copies of selected image files and resize them to a specific size (width).

![](screenshots/resize-1.jpg) ![](screenshots/resize-2.jpg) ![](screenshots/resize-3.jpg)

### `Translate to English`

Translates text to English, showing a popup of [Google Translate's website](https://translate.google.com/).

![](screenshots/trans-1.jpg) ![](screenshots/trans-2.jpg)

Other useful resources
---

- [Quick Look plugins](https://github.com/sindresorhus/quick-look-plugins)