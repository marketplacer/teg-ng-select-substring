# Overview

Highlights a subsctring in a HTML text.

## Install

    bower install <path to github repo>

Include the JS script:

    <script src="/bower_components/<path to file name>.js"></script>

If you need to support IE8 and other older browsers please include:

    <script src="/bower_components/es5-shim/es5-shim.min.js"></script>

Add module to your app's dependencies:

    angular.module('YourApp', ['TegNgSelectSubstring'])

## Usage

    tegSelectSubstring.select('My penguin is happy!', 'Penguin')

will produce:

    My <span class='SelectedSubstring'>penguin</span> is happy!


## Development

After cloning the github repo into a dir:

    npm install
    bower install

Test:

    gulp test

Build:

    gulp

Finally, bump bower version number:

    git tag v0.1.[patch number]
    git push origin v0.1.[patch number]



