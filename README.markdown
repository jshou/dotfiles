# jshou does dotfiles

## install

- `git clone git@github.com:jshou/dotfiles.git ~/.dotfiles`
- `cd ~/.dotfiles`
- `./install.sh`
- `./dependencies.sh`

The install script will symlink the appropriate files in `.dotfiles` to your
home directory. Everything is configured and tweaked within `~/.dotfiles`,
though.

`dependencies.sh` will install libs and utils that I like. It expects
`install.sh` to have been run already.

## shiftit hammerspoon
also do [this](https://github.com/peterklijn/hammerspoon-shiftit)

## thanks

I forked [Zach Holman](http://github.com/holman)'s excellent
[dotfiles](http://github.com/holman/dotfiles) but eventually modified it to fit
my own needs.
