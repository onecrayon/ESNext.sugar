# ESNext.sugar

ESNext.sugar adds support for ECMAScript 2015 and 2016 files in Espresso (_aka_ ES6, ES Next, and a bunch of other random names)

ES Next syntax highlighting will trigger for documents with the following extensions:

* `.es`
* `.es6`
* `.babel`

Or for `.js` files with either a "hashbang" style comment as the first line. Here is a subset of available options, all of which are case insensitive, don't care about whitespace, and can have a space, hyphen, or nothing between words:

* `//! esnext` or `//! ES Next` or `//! ES-Next` or...
* `//! ECMAScript 2016` or `//! ES 2016` or `//! es2015` or...
* `//! ES-6` or `//! ES7` or...

The ES Next syntax will also trigger if the very first line of your `.js` file is the string `'use babel'`.

## Installation

**Requires Espresso 2.2+**

The best way to install ESNext.sugar is directly from GitHub:

    cd ~/Library/Application\ Support/Espresso/Sugars
    git clone git://github.com/onecrayon/ESNext.sugar.git

Relaunch Espresso, and ES Next will be available in your **View&rarr;Languages** menu. You can then update the Sugar when necessary by running the following command:

    cd ~/Library/Application\ Support/Espresso/Sugars/ESNext.sugar
    git pull

Alternately, you can [download the Sugar](https://github.com/onecrayon/ESNext.sugar/zipball/master), decompress it, rename the resulting folder `ESNext.sugar`, and double click to install it.

## MIT License 

Copyright (c) 2016 Ian Beck

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
