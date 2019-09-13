# test-assets

A tiny, self contained version of front-end assets for testing and debugging.

Everybody has that point where they need to test a build system, compiler, optimizer or any other utility that requires assets.  
That's where test-assets comes in, it clones a bunch of html, css, js, images, fonts and svg's right into your project folder with one easy command.

## Installation:

``git clone https://github.com/BillieBobbel23/test-assets your/path/here``

## contents

test-assets contains: 

* An index.html file
* An .SCSS file with some styles used for index.html
* A Javascript file
* A TTF fontfile ([Lato](http://www.latofonts.com/))
* Some images of cats ([freeimages](https://www.freeimages.com/))
* A few SVG's 

everything is contained within the ``src`` folder

## Usage
This is simply a self contained module of front-end assets that is useful for testing and debugging of (automation) tools.  
Apply it where needed.

**See it in action**
 
[nodejs-boilerplate](https://github.com/BillieBobbel23/node-boilerplate) uses this package for debugging by running it's tasks against it.
