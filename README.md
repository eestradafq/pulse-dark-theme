# 🌙 Pulse Dark Theme

[![Version](https://img.shields.io/badge/version-0.0.1-blue.svg)](https://github.com/yourusername/pulse-dark-theme)
[![VS Code](https://img.shields.io/badge/VS%20Code-1.102.0+-007ACC.svg)](https://code.visualstudio.com/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

A clean and modern dark theme for Visual Studio Code with balanced colors and smooth syntax highlighting that's easy on your eyes during long coding sessions.

## ✨ Features

- **🎨 Modern Design**: Elegant dark interface with carefully balanced colors
- **👁️ Eye-friendly**: Color palette optimized to reduce visual fatigue
- **🔧 Complete Support**: Compatible with all popular programming languages
- **🎯 Precise Highlighting**: Detailed and consistent syntax highlighting
- **🌈 Semantic Colors**: Clear differentiation between code types

## 🎨 Color Palette

### Main Colors
- **Primary Background**: `#1a1a1a` - A soft and elegant black
- **Secondary Background**: `#141414` - For sidebars and panels
- **Primary Text**: `#D8DEE9` - Soft white for comfortable reading
- **Secondary Text**: `#CCCCCC99` - For less important elements

### Syntax Colors
- **Functions**: `#efb080` - Warm orange for functions
- **Classes**: `#87c3ff` - Light blue for classes and types
- **Strings**: `#e394dc` - Soft pink for text strings
- **Numbers**: `#ebc88d` - Golden yellow for numeric values
- **Keywords**: `#83d6c5` - Aqua green for keywords
- **Variables**: `#AA9BF5` - Soft purple for properties
- **Comments**: `#6d6d6d` - Gray for comments (with italic style)

## 🚀 Installation

### From VS Code Marketplace
1. Open Visual Studio Code
2. Go to the Extensions tab (`Ctrl+Shift+X`)
3. Search for "Pulse Dark Theme"
4. Click "Install"
5. Go to `File > Preferences > Color Theme` and select "Pulse Dark Theme"

### Manual Installation
1. Download this repository
2. Copy the folder to your VS Code extensions directory:
   - **Windows**: `%USERPROFILE%\.vscode\extensions`
   - **macOS**: `~/.vscode/extensions`
   - **Linux**: `~/.vscode/extensions`
3. Restart VS Code
4. Select the theme from `File > Preferences > Color Theme`

## 🔧 Recommended Settings

For the best experience with Pulse Dark Theme, we recommend using these settings in your `settings.json`:

```json
{
  "editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.5,
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "workbench.iconTheme": "material-icon-theme"
}
```

## 💻 Supported Languages

Pulse Dark Theme includes optimized support for:

- **JavaScript/TypeScript** - Advanced semantic highlighting
- **Python** - Support for decorators and special methods
- **C/C++** - Complete syntax for systems development
- **Java** - Types and annotations
- **PHP** - Namespaces and modern functions
- **CSS/SCSS/Less** - Properties and selectors
- **HTML** - Tags and attributes
- **Markdown** - Headers, links and formatting
- **JSON** - Differentiated keys and values
- **Go** - Operators and packages
- **Rust** - Lifetimes and ownership
- **And many more...**

## 📷 Screenshots

### JavaScript/TypeScript
```javascript
// Example code with Pulse Dark Theme
class PulseTheme {
  constructor(name) {
    this.name = name;
    this.colors = ['#efb080', '#87c3ff', '#e394dc'];
  }
  
  applyTheme() {
    console.log(`Applying theme: ${this.name}`);
    return this.colors.map(color => `hsl(${color})`);
  }
}
```

### Python
```python
# Decorators and classes with optimized highlighting
@dataclass
class ThemeConfig:
    name: str = "Pulse Dark"
    background: str = "#1a1a1a"
    
    def get_colors(self) -> Dict[str, str]:
        return {
            "functions": "#efb080",
            "classes": "#87c3ff",
            "strings": "#e394dc"
        }
```

## 🛠️ Development

### Project Structure
```
pulse-dark-theme/
├── package.json           # Extension configuration
├── themes/
│   └── pulse-dark-theme.json   # Theme definition
├── CHANGELOG.md          # Change history
└── README.md            # This file
```

### Customization
If you want to customize the theme:

1. Clone this repository
2. Modify `themes/pulse-dark-theme.json`
3. Install the extension locally
4. Contribute your improvements

## 🤝 Contributing

Contributions are welcome! If you find a bug or have a suggestion:

1. Fork this repository
2. Create a branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Reporting Issues
- Use [GitHub Issues](https://github.com/eestradafq/pulse-dark-theme/issues)
- Include screenshots if possible
- Specify your VS Code version and operating system

## 📝 Changelog

### [0.0.1] - 2025-08-03
- ✨ Initial theme release
- 🎨 Base color palette implemented
- 💻 Support for all major languages
- 🔧 Semantic color configuration
- 📚 Initial documentation

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ❤️ Acknowledgments

- Inspired by modern dark theme design principles
- Colors carefully selected for optimal development experience
- VS Code community for feedback and suggestions

---

**Enjoy coding with Pulse Dark Theme!** 🚀

If you like this theme, please consider:
- ⭐ Starring the repository
- 📝 Leaving a review on VS Code Marketplace
- 🐛 Reporting bugs or suggesting improvements
- 📤 Sharing with other developers
