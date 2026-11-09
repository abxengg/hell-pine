
# 🌑 Hell Pine — A Darker Twist on Rosé Pine

[![ci](https://github.com/abxengg/hell-pine/actions/workflows/ci.yml/badge.svg)](https://github.com/abxengg/hell-pine/actions/workflows/ci.yml)

> _“Born in the fire of tmux, refined for the calm of code.”_

**Hell Pine** is a bold, terminal-inspired dark theme for Visual Studio Code — a meticulously crafted evolution of [Rosé Pine](https://rosepinetheme.com/), born from the nuanced visual shifts experienced within **tmux** sessions. What began as a subtle observation became a deliberate design — optimized for developers who live in the terminal and demand both beauty and clarity in their workflow.

> This is Rosé Pine after going through hell... and coming back beautiful.

---

## ✨ Why Hell Pine?

While working with Rosé Pine inside `tmux`, I discovered unexpected but aesthetically pleasing color distortions — deeper shadows, punchier highlights, and an overall sharper contrast. It felt raw yet refined — and I knew it deserved to be more than a glitch.

**Hell Pine** is my response — a theme that retains the elegance of Rosé Pine while infusing it with terminal grit and expressive contrast. The result is a developer-centric palette perfect for long coding sessions, especially in split-pane, multi-window environments.

---


## Preview

![Rust Snippet](./assets/preview/rust.png)
![Zig Snippet](./assets/preview/zig.png)
![JS Snippet](./assets/preview/js.png)
![Java Snippet](./assets/preview/java.png)

---

## 💻 Developer Setup

To enhance the look and feel of your editor or code previews, it's **recommended** to add the following to your VS Code `settings.json`:

```json
{
    "editor.fontWeight": "600"
}
```
---


## 🎨 Features

- 🖤 **Dark elegance** with enhanced contrast and visual edge  
- 🧠 **Focus-driven** colors for reduced eye fatigue  
- ⚡️ **Optimized** for terminal emulators and Tmux workflows  
- 🧩 **Semantic highlighting** — colors stay consistent when language servers (TypeScript, Rust, Java, Go, …) take over
- 📝 Tuned for code, JSON/YAML, CSS/HTML and Markdown

---

## 🚀 Installation

### 🔌 From the VS Code Marketplace

Simply search for `Hell Pine` in the Extensions tab or install directly via command:

```bash
ext install ABX.hell-pine
```

Or visit the Marketplace page here:
📎 https://marketplace.visualstudio.com/items?itemName=ABX.hell-pine

### 🛠️ Manual Installation

Build and install the `.vsix` yourself:

```bash
git clone https://github.com/abxengg/hell-pine.git
cd hell-pine
npx @vscode/vsce package
code --install-extension hell-pine-*.vsix
```

Then open the Command Palette → **Preferences: Color Theme** → **Hell Pine**.

To hack on the theme, open the folder in VS Code and press <kbd>F5</kbd> — an Extension Development Host window opens with your changes applied live.

## 🔧 Development & Releases

- **CI** ([`ci.yml`](.github/workflows/ci.yml)): every push to `master` and every pull request validates the theme colors and builds the `.vsix`, which is attached to the run as an artifact.
- **Release** ([`release.yml`](.github/workflows/release.yml)): pushing a version tag publishes the extension.

To release a new version:

1. Bump `version` in `package.json` and add a section to [`CHANGELOG.md`](CHANGELOG.md).
2. Commit, then tag and push: `git tag vX.Y.Z && git push origin master vX.Y.Z`.

The release workflow checks that the tag matches `package.json`, creates the GitHub release with the `.vsix` and the changelog notes, and publishes to the VS Code Marketplace using the `VSCE_PAT` repository secret.

### 🙏 Acknowledgements

Huge appreciation to the creators of [Rosé Pine](https://rosepinetheme.com/) for the inspiration and aesthetic foundation.

### 🔮 Stay Updated
More ABX creations coming soon.


