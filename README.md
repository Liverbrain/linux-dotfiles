### Please read
I have taken a hiatus due to college and other personal reasons. I plan to come back in January with new dotfiles and other projects. Thank you so much for your understanding.

# linux-dotfiles
This is where I dump all of my dotfiles, I'll try to keep it as neat as possible!
Below is what my current setup looks like. I cannot promise you that everything will work out of the box!
![alt text lol](https://raw.githubusercontent.com/Liverbrain/linux-dotfiles/master/2020-07-06-111209_1366x768_scrot.png) <br />

### compton
In order to achieve the blur effect in the preview, you'll need a certain fork of compton called compton-tryone-git. Otherwise you won't achieve the level of blur in the screenshot (this took me way too long to find out, so I'm saving you the trouble!)
### dunst
My notification application of choice. My configuration requires CozetteVector font to be installed. If you use Discord, you'll see avatar icons within the notification window.
### i3
i3-gaps is the window manager I use. No dependencies for this, the keybindings are pretty much all the same as the defaults. You'll need compton-tryone for transparency to work. Pressing Ctrl-d opens rofi.
### ncmpcpp
Super configurable media player for the terminal. I took the ncmpcpp album art script from [here](https://github.com/alnj/ncmpcpp-ueberzug) and decided to tweak it to my liking. Finally album art in ncmpcpp that WORKS!
You'll probably have to change the music directory in the config file from /home/smek/music/ to whatever directory your music is in. It should work fine after that.
### polybar
You'll need the CozetteVector and rissole fonts for my polybar config to work. Even then, it most likely won't work out of the box. You'll also need mpd (and probably mpc) for the music controls to work, and the workspace switcher will only work with i3 and i3-gaps as far as I know.
### ranger
Ranger is my file manager of choice. I recently added neat little file icons for mostly aesthetic purposes. It works fine with CozetteVector as the terminal font. The file icon script can be found [here](https://github.com/alexanderjeurissen/ranger_devicons)
### rofi
My rofi configuration should work out of the box as long as you have the CozetteVector font installed. Nice and easy!
### weechat
Still working on the config file for this one. I honestly don't use IRC a lot, so updates for this one will be slow. That might change though!
### zathura
My PDF viewer. You'll need to install the zathura-git package for transparency to work. The muPDF backend is currently broken as far as I know, so you'll need to install zathura-pdf-poppler-git as well in order to obtain PDF support. Pressing the "B" key will bring up the status bar (much like sxiv)


# What I Use
Not like you care though
- My computer is a hand-me-down Dell Latitude E7250 with a loud ass fan
- I use arch btw
- Still using xorg, not cool enough for wayland
- My window manager is i3-gaps
- My fonts are [CozetteVector](https://github.com/slavfox/Cozette) and [rissole](https://addy-dclxvi.github.io/post/bitmap-fonts/)
- My gtk theme is vimix-dark
- My image viewer is [sxiv](https://github.com/muennich/sxiv)
- My photo editor is GIMP
- I create my colorschemes with [pywal](https://github.com/dylanaraps/pywal)
- My PDF reader is [zathura](https://aur.archlinux.org/packages/zathura-git/) (you'll also want [this package](https://aur.archlinux.org/packages/zathura-pdf-poppler-git/) in order to read PDFs)
- My music players are ncmpcpp and [spotify-tui](https://github.com/Rigellute/spotify-tui).
- My taskbar is [polybar](https://github.com/polybar/polybar)
- My menu is made with [rofi](https://github.com/davatorium/rofi)
- My text editor is nano
- My compositor is compton
- [Here are some of the wallpapers I use](https://imgur.com/a/3EoAx65)

# To-Do
Everything checked below will be added/changed in the next update! (none of these are in any real order)
- [ ] Update Zathura config
- [ ] Add weather icons to polybar
- [ ] Make weechat look nicer
- [ ] Make a Firefox CSS theme and upload it here
- [ ] Upload usable newsboat config here
- [ ] Use bitmap Cozette font instead of CozetteVector
- [ ] Make a Firefox start page
- [ ] Configure Claws Mail (because Mutt is unusable)
- [ ] Add brightness controls to polybar
- [ ] Go to college
