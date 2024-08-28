# Evolve

## Play

https://pmotschmann.github.io/Evolve/

## About

An incremental game about cultivating power and growing your sect from an unsouled orphan into a fierce Monarch.
Progress combines elements of a clicker with an idler and has lots of micromanagement.

How far will you make it?

## CSS Changes
Evolve uses LESS to build its CSS, you can not just edit the minified CSS file. You must instead edit src/evolve.less then use the less compiler to rebuild the CSS file.

## Build Commands
Assuming you configured your build environment correctly the game can be built, deployed to GitHub Pages or launched using

```
# Builds everything
npm run build
# Builds the game bundle
npm run evolve
# Builds the CSS file for the game
npm run evolve-less
# Builds the wiki bundle
npm run wiki
# Builds the Wiki CSS file
npm run wiki-less
# Launches the game server locally (localhost:4400)
npm run serve
# Deploys the game to GitHub Pages
npm run deploy
```
