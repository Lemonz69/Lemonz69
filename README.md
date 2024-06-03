# Moddable HTML Project

This is a simple HTML project designed to be easily moddable.

## Structure

- `index.html`: The main HTML file.
- `css/styles.css`: The base CSS file.
- `js/script.js`: The base JavaScript file.
- `mods/`: Directory for mods.

## Creating a Mod

1. Create a new directory inside the `mods/` directory.
2. Add your mod's CSS and JavaScript files in the new directory.
3. Include your mod's CSS and JavaScript files in `index.html`.

Example:

```html
<link rel="stylesheet" href="mods/example-mod/mod.css">
<script src="mods/example-mod/mod.js"></script>
