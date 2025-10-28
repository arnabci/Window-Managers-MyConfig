# Window-Managers-MyConfigs
My personal configs for all Window Managers I used.

# Sway
Config file is a copy of /etc/sway/config.  
You can also paste it in the /home/username/.config/sway/config and it should work.  
But I like to fly high speed low drag lmao.  
Put the catppuccin-mocha.ini into ~/.config/foot/

# Hyprland
Config files in Hyprland are a little complicated.  
It is a modified version of,  
<url>https://github.com/HyDE-Project/HyDE</url> &  
<url>https://github.com/end-4/dots-hyprland</url>  
Download the respective folders from my github files into /home/username/.config/hypr/ and /home/username/.config/waybar/

# Fun things you need to do to make this work

xrandr --output "DP-1" --primary (Wayland equivalent for creating a primary display.  
This helps games like dota not take weird resolutions when running.)

# Make SSH keys work on Kitty

eval (ssh-agent -c)  
ssh-add ~/.ssh/bucket

# Office setup

#monitor = DP-4, 1920x1080@60, 0x0, 1  
#monitor = DP-3, 1920x1080@60, 1920x0, 1
