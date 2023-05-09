# Arcadia Styles

SCSS styles for the Arcadia Research website.

## Usage

Initial setup:

* Node version > 14 recommended. 
* Install packages using npm: `npm install`

Development:

* Watch styles when styles are linked using `@import` (during development cycle)
* Compile styles using `npm run build`
* Generate styles ready for PubPub CSS entry using `npm run release`
* Generate styles as above, putting results directly into clipboard (Mac only) using `npm run release:copy`

For getting final styles up to PubPub, we primarily use `release:copy`.
