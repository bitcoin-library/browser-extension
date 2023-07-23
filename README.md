# Bitcoin-Library Browser WebExtension

WebExtension to send page data to the [bitcoin library metadata editor](https://github.com/bitcoin-library/metadata-editor).

## Instructions for installing

```
$ git clone https://github.com/bitcoin-library/browser-extension.git
$ cd skohub-extension
$ npm install
```

### Add to Chrome

- The extension still has to be added to the Chrome Store
- For now: You can load the unpacked extension from the repo: In `Extensions`, enable Developer mode, click `load unpacked` and open the directory `skohub-extension/src`.

### Add to Firefox

- The extension still has to be added to the Firefox Add-ons Store
- For now: Go to `Add-ons` in `Tools for Add-ons` click `Debug Add-ons` and load a new temporary add-on selecting the manifest in `bitcoin-library-browser-extension/src`. You can also directly launch Firefox with a temporary profile by running `npm run start:firefox`

## Usage

After installing the extension click the new extension icon on any webpage, this will open a new tab to SkoHub Editor with the extracted content of the page.

## Credits

Based on the [SkoHub Browser Extension](https://github.com/skohub-io/skohub-extension)
