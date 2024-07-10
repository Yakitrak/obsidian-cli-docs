---
layout: single
title: "Set Default Vault"
sidebar:
    nav: "docs"
---

When using any commands, you will need to specify the vault. This can be done by using
the `--vault` flag. However, if you are using the same vault frequently, you can set it as your default vault. This will
mean that you do not need to specify the vault every time you use a command. You can set your default vault by running:

```zsh
obsidian-cli set-default <vault-name>
```

Where `<vault>-name` is the name of your vault. This is not the path of the vault but the name of the folder. For
example, if your vault is located at `~/Documents/example-vault`, then the vault name is `example-vault`.

**Note:** You need to ensure you have already opened the vault in Obsidian before you can set it as your default
vault.
{: .notice--warning}

If your folder has spaces in it, you will need to wrap the name in quotes. For example, if your vault is
located at `~/Documents/My Vault`, then you would run:

```zsh
obsidian-cli set-default "My Vault"
```

If you have set your default vault successfully, you will see the following message:

```zsh
Default vault set to: <vault-name>
Default vault path set to: <vault-path>
``` 

You can also print your default vault as shown in [Print Default Vault]({{ site.baseurl }}{% link docs/commands/print-default-vault.md %}). You can now start using commands without having to specify the vault.

