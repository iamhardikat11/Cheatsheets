<hr>

Homebrew Cheat Sheet 
===============
### Index
* [Commands](#commands)
* [More package commands](#more-package-commands)
* [Brew Cask commands](#brew-cask-commands)
* [Search](#search)
* [Global commands](#global-commands)

<hr>

## Commands
### Install a package
```
brew install my_package
```
### Remove/Uninstall a package
```
brew uninstall my_package
```
### Upgrade a package
```
brew upgrade my_package	
```
### Unlink
```
brew unlink my_package
```
### Link
```
brew link my_package
```
### Change versions
```
brew switch my_package 2.5.0	
```
### See what versions you have
```
brew list --versions git	
```
<hr>

## More Package Commands
### List versions, caveats, etc
```
brew info git
```
### Remove old versions
```
brew cleanup git	
```
### Edit this formula
```
brew edit git	
```
### Print this formula
```
brew cat git	
```
### Open homepage
```
brew home git	
```
### Search for formulas
```
brew search git	
```
<hr>

## Brew Cask Commands

### Install the Firefox browser
```
brew install --cask firefox
```
### List installed applications
```
brew list --cask	
```
<hr>

## Global Commands
### Update brew and cask
```
brew update	
```
### Upgrade all packages
```
brew upgrade	
```
### List installed
```
brew list	
```
### What’s due for upgrades?
```
brew outdated	
```
### Diagnose brew issues
```
brew doctor	
```
