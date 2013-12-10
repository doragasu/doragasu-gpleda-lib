doragasu-gpleda-lib
===================

A collection of free symbols for gschem and footprints for pcb.

Usage
=====

Just make sure you include the path where the symbols are in your `gafrc` file, for gschem to find them. For pcb to be able to use the footprints, add the path where the footprints are located to the `library-newlib` property of your `~/.pcb/preferences` file, like in this example:

    library-newlib = ~/path/to/footprints

License
======

Symbols are distributed under GPLv3+ license, but can be used without restrictions.
