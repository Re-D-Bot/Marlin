# Re-D-Bot
This is configured firmware for Re-D-Bot 3D Printer.

# Marlin 3D Printer Firmware
<img align="right" src="../../raw/1.1.x/buildroot/share/pixmaps/logo/marlin-250.png" />

## Marlin 1.1.0

Marlin 1.1 represents an evolutionary leap over Marlin 1.0.2. It is the result of over two years of effort by several volunteers around the world who have paid meticulous and sometimes obsessive attention to every detail. For this release we focused on code quality, performance, stability, and overall user experience. Several new features have also been added, many of which require no extra hardware.

For complete Marlin documentation click over to the [Marlin Homepage <marlinfw.org>](http://marlinfw.org/), where you will find in-depth articles, how-to videos, and tutorials on every aspect of Marlin, as the site develops. For release notes, see the [Releases](/MarlinFirmware/Marlin/releases) page.

## Stable Release Branch

This Release branch contains the latest tagged version of Marlin (currently 1.1.0 – May 2017).

Previous releases of Marlin include [1.0.2-2](/MarlinFirmware/Marlin/tree/1.0.2-2) (December 2016) and [1.0.1](/MarlinFirmware/Marlin/tree/1.0.1) (December 2014). Any version of Marlin prior to 1.0.1 (when we started tagging versions) can be collectively referred to as Marlin 1.0.0.

## Contributing to Marlin

Click on the [Issue Queue](/MarlinFirmware/Marlin/issues) and [Pull Requests](/MarlinFirmware/Marlin/pulls) links above at any time to see what we're currently working on.

To submit patches and new features for Marlin 1.1 check out the [bugfix-1.1.x](/MarlinFirmware/Marlin/tree/bugfix-1.1.x) branch, add your commits, and submit a Pull Request back to the `bugfix-1.1.x` branch. Periodically that branch will form the basis for the next minor release.

Note that our "bugfix" branch will always contain the latest patches to the current release version. These patches may not be widely tested. As always, when using "nightly" builds of Marlin, proceed with full caution.

## Current Status: In Development

Marlin development has reached an important milestone with its first stable release in over 2 years. During this period we focused on cleaning up the code and making it more modern, consistent, readable, and sensible.

## Future Development

Marlin 1.1 is the last "flat" version of Marlin!

Arduino IDE now has support for folder hierarchies, so Marlin 1.2 will have a [hierarchical file structure](/MarlinFirmware/Marlin/tree/breakup-marlin-idea). Marlin's newly reorganized code will be easier to work with and form a stronger starting-point as we get into [32-bit CPU support](/MarlinFirmware/Marlin/tree/32-Bit-RCBugFix-new) and the Hardware Access Layer (HAL).

[![Coverity Scan Build Status](https://scan.coverity.com/projects/2224/badge.svg)](https://scan.coverity.com/projects/2224)
[![Travis Build Status](https://travis-ci.org/MarlinFirmware/Marlin.svg)](https://travis-ci.org/MarlinFirmware/Marlin)

## Marlin Resources

- [Marlin Home Page](http://marlinfw.org/) - The Marlin Documentation Project. Join us!
- [RepRap.org Wiki Page](http://reprap.org/wiki/Marlin) - An overview of Marlin and its role in RepRap.
- [Marlin Firmware Forum](http://forums.reprap.org/list.php?415) - Find help with configuration, get up and running.
- [@MarlinFirmware](https://twitter.com/MarlinFirmware) on Twitter - Follow for news, release alerts, and tips & tricks. (Maintained by [@thinkyhead](/thinkyhead).)

## Credits

The current Marlin dev team consists of:
 - Roxanne Neufeld [@Roxy-3D] - English
 - Scott Lahteine [@thinkyhead] - English
 - Bob Kuhn [@Bob-the-Kuhn] - English
 - Andreas Hardtung [@AnHardt] - Deutsch, English
 - Nico Tonnhofer [@Wurstnase] - Deutsch, English
 - Jochen Groppe [@CONSULitAS] - Deutsch, English
 - João Brazio [@jbrazio] - Portuguese, English
 - Bo Hermannsen [@boelle] - Danish, English
 - Bob Cousins [@bobc] - English
 - [@maverikou]
 - Chris Palmer [@nophead]
 - [@paclema]
 - Erik van der Zalm [@ErikZalm]
 - David Braam [@daid]
 - Bernhard Kubicek [@bkubicek]

More features have been added by:
 - Alberto Cotronei [@MagoKimbra] - English, Italian
 - Thomas Moore [@tcm0116]
 - Ernesto Martinez [@emartinez167]
 - Petr Zahradnik [@clexpert]
 - Kai [@Kaibob2]
 - Edward Patel [@epatel]
 - F. Malpartida [@fmalpartida] - English, Spanish
 - [@esenapaj] - English, Japanese
 - [@benlye]
 - [@Tannoo]
 - [@teemuatlut]
 - [@bgort]
 - [@LVD-AC]
 - [@paulusjacobus]
 - ...and many others

## License

Marlin is published under the [GPL license](/COPYING.md) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
