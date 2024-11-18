# Plug-in Play ReaPack Repository

A template for GitHub-hosted ReaPack repositories with automated
[reapack-index](https://github.com/cfillion/reapack-index)
running from GitHub Actions.

Replace the name of the repository in [index.xml](/index.xml) when using this template.
This will be the name shown in ReaPack.

```xml
<index version="1" name="Name of your repository here">
```

Replace the contents of this file ([README.md](/README.md)).
This will be the text shown when using ReaPack's "About this repository" feature.

reapack-index looks for package files in subfolders.
The folder tree represents the package categories shown in ReaPack.

Each package file is expected to begin with a metadata header.
See [Packaging Documentation](https://github.com/cfillion/reapack-index/wiki/Packaging-Documentation) on reapack-index's wiki.

The URL to import in ReaPack is [https://github.com/Gearoid-O-Broin/plug-inplay/raw/master/index.xml](https://github.com/Gearoid-O-Broin/plug-inplay/raw/master/index.xml).


# Installation
If you have the ReaPack Extension installed, you can add the repository to Reaper with this URL:

```xml
https://github.com/Gearoid-O-Broin/plug-inplay/raw/master/index.xml
```

If you don't have ReaPack installed, you can download plugins individually and place them in your Reaper/Effects directory.

You can also use [ysfx](https://github.com/jpcima/ysfx) or [ReaJS](https://www.reaper.fm/reaplugs/) to run JSFX plugin in another DAW.
