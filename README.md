# DjangoCon.us Conference Website

## Installation

This project requires Node v20 or greater.

1. Run `npm install` to install Node packages.

## Building & Development

This project uses Liquid for templating. As such, you may wish to install syntax highlighting for Liquid in your text editor.

* VS Code: [Liquid Language Support](https://marketplace.visualstudio.com/items?itemName=neilding.language-liquid)
* [Liquid documentation](https://liquidjs.com/)

Build and watch for local changes by running:

`npm run serve`

This opens a local server at `http://localhost:8080/` and watches for changes to the source files.

# To Dos

1. Replace autoprefixer and cssnano with lightningcss

# Guidelines for Development

1. While 11ty allows for shortcodes and other customizations, sticking with Liquid fundamentals is preferred for interoperability.
