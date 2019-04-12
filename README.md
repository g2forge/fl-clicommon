# Forklift CLI Common

[Forklift](https://github.com/g2forge/fl-clicommon) pallet to install commonly used command line tools and an example of a self-installing repo built using forklift.

# Installation

```
bash <(curl -L https://raw.githubusercontent.com/g2forge/forklift/master/install) import com.github g2forge/fl-clicommon master
```

# Packages

* tmux
* dos2unix
* nano
* curl
* git
* make
* psmisc
* bc
* jq
* rsync
* unzip
* wget

# Maintenance

The forklift [post-import](forklift/post-import) script installs the packages using forklift's ability to install OS packages.
It reads the list of packages to install from the [Packages](#packages) section of this file, so if you wish to change the set of installed packages you need simply change that list.
