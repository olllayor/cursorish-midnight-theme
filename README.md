# Cursorish Midnight Theme

An ultra-dark VS Code theme designed specifically for night-time coding and minimal eye strain. Cursorish Midnight provides a pure dark experience with vibrant syntax highlighting that remains visible even in low-light conditions.

## Features

- 🌃 Ultra-dark color scheme perfect for night-time coding
- 🎨 Vibrant syntax highlighting visible in dark environments
- 💻 Full syntax highlighting support for all major languages
- 🎯 Optimized semantic token colors for modern VS Code
- ✨ Beautiful UI elements with consistent styling
- 👁️ Minimal eye strain with ultra-dark backgrounds
- 🎨 6-level rainbow bracket highlighting
- 🌙 Perfect for extended night coding sessions

## Installation

### From VS Code Marketplace

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for "Cursorish Midnight"
4. Click Install
5. Select "Cursorish Midnight" from the theme selector (Ctrl+K Ctrl+T / Cmd+K Cmd+T)

### Manual Installation

Clone the repository and copy the theme file to your VS Code extensions folder:

```bash
# macOS
cp -r cursorish-midnight-theme ~/.vscode/extensions/

# Linux
cp -r cursorish-midnight-theme ~/.config/Code/extensions/

# Windows
copy cursorish-midnight-theme %USERPROFILE%\.vscode\extensions\
```

## Color Palette

The theme uses an ultra-dark color palette optimized for night-time coding:

- **Background**: `#0a0e27` - Pure ultra-dark for minimal light emission
- **Foreground**: `#e8eaf6` - Soft white text for comfortable reading
- **Primary Accent**: `#7986cb` - Soft indigo for primary elements
- **Secondary Accent**: `#9fa8da` - Lighter indigo for secondary elements
- **Success**: `#4caf50` - Green for additions and success states
- **Error**: `#ef5350` - Red for errors and critical states
- **Warning**: `#ffb74d` - Orange for warnings and caution states
- **Info**: `#29b6f6` - Bright cyan for informational elements

## Supported Languages

The theme provides optimized syntax highlighting for:

- **Web**: JavaScript, TypeScript, HTML, CSS, Vue, React
- **Python**: Full support including decorators and type hints
- **Java**: Classes, methods, imports, and generics
- **C/C++**: Types, functions, preprocessor directives
- **Go**: Functions, types, and interfaces
- **Rust**: Lifetimes, traits, and macros
- **JSON/YAML**: Proper colors for data structures
- **Markdown**: Headers, emphasis, links, and code blocks
- **Bash/Shell**: Commands and syntax highlighting
- **And many more...**

## Semantic Highlighting

The theme includes comprehensive semantic token colors for enhanced syntax highlighting in supported languages, providing better distinction between:

- **Variables**: Constants, globals, readwrite variables
- **Functions**: Built-in, declarations, method calls
- **Classes and Types**: Declarations, built-in types, type hints
- **Properties and Methods**: Class members, object properties
- **Decorators**: Python decorators, annotations
- **Special Parameters**: Self/this parameters
- **Macros**: Preprocessor directives and macros

## UI Customization

You can customize the theme colors by creating a user settings override:

1. Open VS Code Settings (Cmd+, / Ctrl+,)
2. Search for "workbench.colorCustomizations"
3. Add your custom colors:

```json
"workbench.colorCustomizations": {
    "editor.background": "#0a0e27",
    "editor.foreground": "#e8eaf6",
    "editor.lineHighlightBackground": "#1a1f3a",
    "activityBar.background": "#0f1329"
}
```

## Bracket Highlighting

The theme includes 6-level rainbow bracket highlighting to help distinguish nested code structures:

1. **Level 1**: Indigo
2. **Level 2**: Light indigo
3. **Level 3**: Cyan
4. **Level 4**: Purple
5. **Level 5**: Pink
6. **Level 6**: Light pink

## Terminal Colors

Full ANSI color support including:

- **Standard colors** (black, red, green, yellow, blue, magenta, cyan, white)
- **Bright variants** for enhanced visibility in dark terminals
- **Optimized contrast** for terminal readability

## Git Integration

Custom colors for Git decorations:

- **Modified**: Orange
- **Added**: Green
- **Deleted**: Red
- **Untracked**: Cyan
- **Ignored**: Dimmed gray

## Why Cursorish Midnight?

Cursorish Midnight is designed for developers who:

- Code during night hours and need minimal eye strain
- Prefer ultra-dark themes over standard dark themes
- Want vibrant syntax highlighting that stands out
- Spend long hours in dark environments
- Need a theme optimized for low-light viewing

## Feedback & Support

If you have suggestions or find any issues with the theme, please open an issue on the [GitHub repository](https://github.com/olllayor/cursorish-midnight-theme).

## License

MIT License - see LICENSE file for details

## Credits

Created with ❤️ for night-time developers and late-night coders.

## Companion Themes

Explore other themes in the Cursorish collection:

- **Cursorish Light** - [Clean light theme](https://marketplace.visualstudio.com/items?itemName=ollayor.cursorish-light-theme) for bright environments
- **Cursorish Dark** - [Dark theme](https://marketplace.visualstudio.com/items?itemName=ollayor.cursorish-dark-theme) for any lighting condition
