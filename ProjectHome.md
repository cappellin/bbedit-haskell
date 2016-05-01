# BBEdit Codeless Language Module for Haskell #

This module adds support for editing the [Haskell](http://www.haskell.org) computer language within [BBEdit](http://www.barebones.com/products/bbedit/), a commercially available text editor for MacOS X.

## Features ##
These features are implemented:
  * color highlighting of keywords and comment, including nested comments
  * color syntax for characters and strings, including multi-line strings
  * scanning of function names; they appear in a drop-down menu in the editing window
  * automatic detection of .hs suffix
  * support for Un/Comment command available in BBEdit 10.1 and above

## Installing ##
Download the module, which consists of a single file named [Haskell.plist](http://bbedit-haskell.googlecode.com/files/Haskell.plist), and place it in the following folder.
<pre>~/Library/Application Support/BBEdit/Language Modules/</pre>

**Tip**: If you have a hard time locating this folder, open a Finder window, press Command-Shift-G and paste the path above in the text box.

If BBEdit is running, quit and restart. The language pull-down menu at the bottom of the editing window now contains an item `Haskell` which activates the features.  Files ending with `.hs` are also automatically recognized.

The instructions are also included within the file.


---

## Disclaimer ##

The author never had nor has any ties with BareBones Software.  The module is provided "as is" without warranty of any kind.