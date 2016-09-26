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

brew install tmux

# install java
brew tap caskroom/cask
brew cask install java
java -version

# install leiningen
brew install leiningen

# install intelli-j community edition
brew tap caskroom/versions
brew cask install intellij-idea-ce

# we use citrix to use machines at home so...
brew cask install citrix-receiver

brew cask install little-snitch

brew cask install google-chrome

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
