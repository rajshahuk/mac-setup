# Mac Setup for Development

## Brew

This is dependent on command line tools being available from xcode.

Brew installed from here:

<http://brew.sh/>

The script to run is:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

_and then..._

```
# install git
# brew install git
# no longer needed as it is installed with xcode command line tools

brew install tmux

# install latest version of Java
brew cask install java
java -version

# for older oracle builds go to the Oracle website and download from there
# <https://www.oracle.com/technetwork/java/javase/downloads/index.html>

# install leiningen
brew install leiningen

brew install macvim

brew cask install virtualbox vagrant

brew cask install gimp

brew cask install imageoptim

```

The following things are installed from the app store

   * 1password
   * Keynote
   * Numbers
   * Pages
   * Evernote
   * XCode
   * Magnet
   * Things

The following applications need to be downloaded from the vendor's website:

   * [Dropbox](https://www.dropbox.com)
   * [Little Snitch](https://www.obdev.at/products/littlesnitch/download.html)
   * Intelli J

