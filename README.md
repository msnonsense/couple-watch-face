# Couple Watch Face Generator

A tiny web app that makes an Apple Watch photo-face image with a couple's names,
sized and styled to be read at a glance. It runs **entirely in your browser** with
no server and no tracking; nothing you type ever leaves your device.

## Use it

- **On a computer:** open the page, edit the names, click **Save image**.
- **On an iPhone/iPad:** open the page in Safari, then **Share ▸ Add to Home
  Screen** to install it as an offline app. Tap **Save image**, choose **Save
  Image** to put the PNG in Photos, then set the watch to a **Photos** face.

Type one word per line. The last line is usually the surname spelled the way it
sounds, so the name is easy to say out loud:

```
Name
&
Name
SaysLikeThis
```

Controls let you change the font style, watch size, text thickness, line spacing,
edge padding, and whether to reserve space for the watch clock. The text
auto-fits to the largest size that stays inside the watch-safe area.

## What's here

Static files only: `index.html` (self-contained, with the font embedded),
`manifest.webmanifest` and `sw.js` (so it installs and works offline), and
`icons/`. Host it on any static host (this repo is served via GitHub Pages).

The embedded typeface is [Merriweather](https://github.com/EbenSorkin/Merriweather),
used under the SIL Open Font License (`fonts/OFL.txt`).
