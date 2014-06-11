# The “Flower Power” Component Style Guide

This mini-project is both:

* An example of an auto-generated CSS style guide (using kss-node)
* An example of how Design Components should be structured.

The rendered version of this project is available at http://johnalbin.github.io/flower-power

<img src="images/flower.png" alt="The fully rendered Flower component">

## Installation

The build scripts require `node-kss` to be installed in this directory. [node-kss](https://github.com/hughsk/kss-node) is a Node.js port of KSS. To install node-kss:

1. Install Node.js on your local system. With Homebrew on Mac OS X, you can install it with `brew install node`.
2. Use Node.js' package manager, npm, to install the node-kss and its dependencies based on the versions specified in `package.json`.
   * From the root of this project, run: `npm up`

## Building the style guide

Each time a component in the `sass` folder is modified:

1. Document the CSS classes using KSS as described on the [KSS Node website](https://github.com/hughsk/kss-node).
2. Run: `./build`
