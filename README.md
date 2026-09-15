# Liquid Fox, Aure Edition

A Firefox theme for macOS inspired by Golden Gate style.
Based on the miloszfalinski/liquid-fox.

<picture width="50">
  <source media="(prefers-color-scheme: dark)" srcset="./screenshots/dark.png?raw=true">
  <source media="(prefers-color-scheme: light)" srcset="./screenshots/light.png?raw=true">
  <img alt="Screenshot of the Firefox browser with my theme">
</picture>

- Customized just the way I like it
- Big fat borders were removed
- Colours were picked from macOS Golden Gate
- Shadows were added everywhere
- App menu and popups were styled to match native design
- Dark mode adjustments

## Install

### Quick (script)

```bash
./install.sh
```

The script lets you pick a Firefox profile and copies `chrome/userChrome.css` into it.

### Manual

1. Open `about:profiles` in Firefox and find your active profile directory
2. Create a `chrome/` folder inside it (if it doesn't exist)
3. Copy `chrome/userChrome.css` into that folder

### Enable in about:config

Open `about:config` in Firefox and set both of these to `true`:

```
toolkit.legacyUserProfileCustomizations.stylesheets
widget.macos.titlebar-blend-mode.behind-window
```

Then restart Firefox.

## Uninstall

Delete the `chrome/userChrome.css` file from your Firefox profile directory and restart Firefox. You can find your profile directory by visiting `about:profiles`.

## License

[MIT](LICENSE)
