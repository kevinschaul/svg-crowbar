#SVG Crowbar

_Minimally altered to better support Washington Post-specific fonts_

A Chrome-specific bookmarklet that extracts SVG nodes and accompanying styles from an HTML document and downloads them as an SVG file—A file which you could open and edit in Adobe Illustrator, for instance. Because SVGs are resolution independent, it’s great for when you want to use web technologies to create documents that are meant to be printed (like, maybe on newsprint). It was created with [d3.js](http://d3js.org) in mind, but it should work fine with any SVG.

[Original project page](http://nytimes.github.com/svg-crowbar/)

[Post crowbar](javascript:javascript: %28function %28%29 { var e = document.createElement%28'script'%29; e.setAttribute%28'src', 'https://s3.amazonaws.com/postgraphics/_tools/crowbar/svg-crowbar-2.js'%29; e.setAttribute%28'class', 'svg-crowbar'%29; document.body.appendChild%28e%29; }%29%28%29;) ← Drag this to your bookmarks bar.
