# additionalBrightnessToggle
GNOME Extension to implement additional brightness toggles in the Quick List.
Compatible Device: Asus Zenbook Pro Duo 14 OLED

## Instructions:
  1. The repository uses [brightnessctl](https://github.com/Hummer12007/brightnessctl) and gnome-shell-extenstions libraries. Please ensure that the libraries are installed and functional.
  2. Clone and move the git repo to ``` ~/.local/share/gnome-shell/extensions ```:
     ```
     git clone https://github.com/shashwatSrivastava-official/additionalBrightnessToggle
     mkdir ~/.local/share/gnome-shell/extensions/additional-brightness-control
     mv additionalBrightnessToggle ~/.local/share/gnome-shell/extensions/additional-brightness-control
     cd ~/.local/share/gnome-shell/extensions/additional-brightness-control
     mv additionalBrightnessToggle/* .
     rm additionalBrightnessToggle
     ```
  3. Enable the 
## Scope for Improvements:
  1. Further adding support for multiple screens and making the code block more modular and generalized.
  2. Keymapping for secondary or multiple monitors for shortcut brightness toggling.

## FAQs:
  1. If the brightness toggle doesn't work, check if ``` brightnessctl set ``` does not require superuser access. To fix this run ``` sudo usermod -aG video ${USER} ``` .
  2. To modify and implement the code for different screens, replace 'asus_screenpad' with your device name in the extension.js file. Use ``` brightnessctl -l ``` to get a list of devices.

## Credits:
 - [Jaskaran Singh](https://github.com/jksjaz)
 - [Shashwat Srivastava](https://github.com/shashwatSrivastava-official)
