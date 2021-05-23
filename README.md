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

<img src="screenshots/br-1.jpg" width="326"> <img src="screenshots/br-2.jpg" width="123">

### `Gzip file`

Creates a `gz` file of a selected file. Requires `gzip` (built-in).

<img src="screenshots/gz-1.jpg" width="323"> <img src="screenshots/gz-2.jpg" width="132">

### `Convert to JPEG`

Creates a copy of an image file in JPEG format.

<img src="screenshots/jpg-1.jpg" width="370"> <img src="screenshots/jpg-2.jpg" width="105">

### `Resize images`

Creates copies of selected image files and resize them to a specific size (width).

<img src="screenshots/resize-1.jpg" width="434"> <img src="screenshots/resize-2.jpg" width="575"> <img src="screenshots/resize-3.jpg" width="143">

### `Translate to English`

Translates text to English, showing a popup of [Google Translate's website](https://translate.google.com/).

<img src="screenshots/trans-1.jpg" width="483"> <img src="screenshots/trans-2.jpg" width="731">

Other useful resources
---

- [Quick Look plugins](https://github.com/sindresorhus/quick-look-plugins)