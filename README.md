# wl-random-wallpaper
Wrapper script for swww. Changes wallpapers on all monitors after a specified interval.  
Requires `python3`(any version probably), `swww`, `wlr-randr`!  
Tested on `sway` and `Hyprland`.

## Configuration
Edit `wl-random-wallpaper` and change the variables at the top of the file.

## Usage
Ensure all dependencies are installed.  
### sway
Add something like `exec "/home/user/.local/bin/wl-random-wallpaper"` to your sway config.  

### Hyprland
Add something like `exec-once = /home/user/.local/bin/wl-random-wallpaper` to your hyprland config.
## License
Licensed under the MIT License.
