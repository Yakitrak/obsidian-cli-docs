---
layout: single
title: "Delete Note"
sidebar:
    nav: "docs"
---

The `delete` command deletes a note in Obsidian. The `<note-path>` is the path to the note which will be deleted from the top level of the vault.

To delete a note in your default vault:

```zsh
obsidian-cli delete <note-path>
```

To delete a note in a specific vault:

```zsh
obsidian-cli delete <note-path> --vault <vault-name>
```



