---
layout: single
title: "Move Note"
sidebar:
    nav: "docs"
---

The `move` command moves a note in your vault. The `<current-note-path>` and `<new-note-path>` are the paths to the note which will be moved and the path to the new note respectively. If the path to the new note does not exist, it will be created. 

To move a note in your default vault:

```zsh
obsd move <current-note-path> <new-note-path>
```

To move a note in a specific vault:

```zsh
obsd move <current-note-path> <new-note-path> --vault <vault-name>
```

To move (or rename) a note and open it  
```zsh
obsd move <note-path> <new-note-path> --open
```

**Note:** This command can also be used to rename a note by providing the same path for both `<current-note-path>` and `<new-note-path>`. For example `obsd move "folder name/cake" "folder name/cookies"` will rename the note `cake` to `cookies`.
{: .notice--info}


