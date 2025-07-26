# nature-of-code

Coding along to [the awesome book by the same moniker](https://natureofcode.com/introduction/) along with the many awesome little nuggets to be found on [The Coding Train](https://thecodingtrain.com/).

## Contents of this folder

* `_lib/`
  * `p5.js`
  * `p5.min.js`
  * `p5.sound.js`
  * `p5.sound.min.js`
* `empty-example/`
  * `index.html`
  * `sketch.js`

## Resources


### _lib directory

The `_lib` directory includes `p5.js` and related related libraries, in both original versions and minified versions (*where possible*).

#### p5.js, p5.min.js

The main file stores the complete `p5.js` library. It is easy to read by humans, so feel free to open it and explore its contents. It also has a friendly error system, which helps new programmers with common user errors.

The minified file is a lighter version, with the same functionalities, but smaller file size. This minified version is harder to read for humans, and does not include the friendly error system.

#### p5.sound.js, p5.sound.min.js

p5.sound extends `p5.js` with Web Audio functionality including audio input, playback, analysis, and synthesis.

### empty-example director

This is an empty example of a website. The folder includes the file for the website, index.html, and a template starting point for your `p5.js` sketch, called sketch.js.

#### index.html

index.html is a template for an HTML file. This index.html first imports the libraries included in the root folder (`p5.js`, `p5.sound.js`) then loads and executes the file sketch.js which is where you can write your own code.

#### sketch.js

The sketch.js is a template for the p5.js sketch, with the functions setup() and draw() that you can complete.

## What's next?

For more information to help with getting started, please refer to the `p5.js` website:  
<https://p5js.org/tutorials/get-started/> and <https://p5js.org/tutorials/>

An online reference to the `p5.js` library is available here:  
<https://p5js.org/reference/>

In order to run your website (including the empty-example), you need to enable a local server, please see this tutorial in our wiki:  
<https://github.com/processing/p5.js/wiki/Local-server>

## License

The p5.js library is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation, version 2.1.
