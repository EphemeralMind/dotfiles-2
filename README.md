# dotfiles

> Linux config files (beets, cmus, GnuPG, i3, mpv, ranger, sxhkd, X11)

```text
                   dP            dP   .8888b oo dP
                   88            88   88   "    88
             .d888b88 .d8888b. d8888P 88aaa  dP 88 .d8888b. .d8888b.
             88'  `88 88'  `88   88   88     88 88 88ooood8 Y8ooooo.
             88.  .88 88.  .88   88   88     88 88 88.  ...       88
.----------- `88888P8 `88888P'   dP   dP     dP dP `88888P' `88888P' ----------.
|:::::::::::::.......::......::::..:::..:::::..:..::......:::......::::::::::::|
|::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::|
|::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::|
|------------------------------------------------------------------------------|
|    beets | music tagger & library organizer                          beet(1) |
|     cmus | c* music player                                           cmus(1) |
|      git | revision control system                                    git(1) |
|    gnupg | gnu privacy guard suite         gpg2(1), gpg-agent(1), dirmngr(8) |
|       i3 | window manager                                              i3(1) |
| i3blocks | flexible scheduler for i3bar                          i3blocks(1) |
|     inox | chromium browser (inox-patchset)              chromium-browser(1) |
|      mpv | media player                                               mpv(1) |
|   ranger | file manager                                            ranger(1) |
|    sxhkd | simple x hotkey daemon                                   sxhkd(1) |
|      x11 | x window system                        x(7), xinit(1), xserver(1) |
`------------------------------------------------------------------------------'
```

## Quickstart

1. Clone the repository into your home directory:

   `git clone --recursive https://github.com/bardisty/dotfiles ~/dotfiles`

2. `cd` into the repository:

   `cd ~/dotfiles`

3. Use [GNU Stow](https://www.gnu.org/software/stow/) to create and manage
   the required symlinks:

   `stow <directory>` e.g., `stow mpv`
