# rdptabs.github.io

The project page for **RdpTabs**, a Windows Remote Desktop client with Chrome-style tabs:
<https://rdptabs.github.io/>

The application itself — source, releases, issues — lives in
[yzhou79/RdpTabs](https://github.com/yzhou79/RdpTabs).

## What is in here

One hand-written page, no build step, no framework, no external requests:

| File | |
|---|---|
| `index.html` | The whole page, styles inline. Tab switching is pure CSS (`:checked` on hidden radios), no JavaScript. |
| `site-session.jpg`, `site-newtab.jpg`, `site-error.jpg` | The three screens the tab strip switches between. Identical dimensions so switching does not shift the layout. |
| `tabs.jpg` | Full window shot, used as the Open Graph preview image. |
| `inter-latin.woff2` | Inter, latin subset, variable 400–700. Self-hosted rather than loaded from a font CDN, so the page stays single-origin and visitors' addresses are not handed to a third party. |

To change anything, edit `index.html` and push — GitHub Pages serves this repository's default branch
directly.

The screenshots use invented hosts (`10.0.0.5`, `Jump host`, …); no real machine or account appears in them.
The tab strip on the page is drawn in HTML and CSS with the app's own dark palette, and each screenshot has
its own strip cropped off so the two line up as one window.
