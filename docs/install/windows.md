---
layout: single
title: "Windows Installation"
sidebar:
  nav: "docs"
---

#### Step 1: Install Scoop

---
Follow instructions [here](https://scoop.sh/) to install scoop package manager.

#### Step 2: Add the yakitrak bucket

---
On powershell, run the following command to add the yakitrak bucket to scoop:
```powershell
scoop bucket add scoop-yakitrak https://github.com/yakitrak/scoop-yakitrak.git
```
#### Step 3: Install Obsidian CLI

---
```powershell
scoop install obsidian-cli
```

#### Step 4: Confirm installation

```zsh
obsd --version
```

After installation, you can now run `obsd` from anywhere on your system. To set up your default vault, please refer to [Set Default Vault]({{ site.baseurl }}{% link docs/commands/set-default-vault.md %}).


