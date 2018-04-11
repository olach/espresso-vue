# Vue.js for Espresso
This is a plugin for MacRabbit's [Espresso](https://espressoapp.com) code editor with support for [Vue.js](https://vuejs.org).

## Features

- Syntax highlighting of Vue Single File Components (HTML, CSS, SCSS, Less, [Stylus](https://github.com/aljs/Stylus.sugar), JS, CoffeScript).
- Autocompletion of Vue template syntax, such as `v-bind` and `v-if`.

## Installation

1. Download and extract the zip
2. Double click the Vue.espressoplugin file to install it

Or, if you want to use a Git workflow:

1. Clone this repo
2. From the root of the repository, run this command in the terminal to create a symlink to the Espresso plugin folder:
	`ln -s $(pwd)/Vue.espressoplugin ~/'Library/Application Support/Espresso/Plug-Ins/Vue.espressoplugin'`
3. Restart Espresso
