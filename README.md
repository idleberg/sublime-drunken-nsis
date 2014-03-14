# Drunken NSIS for Sublime Text

## Description

This might or might not be a good idea to improve your NSIS skills. Using this package, you will likely never memorize the correct syntax. But then again, using this you don't have to anymore. This package irons some of the inconsistencies of the NSIS language, allowing command aliases to be completed into valid syntax. Furthermore, valid syntax completions are included as well.

## Installation

### Package Control

1. Make sure you already have [Package Control](https://sublime.wbond.net/installation) installed
2. Choose *Install Package* from the Command Palette (`Ctrl+Shift+P` on Windows/Linux, `⇧⌘P` on OS X)
3. Select *Drunken NSIS* and press `Enter`

With [auto_upgrade](http://wbond.net/sublime_packages/package_control/settings/) enabled, Package Control will keep all installed packages up-to-date!

### GitHub ###

1. Change to your Sublime Text `Packages/User` directory
2. Clone repository `git clone https://github.com/idleberg/Drunken-NSIS.git`

### Manual Installation ###

1. Download the files using the GitHub [.zip](https://github.com/idleberg/Drunken-NSIS/archive/master.zip) download option
2. Unzip the files to your Sublime Text `Packages/User` directory

## Aliases

All invalid syntax is prefixed with a `§` symbol. Press `Tab` to auto-complete to valid syntax.

### Word Order

The order of noun and verb is reversible, you can use combos such as `FileRead`/`ReadFile` or `SectionSetText`/`SetSectionText`. Use `Tab` key to jump between fields.

### Prince Versions

Named after the Prince Emulator in Douglas Coupland's [Microserfs](http://www.wired.com/wired/archive/2.01/microserfs.html), these versions make no difference between `BringToFront`/`Bring2Front` or `Goto`/`Go2`. Again, make use of the `Tab` key to jump between fields.

## License

The MIT License (MIT)

Copyright (c) 2014 Jan T. Sott

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.