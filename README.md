# mpv9tv.sh
Fullscreen 9 TV channel watching Linux shell script. It's very useful watching 9 tv the same time with opened muted and volume control with mouse scroll.

# Requirements
1. sudo yum install mpv youtube-dl
2. 1920X1080 screen resolution (if not or different, need to calculate --geometry parameters)
3. Add this two-line to "~/.config/mpv/input.conf" for volume control with mouse scrool.  
  MOUSE_BTN3 add volume 2  
  MOUSE_BTN4 add volume -2  
