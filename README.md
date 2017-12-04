
Robospin GBC
============

- **Author/Maintainer:** Sean Wallitsch
- **Email:** shidarin@alphamatte.com
- **License:** MIT, CC-BY-NC-SA
- **Status:** Development
- **Version:** 1.0
- **GitHub:** https://github.com/shidarin/robospin_gbc

Introduction
------------

A robospin fork customized for Nintendo Game Boy and Game Boy Color games.
Classic wheel design showcases snaps or videos in the Game Boy Color's screen,
as well as showing flyer and cart art.

[![Theme Preview](preview.png?raw=true)](preview.png?raw=true)

[Original photography](https://www.flickr.com/photos/wenthevegan/6893907701/in/photostream/) 
for this theme is by [Wen Zeng](https://www.flickr.com/photos/wenthevegan/). 
Retrieved via CC-BY license on August 15th, 2015. License on flickr has since 
been changed, but CC-BY cannot be revoked. Modifications have been made to her 
original work.

Installation
------------

The simplest installation method is through git, from within your attract
mode layout folder::

    git clone https://github.com/shidarin/robospin_gbc.git

This will create a `robospin_gbc` folder inside your layout folder, and 
you can now select `robospin_gbc` as a theme for a display.

You can also unzip archives from the [release page](https://github.com/shidarin/robospin_gbc/releases) 
into a `robospin_gbc` folder in your layout folder, and it will do the same 
thing without git.

Usage
-----

`robospin_gbc` uses a new art type, `cart` to display cartridges besides 
any flyer (box) art. If you wish to display carts, you must create a new 
art entry from the emulator settings window.

Options
-------

`robospin_gbc` exposes the following options:

* SpinWheel: The artwork to spin
* Mask: Darkens the area behind the SpinWheel
* Transition Time: Time in milliseconds for wheel spin.

Changelog
---------

*New in version 1.0:*

Initial release.

License
-------

    Code:

    The MIT License (MIT)

    | robospin_gbc
    | Copyright (c) 2017 omegaman, verion, raygun, Sean Wallitsch
    | https://github.com/shidarin/robospin_gbc

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

    Images:

    Original photography by Wen Zeng
    https://www.flickr.com/photos/wenthevegan/6893907701/in/photostream/
    https://www.flickr.com/photos/wenthevegan/
    Distributed under a CC-BY License on August 15th, 2015.
	Modifications have been made.

    Images present in this package are distributed under a CC-BY-NC-SA license
    Note that this is a more restrictive license than the MIT license, and only
    applies to the images.
    http://creativecommons.org/licenses/by-nc-sa/4.0/
    http://creativecommons.org/licenses/by-nc-sa/4.0/legalcode