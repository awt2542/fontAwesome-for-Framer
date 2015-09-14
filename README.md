# FontAwesome for Framer.js

Add Font Awesome icons to your prototypes. Find available icons: [ Font Awesome's Cheatsheet](https://fortawesome.github.io/Font-Awesome/cheatsheet/)

![FontAwesome](http://cl.ly/image/2C0w1Z1l3n2T/fa.png)

## Installation

1. Place the FontAwesome and fonts folder in your /modules folder
2. Add FontAwesome = require 'FontAwesome' to the top of your document


More info about modules in Framer and how to install them: [FramerJS Docs - Modules](http://framerjs.com/docs/#modules)


## Properties (extends Layer)

- .icon - html entity, unicode character or class name.
- .color - color of the icon
- .fontSize - size of the icon

## Examples

### Basic usage
	speak = new FontAwesome
		icon: 'commenting'
		color: 'blue'
		fontSize: 250
	speak.center()

## License

The Font Awesome font is licensed under the SIL OFL 1.1:

* http://scripts.sil.org/OFL

Font Awesome CSS, LESS, and Sass files are licensed under the MIT License:

* http://opensource.org/licenses/mit-license.html

Full details: http://fontawesome.io/license

##Contact

Twitter: [@andreaswah](http://twitter.com/andreaswah)
