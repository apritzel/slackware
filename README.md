# Slackware build scripts - fixes and updates

This repository contains fixes and updates to official Slackware
build scripts used to build the distribution.
They cover several topics (in extra branches):

- tar

    Starting with GNU tar 1.27 there is a command line switch to
    enable the old behavior of version 1.13 and before of not
    clobbering symlinks on archive extraction. This branch
    adapts pkgtools to make use of this feature (if available)
    and also updates the tar Slackbuild to the new tar version.
