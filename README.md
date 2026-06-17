# Jackhammer Syntax — VS Code

A dark syntax theme with muted pastel accents on a near-black navy background. Ported from the original [Atom theme](https://github.com/muukii/jackhammer-syntax) by [muukii](https://github.com/muukii).

<img width="1464" height="816" alt="image" src="https://github.com/user-attachments/assets/04f8f41f-39e4-4ff2-8b52-9bed0a5257b8" />


## Installation

### From the Marketplace
1. Open **Extensions** in VS Code (`Cmd+Shift+X`)
2. Search for **Jackhammer Syntax**
3. Click **Install**
4. Open the Command Palette (`Cmd+K Cmd+T`) and select **Jackhammer**

### Manual Install
1. Download the `.vsix` file from [Releases](https://github.com/voidpls/jackhammer-syntax-vscode/releases)
2. Run `code --install-extension jackhammer-syntax-1.0.0.vsix`

## Palette

| Token | Hex | Use |
|-------|-----|-----|
| Very Light Gray | `#c5c8c6` | Default text |
| Light Gray | `#485375` | Comments |
| Gray | `#373F59` | Guides |
| Dark Gray | `#262B3D` | Borders, hover |
| Very Dark Gray | `#1D212E` | Editor background |
| Light Navy | `#65759B` | Variables, regexp |
| Blue | `#8ABCD5` | Types, headings, tags |
| Purple | `#C4B4C6` | Italic, decorators |
| Pink | `#E99FBF` | Numbers, inserted |
| Red | `#E04D69` | Keywords, storage |
| Orange | `#CA708A` | Strings, constants |

## Scope Coverage

The theme includes token colors for:
- Core syntax (keywords, strings, constants, variables, comments)
- HTML/CSS/SCSS tags, properties, pseudo-classes
- JSON/YAML keys and values
- Markdown headings, bold, italic, links, code blocks, blockquotes
- Git diff markers (inserted, deleted, changed)
- Rust, Go, Swift, Python, Ruby specifics
- Semantic highlighting for TypeScript/JavaScript

## Developing

```bash
# Package the extension
npx @vscode/vsce package

# Install locally
code --install-extension jackhammer-syntax-1.0.0.vsix
```

## Credits

- Original Atom theme by [muukii](https://github.com/muukii)
- VS Code port by [voidpls](https://github.com/voidpls)

## License

MIT
