# sh scripts
collection of some shell scripts 

## <li>`lolban`</li>
toilet piped through lolcat.


Usage:
1. Make the script executable by `chmod +x lolban`
2. Put it somewhere in your path so you can call it from anywhere like `/.local/bin`

Requirements: 
1. `toilet`
2. `lolcat`
3. fonts from https://github.com/xero/figlet-fonts

![lolban](https://media.discordapp.net/attachments/907150610703474708/910188151241314314/2021-11-16_20-52.png)
 
Credits: [budlabs](https://www.youtube.com/channel/UCi8XrDg1bK_MJ0goOnbpTMQ)

## <li>`toggle-touchpad.sh` : Toggle your laptop's touchpad on/off </li>
Usage:

a. **From Terminal.**
  1. Navigate to the folder containing the scripts
  2. Make it executable by running `chmod +x` on the script
  3. Execute the script by `./toggle-touchpad.sh`
  4. You may move or symlink it somewhere in your $PATH such that using its full path is unneeded.

b. **Through a keybind.**
  1. Make the script executable
  2. Edit your WM's config and add the keybind.
      -  **i3wm:** `bindsym $mod+Shift+T exec ~/.scripts/toggle-touchpad.sh`

NOTE: It displays a notification when you toggle it.

## <li>`krohnkite-toggle.sh` : Toggle [Krohnkite](https://github.com/esjeon/krohnkite)</li>
Toggle Krohnkite (Dynamic Tiling extension for KWin) through terminal or a shortcut key.
Usage:

a. **You can run the script from the terminal itself.**
  1. Navigate to the folder containing the script
  2. Make the script executable first by `sudo chmod +x krohnkite-toggle.sh`.
  3. Execute the script by `sh krohnkite-toggle.sh`.
```
sudo chmod +x krohnkite-toggle.sh
sh krohnkite-toggle.sh
```
b. **Execute the script via a shortcut-key.**
  1. System Settings > Shortcuts > Custom Shortcuts > Create a new Command/URL Gloabal Shortcut
  2. Assign the Shortcut-Key under the `Trigger` Tab
  3. Add the execute command under the `Action` Tab. In my case: `sh /home/siddharth/.my-sh-scripts/krohnkite-toggle.sh`

## License
[WTFPL](https://github.com/siddharth-03s/scripts/blob/main/LICENSE.txt)

All attempts have been made to identify third party content within the repository, with sources and attribution given where necessary. Please contact me if any issues are discovered.


