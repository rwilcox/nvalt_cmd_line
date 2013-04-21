Assumptions
==============

That you have [nvalt](https://github.com/ttscoff/nv) set up to save your files in plain text format

It also assumes you're using zsh.

Use of `nvi` REQUIRES the dialog Unix utility. `port install dialog` or see [dialog's homepage](http://invisible-island.net/dialog/dialog.html)

Tools
================

The tools provided in this package fall under two categories.

Exact, for when you know what file you are looking for:

  * `nve` - NVAlt exact file. Shows full path to NVAlt file name you typed. Usage `nve zsh.markdown`
  * `nved` - NVAlt exact file do. Opens the specified file with the specified program. Usage `nved zsh.markdown $EDITOR`

Find:

  * `nvf` - NVAlt list. Lists files whose names match the given parameter. Usage: `nvf zsh`
  * `nvfq` - NVAlt list, with quoted results. Like `nvf` but returns quoted/safe file paths. Useful when you're going to copy/paste a file path into a new command. Usage: `nvfq zsh`

Tools:

  * `nvl` - NVAlt find and Less. Send found files, that match search string, to `less`. Usage: `nvl zsh`
  * `nvi` - NVAlt pick a file interactively (giving you a list of files that match the search string) and open that file with the specified program. Usage `nvi sh $EDITOR`

Why?
===================

When I'm thinking on the command line I want to stay on the command line, even if I need to look something up in NVAlt.


License
===================


LICENSE:

(The MIT License)

Copyright © 2013 Ryan Wilcox

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

