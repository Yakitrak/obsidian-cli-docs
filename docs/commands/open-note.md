---
layout: single
title: "Open Note"
sidebar:
    nav: "docs"
---

The open command opens a given note in Obsidian. The note argument is the note name in the vault, it does not need to be
the entire path (although yo.u can use the path from the root of the vault if you want)

**Note:** Your terminal working directory does not need to be in your vault. You can use any command from anywhere.
{: .notice--info}

To open a note in your default vault:

```zsh
obs open <note-name>
```

To open a note in a specific vault:

```zsh
obs open <note-name> --vault <vault-name>
```

To open a note a where `note-path` is the path from the root of the vault to the note. For example, if you have a note at
`/vault-name/notes/2021-01-01.md`, you can open it with:

```zsh
obs open notes/2021-01-01.md --vault <vault-name>
```