# Mac Setup for Development

## Docker

Manual installation of docker from: https://www.docker.com/products/docker-toolbox

## Brew

This is dependent on command line tools being available from xcode.

Brew installed from here:

http://brew.sh/

The script to run is:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

_and then..._

```
# install git
brew install git

# install java
brew tap caskroom/cask
brew cask install java
java -version

# install leiningen
brew install leiningen




```
