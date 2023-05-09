# Arcadia Styles

SCSS styles for the Arcadia Research website.

## Usage

Initial setup:

* Node version > 14 recommended. 
* Install packages using npm: `npm install`

Development:

* Generate styles ready for PubPub CSS entry using `npm run release`
* Generate styles as above, putting results directly into clipboard (Mac only) using `npm run release:copy`
* Compile styles without outputting release format using `npm run build` (`release`/`release:copy` uses this in their scripts)
* Watch styles using `npm run watch` when styles are linked using `@import` (during development cycle)

For getting final styles up to PubPub, we primarily use `release:copy`.
