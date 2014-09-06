genico
======

Generate icons automatically, so you don't have to.

## Background

The inspiration for this project comes from [audreyr](https://github.com/audreyr)/[favicon-cheat-sheet](https://github.com/audreyr/favicon-cheat-sheet).  The process of properly creating favicons for a website used to painfully time consuming.  Now there is genico.

## Setup

Genico depends on [Imagemagick](http://www.imagemagick.org/) and [OptiPNG](http://optipng.sourceforge.net/)
```bash
$ sudo apt-get install imagemagick optipng
```


## Run

Genico takes two arguments; your image and the output directory.  Run it like this
```bash
$ ruby genico.rb favicon.png output/
```
