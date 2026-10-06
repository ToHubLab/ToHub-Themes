# ToHub-Themes

All custom Firefox themes by ToHubLabs in one place — minimalist, modern, and inspired by real-world designs.

Each theme is a standalone WebExtension with its own `manifest.json` and icon set.

## Available Themes

| Theme | Description | Install |
|---|---|---|
| **Amt-Rot** | A dark theme inspired by German administrative red/grey design. | [Install on Firefox](https://addons.mozilla.org/de/firefox/addon/amt-rot/) |
| **ToHub-Dark** | A clean, minimalist dark theme with deep blacks. | [Install on Firefox](https://addons.mozilla.org/de/firefox/addon/tohub-dark/) |
| **Wasteland — The Hot Grain** | A post-apocalyptic theme with warm dust, rust, and hot grain tones. | [Install on Firefox](https://addons.mozilla.org/de/firefox/addon/wasteland-hot-grain/) |

*More themes coming soon.*

## Installation

### From addons.mozilla.org (Recommended)

Click the **Install on Firefox** link in the table above.

### Manually

1. Download the `.xpi` from the [Releases](../../releases) page.
2. Open Firefox → `about:addons` → gear icon → **Install Add-on From File…**
3. Select the `.xpi` file.

## Development

Each theme folder contains its own `manifest.json` and icons. To test a theme locally:

1. Open Firefox → `about:debugging#/runtime/this-firefox`
2. Click **Load Temporary Add-on…**
3. Select the `manifest.json` inside the theme folder.

## Structure
