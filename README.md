# [vale](https://vale.sh) and [vale-ls](https://github.com/errata-ai/vale-ls) in a snap #

-------------------------------------------------------------------------------

[![vale](https://snapcraft.io/vale/badge.svg)](https://snapcraft.io/vale)

## Installation ##

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/vale)

``` shell
sudo snap install vale
```

For convenience, this snap also bundles the vale-ls Language Server which can be accessed via the vale.vale-ls command.

If you store documents on an external USB drive or similar, ensure you manually connect the removable-media interface after installing the snap:

    snap connect vale:removable-media

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))
