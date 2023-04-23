---
layout: single
title: "Move Note"
sidebar:
    nav: "docs"
---

The move command moves a note in Obsidian. The note arguments are the note path (starting from the root of the vault). If the path to the new note does not exist, it will be created. 

**Note:** This command can also be used to rename a note by providing the same path to the new note as the old note.
{: .notice--info}

**Note:** Your terminal working directory does not need to be in your vault. You can use any command from anywhere.
{: .notice--info}

To move a note in your default vault:

```zsh
obs move <note-path> <new-note-path>
```

To move a note in a specific vault:

```zsh
obs move <note-path> <new-note-path> --vault <vault-name>
```

To move or rename a note and open it  
```zsh
obs move <note-path> <new-note-path> --open
```


