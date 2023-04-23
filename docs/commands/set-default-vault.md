---
layout: single
title: "Set Default Vault"
sidebar:
    nav: "docs"
---

When using any of the commands that require a vault, you will need to specify the vault. This can be done by using
the `--vault` flag. However, if you are using the same vault frequently, you can set it as your default vault. This will
mean that you do not need to specify the vault every time you use a command. You can set your default vault by running:

```zsh
obs set-default-vault <vault-name>
```

Where `<vault>-name` is the name to your vault. This is not the path of the vault but the name of the folder. For
example, if your vault is located at `~/Documents/example-vault`, then the vault name is `example-vault`.

**Note:** You need to ensure you have already opened the vault in Obsidian before you can set it as your default
vault.
{: .notice--warning}

This will print the following:

```zsh
Default vault set to:  <vault-name>
Default vault path set to:  ~/Documents/<vault-name>
``` 

You can also confirm what your default vault is by going to [Print Default Vault]({{ site.baseurl }}{% link docs/commands/print-default-vault.md %}). Otherwise you can now start using any of the commands that require a vault without having to specify the vault.

