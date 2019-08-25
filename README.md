# roblox-dark-themes
Dark themes for Roblox with several other changes

# Themes
[Click here to install Dark Theme for developer.roblox.com](https://raw.githubusercontent.com/NovusTheory/roblox-dark-themes/master/developer-roblox-dark.user.css)

# Code Block Theme
The code block theme on Roblox only remembers your decision to be dark theme for the current session. If you'd like it to remember your theme you can set the cookie to an outrageously long time. Here is the code snippet to do that. You may run this in the Inspect Element (Ctrl + Shift + I) console on `developer.roblox.com`.
```javascript
document.cookie = "theme=light-theme%20dark-theme; max-age=" + (86400 * 365) * 9999 + "; path=/;";
```
