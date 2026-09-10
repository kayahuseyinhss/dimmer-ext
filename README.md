# dimmer-ext

MV3 extension playground: page reading-time estimator

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Highlights

- Per-tab time persisted to chrome.storage
- Manifest V3, service worker based
- Popup shows today's total focus time
- No remote calls, everything stays local

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT - see [LICENSE](LICENSE).
