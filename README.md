# DWM

My personal dwm configuration.

## Wow, did I write all that myself?

Of course not! I used a lot of patches from 
[suckless.org](https://dwm.suckless.org/patches/).

This repo keeps an up to date [config.h](config.h) with all applied patches, and 
the default [config.def.h](config.def.h) without any patches applied. All used 
patches are available in the [patches](patches) direcotry. This way, it is 
really easy to enable or disable certain functionality. Patches in 
[patches/custom](patches/custom) are patches I wrote myself.

## Installation

```sh
git clone git@github.com:reyniersbram/dwm.git
cd dwm
sudo make install
```

For certain parts to work, scripts from my 
[dotfiles](https://github.com/reyniersbram/dotfiles) might be necesarry.

## Syncing with the original dwm branch

Set up the local git configuration to have the official dwm repository as 
a remote called upstream.

```sh
patch -p0 < gitconfig.diff
```

Then just run `git pull` to get the latest changes.
