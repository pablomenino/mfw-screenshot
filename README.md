<h3 align="center">MFW-ScreenShot</h3>
<p align="center">A tool for take screenshots</p>

<p align="center">
<a href="https://github.com/pablomenino/MFW-ScreenShot/releases"><img src="https://img.shields.io/github/release/pablomenino/MFW-ScreenShot.svg"></a>
<a href="./LICENSE"><img src="https://img.shields.io/github/license/pablomenino/MFW-ScreenShot.svg"></a>
</p>

This script works in UNIX-like systems, tested on Fedora 12.

Original intention for use on Gnome 2

## Table of contents

* [How to Use](#how-to-use)

## <a name="how-to-use">How to Use

#### Requirements

To use this script you need to have Perl and ImageMagick installed in your system.

* ImageMagick - OpenMP http://www.imagemagick.org
* Perl

#### How to use

Screen Area

```bash
/PATH-TO-SCRIPT/MFW-ScreenShot.pl --area_screenshot
```

Full ScreenShot

```bash
/PATH-TO-SCRIPT/MFW-ScreenShot.pl --full_screenshot
```

#### Configure destination directory

Change the directory in the script:

```bash
vi /PATH-TO-SCRIPT/MFW-ScreenShot.pl
```

Modify the line:

my $dirto = "Pictures/ScreenShots";

The final directory is on the Home user directory:

```bash
$ENV{HOME} + $dirto
```
