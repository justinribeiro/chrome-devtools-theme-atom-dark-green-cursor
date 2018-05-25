# Devtools Theme: Atom Dark with Green Cursor
An experimental Chrome DevTools theme with a blinking green cursor because reasons.

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/nimelepbpejjlbmoobocpfnjhihnpked.svg)](https://chrome.google.com/webstore/detail/devtools-theme-atom-dark/iocojmginfolhoaalkgabkmilfepnejc?hl=en-US)

![screenshot-1280x800](https://user-images.githubusercontent.com/643503/40563296-1e51e83a-6019-11e8-8822-b5ebc67584bd.png)

## Before you get started

This extension uses the experimental Developer Tools Experiments within Chrome. You must enable this otherwise your theme won't work.

1. Go to chrome://flags/#enable-devtools-experiments
2. Locate and enable "Enable Developer Tools experiments".
3. Select "Relaunch Now" at the bottom of the page (WARNING: this will restart Chrome).
4. Open DevTools > Settings
5. Select Experiments tab, and check 'Allow custom UI themes'.
6. Select Preferences tab, and select Theme: Dark (this theme stacks well with dark).

## Development

1. Clone this repo: `git clone git@github.com:justinribeiro/chrome-devtools-theme-atom-dark-green-cursor.git`.
2. Install dependencies: `yarn`.
3. To build, run `yarn grunt`.
4. In Chrome, go to `More Tools > Extentions`.
5. Enable `Developer Mode`.
6. Use `Load Unpacked` to point to the `theme-extension` directory where you cloned the repo.
7. Close and re-open DevTools to see changes.
8. If you want to iterate, run `yarn grunt watch`. Make sure to reload DevTools after changes to see updates.

## Acknowledgements

1. The theme is based on the excellent [Maurice Cruz' zero-base-themes](https://github.com/mauricecruz/zero-base-themes) setup.
2. The color scheme is based on the excellent [Marvin R' vscode-theme-dark-atom-dark-green-cursor](https://github.com/therealmarv/vscode-theme-dark-atom-dark-green-cursor)
