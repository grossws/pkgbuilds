# Arch Linux AUR packages aggregator repo

## Info

This repo aggregates AUR package repos managed by me (Konstantin Gribov).

I use shortcuts for remotes in `~/.ssh/config`:

```
host aur
     hostname aur.archlinux.org
     user aur
```
 
You can add this snippet to your `~/.ssh/config`, clone this repo
and invoke `git submodule update --init` to fetch current state into submodules.

Then `cd` into subdir and call `makepkg -s` to build it.

## License

Licensed under MIT License. See [LICENSE file](LICENSE)

