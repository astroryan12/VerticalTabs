# UserChrome Configs

This configuration changes the sidebar behavior. There are three options.

## Options

### 1. `userChrome-hover`

Takes up the least space, expands when hovered.

![userChrome-hover](https://github.com/astroryan12/FirefoxTstWindows/blob/main/imgs/layout-hover.png)
![userChrome-hover](https://github.com/astroryan12/FirefoxTstWindows/blob/main/imgs/layout-hover1.png)

### 2. `userChrome-overlay`

Permanently expanded, hides page content behind it. Best used with a quick [shortcut to toggle tst](https://support.mozilla.org/en-US/kb/manage-extension-shortcuts-firefox)

![userChrome-overlay](https://github.com/astroryan12/FirefoxTstWindows/blob/main/imgs/layout-overlay.png)

### 3. `userChrome-static`

Permanently expanded, does not hide page content behind it. Resizes webpage whenever toggled.

![userChrome-static](https://github.com/astroryan12/FirefoxTstWindows/blob/main/imgs/layout-static.png)

## Installation

1. Based on the above table, chose whichever `userChrome-*.css` you want.

2. Copy the chosen file name (e.g. `userChrome-*.css`), and paste it in the userChrome.css import field. To find your profile directory, go to `about:support`.
