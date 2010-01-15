TextMate Closure Compiler Bundle
================================

TextMate Closure Compiler Bundle allows you to quickly compile a JavaScript file with a specified key shortcut. Compiled files are saved as `original_filename.compiled.js`

Setting up
----------

1. Go to **Bundle Editor**, find **Closure Compiler**, and add your user in place of **USERNAME**, in the **Settings** preference.
2. Download the latest version of [compiler.jar](http://code.google.com/closure/compiler/docs/gettingstarted_app.html), and put it in the previously specified directory (ie. `/Users/USERNAME/compiler.jar`)

Usage
-----

Select a bunch of files from TextMate's Drawer and hit `Ctrl + Shift + G` - all selected files will be compiled and saved as `original_filename.compiled.js` in the same directory.