

# Installation #


Whyteboard has a few essential dependencies that must be installed.

  1. [Python](http://python.org/download/) 2.5, 2.6 or 2.7  --
  1. [wxPython](http://www.wxpython.org/download.php) 2.8.9.0 (at minimum) --

the latest versions are always recommended

Please note that the program **does NOT** work on Python 3+

Optional:
  * [ImageMagick](http://www.imagemagick.net) --  (to import/export PDF/PS files)



# Windows #
You can either download the compiled EXE at around 5MB or run the program from source, requiring more disk space initially but won't have to download a 5MB exe to update the program.

## From Source ##
First download the Python exe files, and install them.
Next, grab the wxPython install files. Please note that you must download the correct wxPython version for the Python version you have installed (2.5, 2.6 or 2.7) and whether you are running Windows 32 or 64 bit.

## EXE ##
There is a .zip for both an Installer, and a "stand alone" exe. Download the one you want, extract the files. For the stand alone exe you can extract the files wherever you like; to a USB pen if you so desired.



To import PDF files you will need Imagemagick.
You may also need [GhostScript](http://pages.cs.wisc.edu/~ghost/) alongside ImageMagick.



# Linux #

You most likely have Python installed on your machine. If not, download and install it.
wxPython can be obtained via aptitude on Ubuntu machines -- follow instructions over at the [wxPython Wiki](http://wiki.wxpython.org/InstallingOnUbuntuOrDebian).

Imagemagick can be installed via `sudo apt-get install imagemagick`

You can download the source code directly from the download pages, fetch the latest development code (which may be buggy/fix bugs in releases -- see GettingTheLatestCode) or you can download the .deb package.

You can also download the program via Synaptic/apt by following the instruction [over at Launchpad](https://launchpad.net/~sproaty/+archive/ppa/); this way you'll be notified of any updates by your package manager.