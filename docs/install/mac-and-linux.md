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
brew install yakitrak/yakitrak/obsidian-cli
```

**Note:** If you want to upgrade to the latest version, you can use `brew upgrade yakitrak/yakitrak/obsidian-cli`
{: .notice--info}

## AUR

---

Maintained by [Jonathan Neidel](https://www.jneidel.com/)

```zsh
yay -S obsidian-cli-bin
```

## Confirm installation

---

```zsh
obsidian-cli --version
```

After installation, you can now run `obsidian-cli` from anywhere on your system. To set up your default vault, please refer to [Set Default Vault]({{ site.baseurl }}{% link docs/commands/set-default-vault.md %}).

## Alias

`obsidian-cli` could be alias to anything you like in a shell config of your choice.

`.zshrc`:

```zsh
alias obsdn='obsidian-cli'
```