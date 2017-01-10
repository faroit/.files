# Personal dev environment

## General settings

### Homebrew

```
cat homebrew_packages.txt | xargs brew install
cat homebrewcask_packages.txt | xargs brew cask install
```

### Fonts

```
brew tap caskroom/fonts
brew cask install font-fira-sans font-fira-code
```

## Atom

```bash
apm install --packages-file atom_packages.txt
```
  
## Hyper.js

```bash
cp ./.hyper.js ~
```
