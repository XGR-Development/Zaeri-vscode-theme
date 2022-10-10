# [Zæri]()
![Zæri](https://raw.githubusercontent.com/XGR-Development/Zaeri-vscode-theme/main/long-icon.png)
<br><br> A simple Visual Studio Code theme written with love & affection.

## Installation

There are 3 ways to do this:

1.  - Install it by using the downloading the files directly from this repository
    - Place it in your extension folder
2.  - Install it from the Visual Studio Code Marketplace Online
3.  - Install it from the editor itself - `CTRL + Shift + X`
    - Search `Zaeri`
    - Download the one whose author is `XGR Development`

## Screenshots
![Zæri first screenshot](https://raw.githubusercontent.com/XGR-Development/Zaeri-vscode-theme/main/static/-first-ss.png)
![Zæri second screenshot](https://raw.githubusercontent.com/XGR-Development/Zaeri-vscode-theme/main/static/-second-ss.png)

## Want to modify something ?

Feel free to modify a bit the theme if you feel so. You just need to go to:  
`../.vscode/extensions/xgr-development-zaeri-?.?.?/themes/Zæri-color-theme`

Then manually search the key you want or use `CTRL + F` & manually modify it or use `CTRL + H`.

*The `.vscode` should be in the `Users/<your user>` folder.*

For those who are not used to vscode theme keys:

- The editor colors are in the first part of the .json file
    - Just modify the hexColor code if you want to
- And for the code color himself, it can be find within the second part of the .json file
    - To change the color, modify the hexColor code in the "fontStyle" key of the "settings"
    - To change the style, modify the fontStyle key of the "settings"

**Tip :** To find the key you need / want to modify, you maybe want to turn on the Tokens and Scopes Editor Inspector by doing :

- `CTRL + Shift + P`
- Type `Developer: Inspect Editor Tokens and Scopes`
- Then click on the word you want the color to be modified and search the key that should be in the `textmate scopes` part or the `foreground` one.