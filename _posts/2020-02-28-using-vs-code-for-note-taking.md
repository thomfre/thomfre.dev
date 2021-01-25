---
title:  "Using VS Code for note taking"
date:   2020-02-28 19:04:20 +0100
categories: vscode notes offsec oscp
published: true
---

During my [PWK (Penetration Testing with Kali Linux)](https://www.offensive-security.com/pwk-oscp/) course and lab time, I used VS Code extensively to write my own _research notes_. I used Joplin for enumeration and attack notes.

VS Code combined with Markdown and git (and GitHub, Gitlab etc) make up a very powerful note tool. Below you'll see a list of all the extensions I've added, which make working with Markdown in VS Code even easier.

I recommend structuring your notes in folders that make sense to you. Well structured notes serve a dual purpose, the first is to make the knowledge stick better during the research phase, the second is to make it easier to find what you need when you have to use your notes later.

All of the extensions listed below can also be installed in VSCodium (which is installed by default in Parrot), or you can [install VS Code via snap](https://code.visualstudio.com/docs/setup/linux):

```bash
sudo snap install --classic code # or code-insiders
```

## Fonts

I'm a developer, and a huge fan of the [Fira Code](https://github.com/tonsky/FiraCode) font. If you, like me, want to run this on Linux, you can install the fonts I use with:

```bash
sudo apt install fonts-firacode fonts-noto-color-emoji
```

## VS Code configuration

The following extensions should be installed when viewing/using this repository:

- Github Markdown Preview - [bierner.github-markdown-preview](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview)
- markdownlint - [davidanson.vscode-markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- Markdown Paste - [telesoho.vscode-markdown-paste-image](https://marketplace.visualstudio.com/items?itemName=telesoho.vscode-markdown-paste-image)
- Markdown Navigate - [jrieken.md-navigate](https://marketplace.visualstudio.com/items?itemName=jrieken.md-navigate)
- Markdown All in One - [yzhang.markdown-all-in-one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- Word Count - [ms-vscode.wordcount](https://marketplace.visualstudio.com/items?itemName=ms-vscode.wordcount)
- Markdown PDF - [yzane.markdown-pdf](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)
- Code Spell Checker - [streetsidesoftware.code-spell-checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- GitLens — Git supercharged - [eamodio.gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- PowerShell - [ms-vscode.PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)
- Python - [ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- Ruby - [rebornix.Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)
- C/C++ - [vscode.cpptools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
- C# - [ms-vscode.csharp](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)
- Language Support for Java (TM) by Red Hat - [redhat.java](https://marketplace.visualstudio.com/items?itemName=redhat.java)
- vscode-icons - [vscode-icons-team.vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- Polacode - [pnp.polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)
- vscode-pdf - [tomoki1207.pdf](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf)
- hexdump for VSCode - [slevesque.vscode-hexdump](https://marketplace.visualstudio.com/items?itemName=slevesque.vscode-hexdump)

### My VS Code settings.json

```json
{
  "telemetry.enableTelemetry": false,
  "telemetry.enableCrashReporter": false,
  "editor.formatOnSave": true,
  "workbench.iconTheme": "vscode-icons",
  "editor.fontFamily": "Fira Code,Noto Color Emoji",
  "editor.fontSize": 14,
  "editor.fontLigatures": true,
  "markdown-pdf.executablePath": "/opt/google/chrome/chrome",
  "editor.codeActionsOnSave": {
    "source.fixAll.markdownlint": true
  }
}
```

## GitHub markdown

I use GitHub flavored markdown: [Writing on GitHub](https://help.github.com/en/github/writing-on-github)