# Archibald - An Open Source Ghost Theme with SASS and grunt support fo robust development

## Getting started!

This is a *starter theme* for Ghost, and is not intended to be used as-is on any site or blog.

Archibald is a complementary up to date clone of Casper default styles and templates that can be mixed, matched, removed or refactored to create a unique Ghost themes using [grunt](https://github.com/gruntjs/grunt) and [libsass](https://github.com/sass/libsass).

Archibald is created and maintained by **CONNECTOME**

## Installation

(More detailed installation instructions coming soon.)

### Prerequisites

1. Node.js
2. Sass (libsass)
3. Grunt


### Installation

Clone (or fork) this repository into your /content/themes/ folder in Ghost.

Run `npm install` in the archibald directory to install grunt modules.

Run `grunt` to build the Sass files, or `grunt watch` to work on your code.


### Build

To build a .zip file of your theme for distribution, run:

`grunt bundle --name=yourthemename`

The *build* folder will contain the necessary theme files, and the *dist* folder will contain a .zip file of your theme that you can distribute and use in other Ghost instances.

## Thanks To:

* [ThemeSpectre](http://themespectre.com/) fot their [Linen](https://github.com/ThemeSpectre/Linen) theme which encouraged me to start this project
* Themble & Eddie Machado for the Bones framework
* HTML5 Boilerplate
* Mono Social Icon Font
* [Ghost](https://github.com/TryGhost/Ghost) and [Casper](https://github.com/TryGhost/Casper)
