# Nightcord Mini

Changes the Discord logo in the top left and the default color.
- Pick from any Project Sekai unit logo or the Nightcord one
    - You can add your own icon as well if you know how
- Change Discord's Blurple to be whatever color you want, all of the character's colors are provided 
- Both are optional and can be turned off in settings

## Examples
<p align="center">
<img height=187 src="https://raw.githubusercontent.com/dabluee/discord-themes/refs/heads/main/prsk/assets/logoexample.png">
</p>

## How to Edit
1. Open the .css file in any text editor (Notepad for example).
2. Scroll down to the section shown below (should be right above the giant block of space).
    <img width=500 src="https://raw.githubusercontent.com/dabluee/discord-themes/refs/heads/main/prsk/assets/nightcordoptions.png">
3. Pick whichever options you would like.
    - Change `--recolor: on;` to `--recolor: off;` if you want Discord's Blurple back.
    - Change `--custom-color: var(--mafuyu);` to `--custom-color: var(--an);` if you want a different color for example.
    - The custom logo works the same as recoloring as shown above.
    - If you just want the DMs button color to be different, change recolor-logo-only to be on.
    - It can be annoying to change between options for recolor-max, so it is not necessary. Some examples on how good to how off colors can look with this option are shown below.

        <img width=500 src="https://raw.githubusercontent.com/dabluee/discord-themes/refs/heads/main/prsk/assets/blurpleexample.png">

## Installation

1. Download the theme file [nightcordmini.theme.css](https://raw.githubusercontent.com/dabluee/discord-themes/refs/heads/main/prsk/nightcordmini.theme.css) (Right click > Save as...).
2. Download [BetterDiscord](https://betterdiscord.app/), [Vencord](https://vencord.dev/), or any other option that allows you to change Discord's css.
3. Drag the file into your theme folder for whichever client you are using.
    - `Discord Settings > Themes > Open Themes Folder`
    - Windows folder: `%appdata%/BetterDiscord/themes` or `%appdata%/Vencord/themes`