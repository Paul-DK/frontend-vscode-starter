# 🚀 Frontend VS Code Starter

Welcome to **Frontend VS Code Starter** – a fully customized **Visual Studio Code setup** tailored for **frontend development**! 🎨✨ This setup includes all the essential settings, extensions, and tweaks to **boost productivity** and create a seamless development experience.

---

## 📌 Features

✅ **Pre-configured VS Code settings** optimized for frontend devs.  
✅ **Essential extensions** for HTML, CSS, and Git workflows.  
✅ **Linting & Formatting** via ESLint & Prettier.  
✅ **Live Sass Compiler** for automatic SCSS conversion.  
✅ **Accessibility tools** to ensure inclusive designs.  
✅ **Git integration** for streamlined version control.  
✅ **Beautiful UI enhancements** for a clean coding experience.

---

## 📂 What's Included?

This repo contains the following configuration files:

-   **`settings.json`** – Contains all the optimized settings for VS Code.
-   **`extensions.txt`** – A list of recommended extensions for an enhanced frontend dev workflow.
-   **README.md** – This file! Explains how to set up everything.

---

## 🔧 Installation Guide (Windows, Mac, & Linux)

### 1️⃣ **Install VS Code**

If you don’t already have it, download **Visual Studio Code**:  
🔗 [Download VS Code](https://code.visualstudio.com/)

### 2️⃣ **Clone This Repo**

Open a terminal or PowerShell and run:

```bash
git clone https://github.com/Paul-DK/frontend-vscode-starter.git
```

### 3️⃣ **Install Extensions**

#### 🔹 **Windows (PowerShell)**

```powershell
Get-Content extensions.txt | ForEach-Object { code --install-extension $_ }
```

#### 🔹 **Mac/Linux (Terminal)**

```bash
xargs -n 1 code --install-extension < extensions.txt
```

### 4️⃣ **Apply the VS Code Settings**

**Ensure you replace `user` with your actual system username in the paths below.**

#### 🔹 **Windows (PowerShell)**

```powershell
copy settings.json $env:APPDATA\Code\User\settings.json
```

#### 🔹 **Mac**

```bash
cp settings.json ~/Library/Application\ Support/Code/User/settings.json
```

#### 🔹 **Linux**

```bash
cp settings.json ~/.config/Code/User/settings.json
```

### 5️⃣ **Restart VS Code**

Close and reopen VS Code for the settings to take effect. 🎉

---

## 🛠 Recommended Extensions

| Extension                                                                                                                   | Description                                 |
| --------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)                           | Improves comment readability                |
| [Accessibility Snippets](https://marketplace.visualstudio.com/items?itemName=accessibility-snippets.accessibility-snippets) | Helps ensure accessible coding              |
| [CodeSnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)                                             | Take beautiful screenshots of code          |
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)                                        | JavaScript/TypeScript linting               |
| [Axe Accessibility Linter](https://marketplace.visualstudio.com/items?itemName=deque-systems.vscode-axe-linter)             | Finds accessibility issues in code          |
| [CSS Flexbox Cheatsheet](https://marketplace.visualstudio.com/items?itemName=dzhavat.css-flexbox-cheatsheet)                | Quick flexbox reference                     |
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)                                              | Enhances Git integration                    |
| [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)                               | Provides auto-completion for HTML & CSS     |
| [Material Theme](https://marketplace.visualstudio.com/items?itemName=equinusocio.vsc-material-theme)                        | Aesthetic VS Code theme                     |
| [Material Theme Icons](https://marketplace.visualstudio.com/items?itemName=equinusocio.vsc-material-theme-icons)            | Icon pack for Material Theme                |
| [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)                                      | Automatic code formatter                    |
| [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)                        | Auto-updates paired HTML tags               |
| [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=github.copilot)                                        | AI-powered code suggestions                 |
| [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=github.copilot-chat)                              | AI-powered chat for coding help             |
| [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.LiveSass)                                | Compile SCSS/SASS automatically             |
| [Gutter Preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)                   | Preview images in the gutter                |
| [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)                                         | Visual Git history                          |
| [Live Share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare)                                | Collaborative coding in VS Code             |
| [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)                              | Highlights color codes                      |
| [Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)                                | Colorizes indentation levels                |
| [Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)                                                | Create screenshots of code snippets         |
| [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)                                    | Jump to CSS rules from HTML                 |
| [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)                                    | Run a live preview of your HTML/CSS changes |
| [HTML5 Boilerplate](https://marketplace.visualstudio.com/items?itemName=sidthesloth.html5-boilerplate)                      | Quickly generate HTML5 templates            |
| [SVG Preview](https://marketplace.visualstudio.com/items?itemName=simonsiefke.svg-preview)                                  | Preview SVG images                          |
| [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)                       | Enhanced Markdown support                   |

---

## 📜 License

This project is licensed under the **MIT License**, meaning you’re free to use, modify, and distribute it however you like! 😎

---

### 🎉 Happy Coding!
