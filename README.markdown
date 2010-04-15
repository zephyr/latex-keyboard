
# latex-keyboard

## Purpose

The “keyboard” package provides a single command `\keyboard` to print a special keyboard layout.

## How to Compile

### Using the makefile

To compile everytink, just execute the makefile:

    xelatex --shell-escape makefile

The option `--shell-escape` *is needed* here!

### Fast by hand

Just type

    xelatex keyboard.dtx

This will give you the documentation (without index or change history) as well as the style file and the (uncompiled) demo file.

Even though the documentation depends on XeTeX, the package itself works under every LaTeX engine and can be created with

    tex keyboard.dtx

## Status

This package has not yet reachead a stable status, so the user intferface may change!

## Licence

Copyright 2010 by Dennis Heidsiek

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License, either version 1.3 of this license or (at your option) any later version. All versions of this license (including the latest one) can be accessed online [from the homepage of the LaTeX-project](http://www.latex-project.org/lppl/), but you can also find a local copy of version 1.3 in the LICENCE file.

This work has the LPPL maintenance status “*maintained*” and the Current Maintainer of this work is [Dennis Heidsiek](http://www.google.com/profiles/Dennis.Heidsiek).

This work consists of the file

* keyboard.dtx

and the derived files

* keyboard.sty
* keyboard.pdf
* keyboard-demo.tex
* keyboard-demo.pdf
