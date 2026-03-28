# Privacy Policy — Philately

_Last updated: 2025_

Philately is a browser extension that captures parts of webpages as postage stamps. This policy describes what data the extension handles and how.

## Data Collected

Philately collects no personal data. The only information stored is:

- **Stamps you create** — PNG images of page regions you explicitly capture, saved to `chrome.storage.local` on your own device.
- **Stamp frame size** — your last scroll-adjusted stamp size, stored locally so the next capture starts at the same size.

## Data Sharing

None. No data is sent to any server, third party, or remote service. The extension makes no network requests of any kind beyond loading Google Fonts in the popup UI.

## Page Content

The extension reads the visible area of a tab **only at the exact moment you click to capture**, using the browser's built-in `chrome.tabs.captureVisibleTab` API. This screenshot is processed entirely in-memory, converted to a stamp PNG, and stored locally. It is never uploaded anywhere.

## Storage

All stamps are stored in `chrome.storage.local`, which is sandboxed to your browser profile and never synced to the cloud unless you have Chrome Sync enabled for extension storage (which Philately does not request).

## Permissions

Every permission the extension requests is used solely to deliver the stamp-capture feature. See the store listing for a full per-permission explanation.

## Contact

Questions? Open an issue at the extension's GitHub repository or contact the developer via the Chrome Web Store listing page.