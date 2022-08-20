# legacy-web3-extension

An extension that adds MetaMask's legacy `window.web3` API to your browser.

## Usage

1. `yarn install`
2. `yarn build`
3. Load the unpacked extension from `dist/unpacked/YOUR_FAVORITE_BROWSER`
4. Test with any build of the MetaMask Extension, version [9.0.1]() and later

### Dependencies

The extension's content script contains the [minified source](https://unpkg.com/@metamask/legacy-web3@2.0.0/dist/metamask.web3.min.js) of this dependency as a string literal in order to inject it into web pages as a `<script>` tag.

The complete, unminified source can be viewed [here](https://unpkg.com/@metamask/legacy-web3@2.0.0/dist/metamask.web3.js).

## Supported Browsers

- Brave
- Chrome
- Edge
- Firefox
