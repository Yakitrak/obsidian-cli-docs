---
layout: single
title: "Delete Note"
sidebar:
    nav: "docs"
---

The delete command deletes a note in Obsidian. The note argument is the note path (starting from the root of the vault).

**Note:** Your terminal working directory does not need to be in your vault. You can use any command from anywhere.
{: .notice--info}

To delete a note in your default vault:

```zsh
obs delete <note-path>
```

To delete a note in a specific vault:

```zsh
obs delete <note-path> --vault <vault-name>
```



