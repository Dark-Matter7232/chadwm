# chadwm (Initial look)

<img src="chadwm/assets/col_layout.png">

<img src="chadwm/assets/occ_act_tags.png">
(empty workspaces have their color greyed out)

- NOTE: This is vanilla dwm bar (status2d patch for setting colors) not dwmblocks or polybar. 

# Requirements

- xsetroot package ( status2d uses this to add colors on dwmbar)
- xmenu (for layoutmenu)
- JetbrainsMono Nerd Font (or any nerd font) and Material design icon font

# Setup 

- copy the stuff from fonts folder to your ~/.local/share/fonts ( this is for material design icon font )
- cd into chadwm and sudo make install
- config.h file must be adjusted for your liking!

# Credits 

- Thanks a lot to [eProTaLT83](https://www.reddit.com/user/eProTaLT83) ( he has modified many dwm bar patches like barpadding,statuspadding, systray to work properly with status2d) and as implemented most of my ideas and created patches for them!
- @fitrh helped with [colorful tag patch](https://github.com/fitrh/dwm/issues/1)

# Patches

- barpadding 
- bottomstack
- cfacts
- dragmfact 
- dragcfact (took from bakkeby's build)
- fibonacii
- gaplessgrid
- horizgrid
- layoutmenu 
- movestack 
- vanity gaps
- colorful tags
- statuspadding 
- status2d
- tatami 
- underline tags
- notitle
- cool-autostart
