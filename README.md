# My dotfiles for AwesomeWM on Arch
![awesome1](https://fuji.s-ul.eu/bpLr62e0)
> i fixed the dual cpu & ram on polybar ignore that lmao

## Introduction
This is my first time setting up a WM without using a preconfigured rice, lol. \
Things are bound to be written poorly or broken but oh well. 

I may end up adding or fixing stuff for a while until life catches up with me again.

## Packages
``` yay -S picom rofi polybar fastfetch feh xfce4-screenshooter rofi-power-menu ``` 

probably some other stuff i forgot but i'll fix it when / if i remember

## Fonts
- Get the Fonts [here](https://www.jetbrains.com/lp/mono/) & [here](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/JetBrainsMono.zip) 
- Move files to ``` ~/.local/share/fonts ```, create if doesn't exist

- Run ```fc-cache -f -v ``` 

- Done

##Battery indicator
Simply replace line 56 in ~/.config/polybar/config.ini with ```modules-right = battery xkeyboard memory cpu eth ``` \
Reload awesome with ```ctrl+mod+r``` \
Done!

## Credit

### Fastfetch
- https://github.com/LierB/fastfetch -- ty!!

Some stuff contains things from other repos & people. \
I can't remember all the sources for stuff, but I will add them as I rediscover them.
