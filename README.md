Sublime Syntax Coloring for AC Algorithm
========================================

This short plugin is intended to color syntax of AC Algorithm, a language made
by [Antoine CRÔNIER](https://github.com/antoinecronier) for french algorithm
learners.

How to compile
--------------

Install [Sublime Text](https://www.sublimetext.com/3) and
[Package Control](https://packagecontrol.io/installation) (only if
`CTRL/⌘ + SHIFT + P` and a search for `install` doesn't show
`Package Control: Install Package`).

Then install [PackageDev](https://github.com/SublimeText/PackageDev) (see README
on the repo for further informations about this package).

Before compiling, clone or download this repo somewhere on your disk.

Then, open the `JSON-tmLanguage` file with Sublime and press `CTRL/⌘ + B`. If
everything goes well, you will have a `tmLanguage` file poping in the
same folder as the `JSON-tmLanguage`.

How to install
--------------

Click on the `Preferences > Browse Packages` menu entry and go to `User` folder.
Copy and paste the resulting `tmLanguage` file from the previous step.

How to use
----------

Every file with `.algo` extension will be opened with the right syntax. You can
also setup the syntax via the command palette or the down right corner of your
current window.

VSCode compatibility
--------------------

Since VSCode use the same language definition, this repo is compatible. See 
[vscode-tmlanguage][https://github.com/Togusa09/vscode-tmlanguage] repo for
further details.

How to contribute
-----------------

Feel free to fork and make a request from your repository.

Language conventions
--------------------

Convention for variables names (lower camel case with optionnal number ending) :

	`[a-z]+([A-Z]{1}[a-z]*)*(\d+)*`

Convention for constants names (uppercase with underscores between words) :

	`[A-Z]+(_[A-Z]+)*`

Convention for function and class names (upper camel case) :

	`([A-Z]{1}[a-z]+)+`
