# KeyCheck

See which keys your browser detects on a physical keyboard. KeyCheck shows your current key, recent presses, and progress across the displayed layout.

[Open KeyCheck on GitHub Pages](https://cryaothicc.github.io/KeyCheck/)

## Run locally

Open `index.html` in a desktop or laptop browser and press a key. No install or build step is needed. The page uses Sora from Google Fonts with a system fallback.

## Read the results

- **Yellow** means the key is currently held down.
- **Mint green** means the browser detected the key during this test.
- The key readout shows the physical `KeyboardEvent.code` and legacy `keyCode`.
- Select **Start over** to clear the history and progress.

The diagram follows a standard US physical layout, so its labels may differ from your keyboard. The browser may miss hardware keys such as **Fn** and shortcuts the operating system intercepts. A key that stays unmarked may still work elsewhere.
