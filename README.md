# dygma-raise-layers

My personal dygma raise layer setup with a focus on keyboard OS consistency, ambidextrous programming, and light terminal work.

## Layers

### Typing

[Windows/Linux Typing](configs/windows-linux-typing.json) and [Macos Typing](configs/macos-typing.json)

- `Escape` replaces `Backspace` via top-right corner
- `Tab` and `\|` keys have dual-function `Ctrl` `Modifier` keys (ambidextrous)
- `Layer` [Windows/Linux / Macos typing](#typing) keyboard swap key replaces `Enter` key
- Left-side `Alt` and right-side `Function` keys are dual function `Home`/`End` superkeys (ambidextrous)
- `Arrow` keys replace right-side `Modifier` keys
- Thumb clusters have `Space`, `Backspace`, `Delete`, and `Enter` keys (ambidextrous)
- `Enter` thumb cluster keys are dual function `Layer` [Shortcut keys](#shortcuts) (ambidextrous)

![Windows/Linux Typing](img/windows-linux-typing.png)

![Macos Typing](img/macos-typing.png)

### Shortcuts

[Windows/Linux Shortcuts](configs/windows-linux-shortcuts.json) and [Macos Shortcuts](configs/macos-shortcuts.json)

- number row - media shortcuts
- upper row - Chrome/browser shortcuts (ambidextrous)
- middle row - VSCode/IDE shortcuts (ambidextrous)
- middle row `Layer` keys enter into [Num and F keys](#numpad-and-f-keys) (ambidextrous)
- lower row - Chrome/browser shortcuts - includes Browser Reload superkeys (ambidextrous)

![Windows/Linux Shortcuts](img/windows-linux-shortcuts.png)

![Macos Shortcuts](img/macos-shortcuts.png)

### Numpad and F Keys

[Windows/Linux Num and F Keys](configs/windows-linux-num-f-keys.json) and [Macos Num and F Keys](configs/macos-num-f-keys.json)

- number row - `Function` keys
- left-side typing area - `Numpad` keys
- right-side typing area - `Numpad` keys - optimal for right-side (`Numpad` keys on right, `Arrow` keys on left)
- middle row `Layer` keys enter into [Windows/Linux / Macos Typing](#typing) (ambidextrous)
- left side - `Arrow` keys
- right side - `Modifier` keys

![Windows/Linux Num and F Keys](img/windows-linux-num-f-keys.png)

![Macos Num and F Keys](img/macos-num-f-keys.png)

## Window Snapping

I use the [hammerspoon-shiftit](https://github.com/peterklijn/hammerspoon-shiftit) to enable windows snapping on macos. Code can be found [here](src/init.lua).

## License

MIT
