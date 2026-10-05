# ToHub-Dark

A clean, minimalist dark theme for Firefox. Deep black backgrounds, rounded UI elements, and subtle gray accents.

## Features

- Deep black backgrounds (`#0d0d0d`) for tab bar, nav bar, and new tab page
- Dark gray accents (`#1c1c1c`) for address bar, active tab, and popups
- Rounded, pill-shaped address bar and buttons
- Subtle gray outline on the active tab
- Slightly lighter bookmarks toolbar for better separation
- Works on Windows, macOS, and Linux
- No data collection, no tracking, no external requests

## Installation

### From addons.mozilla.org (Recommended)
👉 [Install ToHub-Dark](https://addons.mozilla.org/de/firefox/addon/tohub-dark/)

### Manually
1. Download the latest `.xpi` from the [Releases](../../releases) page.
2. Open Firefox → `about:addons` → gear icon → **Install Add-on From File…**
3. Select the `.xpi` file.

## Compatibility

- Firefox 63 or newer
- All major operating systems

## Technical Notes

> **Note:** The add-on ID `tohub-dark@tohub.rf.gd` is not an email address. It is a unique identifier required by Firefox.

## Development

The theme is a pure WebExtension theme. The only file needed to modify is `manifest.json`.

To test changes locally:
1. Open Firefox → `about:debugging#/runtime/this-firefox`
2. Click **Load Temporary Add-on…**
3. Select `manifest.json`

## License

See [LICENSE](LICENSE) for details.

## Author

**ToHubLabs** — [https://tohub.rf.gd](https://tohub.rf.gd)
