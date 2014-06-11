Transcrypt Sublime Text 3 Package
=============================
Encrypt and decrypt a document or selection(s) using PyCrypto using AES.

Install
-------
### Package Control
- See [here](http://wbond.net/sublime_packages/package_control) for instructions on installation of Package Control
- In Sublime Text, search for package 'Transcrypt'

### Manual
Clone this repository into `Sublime Text 3/Packages` using OS-appropriate location:

OSX:

    git clone git://github.com/eddiejessup/SublimeText-Transcrypt.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/Transcrypt

Windows:

    git clone git://github.com/eddiejessup/SublimeText-Transcrypt.git "%APPDATA%\Sublime Text 3\Packages\Transcrypt"

Usage
-----
Access `Encrypt` and `Decrypt` via:

- Right-click menu item `Transcrypt`
- Menu item `Tools -> Transcrypt`
- Default keyboard shortcuts:
  - Encrypt: `⌘+K, e` (OSX) or `ctrl+K, e` (Linux and Windows)
  - Decrypt: `⌘+K, d` (OSX) or `ctrl+K, d` (Linux and Windows)

The commands work on a selection, multiple selections or if nothing is selected, the whole document. Once you trigger the command you will be prompted to enter a password.

Requirements
------------
Due to containing C extension modules pre-compiled for Python 3.3, only Sublime Text 3 is supported.

About
----
Based on [Crypto](https://github.com/mediaupstream/SublimeText-Crypto) by [Derek Anderson](https://github.com/mediaupstream) and [Richard Mitchell's fork](https://github.com/mitchellrj/pycrypto) of [PyCrypto](https://github.com/dlitz/pycrypto).

Identical interface to Crypto, but supporting much larger text selections by avoiding the subprocess interface.

Author & Contributors
----------------------
- [Elliot Marsden](https://github.com/eddiejessup)
- [Derek Anderson](http://twitter.com/derekanderson)
- [Isaac Muse](https://github.com/facelessuser)
- [Richard Mitchell](https://github.com/mitchellrj)
- [Dwayne Litzenberger](https://github.com/dlitz)

License
-------
MIT License