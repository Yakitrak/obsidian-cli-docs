---
layout: single
title: "Print Default Vault"
sidebar:
    nav: "docs"
---

Once you have set a default vault using [Set Default Vault]({{ site.baseurl }}{% link docs/commands/set-default-vault.md %}), you can confirm that it has been set by running:

```zsh
obsidian-cli print-default
```

This will print:
```zsh
Default vault name: <vault-name>
Default vault path: <vault-path>

```