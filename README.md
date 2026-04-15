# 🌊 Cyber Deep Sea

A dark color theme for Visual Studio Code inspired by the deep sea and cyber aesthetics.

深海の暗く冷たい水中に、サイバー的な発光がほのかに浮かぶイメージのダークテーマです。
シアン灰系の落ち着いたトーンをベースに、長時間のコーディングでも目が疲れにくい配色を目指しています。

<!-- スクリーンショットを撮影したら以下に追加
## Screenshots

![Editor](images/screenshot-editor.png)
-->

## Features

- 🎨 252 color definitions covering the entire UI
- 👁️ All colors meet WCAG AA contrast ratio (4.5:1+)
- 🧊 Muted cyan-gray text inspired by deep ocean tones
- 💎 Low-saturation token colors (≤55%) for reduced eye strain
- 🌈 Rainbow indent guides & bracket pair colorization
- 🐚 15 syntax highlight groups for clear code readability

## Color Palette

| Role | Hex |
|---|---|
| Background | `#0a1218` |
| UI Text | `#a0bcc0` |
| Code Text | `#b0ccd0` |
| Accent Green | `#48d8a0` |
| Accent Cyan | `#78c8e8` |
| Keywords | `#d87878` |
| Strings | `#7cc098` |
| Classes | `#7c9cd8` |
| Methods | `#c488d8` |
| Parameters | `#d8a878` |

## Installation

### From VSIX (local)

```bash
npm install
npx vsce package
```

Then in VS Code:

```
Ctrl+Shift+P → Extensions: Install from VSIX...
```

### From Marketplace

Search for **Cyber Deep Sea** in the Extensions view (`Ctrl+Shift+X`).

## Development

Press `F5` to launch the Extension Development Host and preview the theme.

See `THEME_DESIGN.md` for detailed design guidelines and color specifications.

## License

[MIT](./LICENSE)
