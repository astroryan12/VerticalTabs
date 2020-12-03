# UserChrome Configs

This configuration changes the sidebar behavior. There are three options.

## Options

### 1. `userChrome-hover`

Takes up the least space, expands when hovered.

![userChrome-hover](https://github.com/akshat46/FlyingFox/blob/master/img/userChrome-hover.png)

### 2. `userChrome-overlay`

Permanently expanded, hides page content behind it. Best used with a quick [shortcut to toggle tst](https://support.mozilla.org/en-US/kb/manage-extension-shortcuts-firefox)

![userChrome-overlay](https://github.com/akshat46/FlyingFox/blob/master/img/userChrome-overlay.png)

### 3. `userChrome-static`

Permanently expanded, does not hide page content behind it. Resizes webpage whenever toggled.

![userChrome-static](https://github.com/akshat46/FlyingFox/blob/master/img/userChrome-static.png)

## Installation

1. Based on the above table, chose whichever `userChrome-*.css` you want. Navigate to your Fierfox profile directory and if need be, delete the old chrome folder and paste the new chrome folder into the directory. To find your profile directory, go to `about:support`.

2. In the userChrome.css file in the newly pasted 'chrome' folder, the final line, '@import url(userChrome-hover.css)' denotes 'userChrome-hover.css' as the default layout. If you wish to change this, simply replace the 'hover' portion in that line, to 'overlay', or 'static', depending on which format you prefer. 