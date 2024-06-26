# JWM themes

A few simple themes for [Joe's Window
Manager](https://joewing.net/projects/jwm/)!

Not that I daily drive these, just having a bit of fun. But I do run them on an
old laptop 🙂

## Themes

### Win95-esque

Inspired by my youth. Needs no further introduction.

[![The Win95-esque theme](./screenshots/win95-esque.png)](./screenshots/win95-esque.png)

## Mac-O-ish

Sort-of-kinda looks a bit like an older MacOS, maybe? 😄

[![The Mac-O-ish theme](./screenshots/mac-o-ish.png)](./screenshots/mac-o-ish.png)

### Slick

A very minimal theme that I came up with, which maximizes screen real estate for
your actual applications and just tries not to distract.

[![The Slick theme](./screenshots/slick.png)](./screenshots/slick.png)

## Installation

These themes assume you're running JWM (obviously) and have
[`xdgmenumaker`](https://github.com/gapan/xdgmenumaker) installed to put all
your applications in the menu. Some package managers have it. Otherwise it's
just a `git clone` / `make` / `make install` away. The "Run" menu item uses
`xfce4-appfinder`, which you may or may not have. Replace with your own
graphical application runner of choice.

Then:

```bash
cd ~
git clone https://github.com/Timendus/jwm-themes.git
```

And then either modify your own `~/.jwmrc` file to hold the contents of
`~/jwm-themes/.jwmrc`, or just copy over my version:

```bash
cp ~/jwm-themes/.jwmrc ~/
```

If you clone this repo somewhere other than your home directory, do a
find/replace through this repository for `$HOME/jwm-themes` and make sure you
fix all the paths.

## Notes

These themes are clearly not **super** close to the original. JWM is quite
constrained in what it can do. This is (no doubt) by design to keep things fast
and memory efficient. For example; I did not manage to get the "MacOS dock" to
properly center on the screen, because the TaskList automatically takes up all
horizontal space. The "Windows taskbar" needs to have different margins, that I
couldn't fix. I think this is a fine compromise for JWM, and for me constraints
fuel creativity.

Also, and this I did find slightly disappointing; JWM doesn't have a "background
cover" setting. It's either stretched without regards for the aspect ratio or
contained ("scaled"). I chose the latter. You may not like this if your display
is not 16:9. Find your own background in that case, and don't file an issue on
this repo 😉

## Hey Joe!

If you read this, just wanted to let you know that I really enjoyed your TI-83
shell Ion when I was in highschool around 2002 😄 It was miles ahead of the
other shells, and I learned a ton from reading its source code. I'm happy to
have recently discovered your super resource-effective window manager, to bring
back life to my older machines. Thanks!
