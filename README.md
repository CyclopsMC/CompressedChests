## Compressed Chests

[![Build Status](https://travis-ci.org/CyclopsMC/CompressedChests.svg?branch=master-1.12)](https://travis-ci.org/CyclopsMC/CompressedChests)
[![Download](https://img.shields.io/maven-metadata/v/http/cyclopsmc.jfrog.io/cyclopsmc/libs-release/org/cyclops/compressedchests/Compressed Chests/maven-metadata.xml.svg) ](https://oss.jfrog.org/artifactory/simple/libs-release/org/cyclops/compressedchests/Compressed Chests/)
[![CurseForge](http://cf.way2muchnoise.eu/full_291143_downloads.svg)](http://minecraft.curseforge.com/projects/291143)

Compress chests for increased slot space

All stable releases (including deobfuscated builds) can be found on [CurseForge](http://minecraft.curseforge.com/mc-mods/291143/files).

[Development builds](https://oss.jfrog.org/artifactory/simple/libs-release/org/cyclops/compressedchests/Compressed Chests/) are hosted by [JFrog Artifactory](https://www.jfrog.com/artifactory/).

### Contributing
* Before submitting a pull request containing a new feature, please discuss this first with one of the lead developers.
* When fixing an accepted bug, make sure to declare this in the issue so that no duplicate fixes exist.
* All code must comply to our coding conventions, be clean and must be well documented.

### Issues
* All bug reports and other issues are appreciated. If the issue is a crash, please include the FULL Forge log.
* Before submission, first check for duplicates, including already closed issues since those can then be re-opened.

### Branching Strategy

For every major Minecraft version, two branches exist:

* `master-{mc_version}`: Latest (potentially unstable) development.
* `release-{mc_version}`: Latest stable release for that Minecraft version. This is also tagged with all mod releases.

### Building and setting up a development environment

This mod uses [Project Lombok](http://projectlombok.org/) -- an annotation processor that allows us you to generate constructors, getters and setters using annotations -- to speed up recurring tasks and keep part of our codebase clean at the same time. Because of this it is advised that you install a plugin for your IDE that supports Project Lombok. Should you encounter any weird errors concerning missing getter or setter methods, it's probably because your code has not been processed by Project Lombok's processor. A list of Project Lombok plugins can be found [here](http://projectlombok.org/download.html).

### License
All code and images are licenced under the [MIT License](https://github.com/CyclopsMC/CompressedChests/blob/master-1.12/LICENSE.txt)
