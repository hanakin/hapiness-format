
# sane-format
  This is a fork of [hapiness-format](https://github.com/martinheidegger/hapiness-format) same concept but with soft 4 space tabs like the rest of the world uses!

## Installation

  Install with npm

    $ npm install -g sane-format

## Example Usage

  Output all formatted javascript in a directory and subdirectories to stdout

    $ sane-format

  Format all javascript files, overwriting them into standard format

    $ sane-format -w

  Format javascript over stdin

    $ sane-format < file.js > formatted-file.js

  Format and overwrite specific files

    $ sane-format -w file1.js file2.js

### Editor plugins

  - Sublime Text: [sublime-standard-format](https://packagecontrol.io/packages/StandardFormat)
  - Atom: [atom-standard-formatter](https://atom.io/packages/standard-formatter)

### Science :mortar_board:

  > A new step should be added to the modification cycle: modifying the program to make it readable.

  [Elshoff & Marcotty, 1982](http://dl.acm.org/citation.cfm?id=358596)
