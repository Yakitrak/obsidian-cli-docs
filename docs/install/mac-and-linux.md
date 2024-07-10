---
layout: single
title: "Mac & Linux Installation"
sidebar:
  nav: "docs"
---

## Homebrew

---

### Step 1: Install Homebrew

---

Follow instructions [here](https://brew.sh/) to install homebrew package manager

### Step 2: Tap the yakitrak repository

---

```zsh
brew tap yakitrak/yakitrak
```

### Step 3: Install Obsidian CLI

---

```zsh
brew install yakitrak/yakitrak/obs
```

**Note:** If you want to upgrade to the latest version, you can use `brew upgrade yakitrak/yakitrak/obs`
{: .notice--info}

## AUR

---

Maintained by [Jonathan Neidel](https://www.jneidel.com/)

```zsh
yay -S obsd-bin
```

## Confirm installation

---

```zsh
obsd --version
```

After installation, you can now run `obsd` from anywhere on your system. To set up your default vault, please refer to [Set Default Vault]({{ site.baseurl }}{% link docs/commands/set-default-vault.md %}).
