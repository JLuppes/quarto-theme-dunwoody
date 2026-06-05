# Dunwoody Quarto Theme

This repo provides a custom Dunwoody theme for Quarto, which will generate RevealJS HTML slideshow presentations.

## Demo

You can see the [setup](https://jluppes.github.io/quarto-theme-dunwoody/Slides/Setup/Setup.html) and [demo](https://jluppes.github.io/quarto-theme-dunwoody/Slides/Demo/demo.html) presentations on [GitHub Pages](https://jluppes.github.io/quarto-theme-dunwoody/).

Note - these are optimized for half-screen presentation (side-by-side with another window), but should be responsive and work pretty well in most resolutions.

## First Time Setup

The easiest way to get started is to use this repo as a [Quarto Starter Template](https://quarto.org/docs/extensions/starter-templates.html).

To do that:

- First, install [Quarto CLI](https://quarto.org/docs/get-started/)
- Then, in a terminal, pull down the template files:

```shell
quarto use template jluppes/quarto-theme-dunwoody
```

This will ask you if you want to create a subdirectory; up to you!

The folder you create/use will now be considered a Quarto Project.

### Updating

Simply run the quarto template command again, and it should overwrite the template files.

Warning - this might overwrite changes to your configuration files, and any manual changes you've made to the `.scss` file. Back those up first if you've made modifications to either!

## Authoring

There are two presentations included in the repo, `Setup` and `Demo` which have some useful information about how to get started, and can themselves be used as reference for building your own presentations.

Mainly, you'll make `.qmd` files in the `Slides` directory, and then you can use `quarto render` in your project folder to generate all of the presentation files. With default configuration, this will make an HTML slideshow using [Reveal.js](https://revealjs.com/) and a PDF version.

You can also use the excellent VS Code extension to enable useful syntax highlighting, auto-completion, and the `Quarto Preview`, which will serve up a live version of your slides which can be helpful for authoring.
