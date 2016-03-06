# Sublime Gnuplot

This package aims to provide a support for creating nice figures with gnuplot in Sublime-Text. So far, various features have been implemented, including:
* Syntax highlighting
* Script execution -- pressing `cmd+b` on Mac OS X, `ctrl+b` on Linux/Windows
* Toggle Comments -- pressing  `cmd+/` on Mac OS X, `ctrl+/` on Linux/Windows [Leandro Heck](https://github.com/leoheck)
* Jump to the location of an error, should one occur when running gnuplot [AJMansfield](https://github.com/AJMansfield)
* Autocomplition for set [joebarker87](https://github.com/joebarker87)

# Installation

Sublime Gnuplot can be installed via [Package Controll](https://sublime.wbond.net/installation) or from source. I recommend that you use Package Control! Not only does it ease installation, but more importantly it automatically updates the plugins it installs, which ensures you will get the latest features and bug fixes.

## Installing via Package Control

To install Sublime Gnuplot via [Package Controll](https://sublime.wbond.net/installation), follow these steps:

1. Open the Command Palette (`cmd+shift+p` on Mac OS X, `ctrl+shift+p` on Linux/Windows).
2. Type `install`  and select `Package Control: Install Package` from the Command Palette. There will be a pause of a few seconds while Package Control finds the available packages.
3. When the list of available packages appears, type `gnuplot` and select `Gnuplot`.
4. After a few seconds Sublime Gnuplot will be installed and loaded. 

## Installing from source

I very strongly discourage you from installing from source. There is no advantage to installing from source vs. using Package Control. In fact, there are several disadvantages, including no automatic updates, no update messages, etc.

If you insist on installing from source, please do not do so unless you are comfortable with the command line and know what you are doing. To install Sublime Gnuplot from source, do the following:

1. Quit Sublime Text.
2. If you have a previous source installation at `Packages/Gnuplot`, delete it.
3. Type in a terminal: 
```
	cd '/path/to/Sublime Text 3/Packages'
	git clone https://github.com/hesstobi/sublime_gnuplot.git Gnuplot
```
4. Restart Sublime Text 3.



