---
layout: single
title: "Open Note"
sidebar:
    nav: "docs"
---

The `open` command allows you to open a specific note within your vault. 
The `<note-name>` refers to the name of the note in the vault, and it doesn't have to be the complete path 
(although you can still use the path from the top-level folder of the vault if desired).

To open a note in your default vault:

```zsh
obsd open <note-name>
```

To open a note in a specific vault:

```zsh
obsd open <note-name> --vault <vault-name>
```

For example, to open a note in `vault/folder name/cake.md`, you can run:

```zsh
obsd open cake 
```

Alternatively, you can use the full path:

```zsh
obsd open "folder name/cake" 
```
