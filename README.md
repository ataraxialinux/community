# Ataraxia Community Ports
This repository contains packages that have been contributed to the Ataraxia Linux project. They are not maintained by the Ataraxia team and are likely to be orphaned, contain bugs or be out-of-date.
## Building
You will first want to clone this repository, which contains all of the "Pkgfile"s that are necessary to build the packages.

```git clone https://github.com/ataraxialinux/community/ /var/cache/ports/community```

You can then use 'prt-get' to build the binaries and install them to your system.

For more information on using prt-get, see our [wiki page.](https://github.com/ataraxialinux/ataraxia/wiki/Package-management)
## Contributing
If you want to contribute a package or submit a bug-fix, simply send a pull request. You must name yourself as the maintainer. If you notice that a package is not maintained, create an issue marking the package as an orphan and asking for a new maintainer. If you notice the package is malicious, create a pull request and label the package for urgent removal.  
