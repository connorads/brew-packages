# brew-packages

[@connorads](https://github.com/connorads) favourite [Homebrew](https://brew.sh/) packages 🍺

## Download `Brewfile`

```sh
git clone https://github.com/connorads/brew-packages
```

## Create symlink to downloaded `Brewfile` from default `Brewfile` path

```sh
ln -s ~/path/to/repo/brew-packages/Brewfile ~/Brewfile
```

## Install packages from `Brewfile`

```sh
brew bundle install
```

## Update `Brewfile`

```sh
brew bundle dump --force
```
