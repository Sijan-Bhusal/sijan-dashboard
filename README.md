## 💻 Preview

This start page is based on the [dawn](https://github.com/b-coimbra/dawn) repository and incorporates additional features for improved usability.

**Essential:** Please ensure you have [userconfig.js](userconfig.js) present and properly set up for the start page to function correctly.

## ⌨️ Keybindings

| Hotkey                                                                 | Action                    |
| ---------------------------------------------------------------------- | ------------------------- |
| <kbd>Numrow</kbd> \| <kbd>MouseWheel</kbd> \| <kbd>Click</kbd>        | Switch tabs               |
| <kbd>s</kbd>                                                          | Search Dialog             |
| <kbd>q</kbd>                                                          | Config Dialog (new)       |
| <kbd>Esc</kbd>                                                        | Close Dialogs             |

The default configuration file is [userconfig.js](userconfig.js), but you can change it in the configuration dialog. For details on configuration, refer to the [original repository](https://github.com/b-coimbra/dawn). Available components include tabs, a clock, and weather.

### Additional Options

- `fastlink`: Set the link for the Pokeball button.
- `localIcons`: Optimize icon loading time; see [Local Icons](#local-icons) for details.

## 🔍 Search Dialog

The search dialog displays a search bar with multiple search engines, configurable in your settings. To use a specific engine, prefix your query with its `!<id>`:

- `!g`: Google
- `!d`: DuckDuckGo
- `!y`: YouTube
- `!r`: Reddit
- `!p`: Pinterest

## Local Icons

To reduce icon loading time, you can [download the icon font](https://github.com/AllJavi/tartarus-startpage/tree/master/src/fonts) and set `"localIcons": true` in your config. This disables remote styles in favor of local assets.

## 🛠️ Getting Started

1. Clone the repository.
2. Make sure [userconfig.js](userconfig.js) exists and is configured for your preferences.
3. (Optional) Download and enable local icons as described above.
4. Open the start page in your browser.

## 🙏 Credit

- [dawn](https://github.com/b-coimbra/dawn)
- [alljavi/tartarus-startpage](https://github.com/AllJavi/tartarus-startpage)

