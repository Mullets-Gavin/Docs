<div align="center">
<h1>Minimal Docs</h1>

Minimal theme repurposed for project documentation. Template documentation for all of my projects.
</div>

## About

Minimal Docs was created using the base Jekyll theme provided [here](https://github.com/pages-themes/minimal). Originally intended as a blog theme, it was repurposed for simple documentation purposes. Minimal Docs uses the [Waves](https://github.com/Mullets-Gavin/Waves) syntax highlighting theme for code blocks.

View a live demo [here](https://mullets-gavin.github.io/Docs/)

## Usage

This theme is intended to use with GitHub Pages. Using this theme is quite simple since it's a Jekyll theme on GitHub. Here's how you can use this:

1. Clone or download this template & create a folder named `docs`, and move all of the contents of this repository excluding the license & readme into the folder.
2. Open up your project & paste the folder into it.
3. When you publish to GitHub, go to your repositories settings and scroll down to the GitHub Pages section.
4. Select branch `master` (or whatever you name it) and select the `/docs` folder.
5. Your beautiful documentation will now appear within a minute.

Configuring the theme is quite simple, open up the file `_config.yml` and change the title & description to support your markdown pages. Create markdown files & link them in the navigation section as an html page since that's what it will be converted to. For example, `index.md` will be able to be linked to as `index.html`:

```html
<a href="index.html">Navigation Link</a> <!--points to index.md-->
```