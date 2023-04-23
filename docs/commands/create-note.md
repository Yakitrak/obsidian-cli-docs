---
layout: single
title: "Create Note"
sidebar:
    nav: "docs"
---

The create command creates (or update if one exists) a note in Obsidian. The note argument is the note name in the vault which will be created in the root of the vault, but you can pass a path to create a note in a subdirectory.

**Note:** Your terminal working directory does not need to be in your vault. You can use any command from anywhere.
{: .notice--info}

To create a note in your default vault:

```zsh
obs create <note-name>
```

To create a note in a specific vault:

```zsh
obs create <note-name> --vault <vault-name>
```

To create a note a where `note-path` is the path from the root of the vault to the note. For example, if you want to create a note at `/vault-name/notes/2021-01-01.md`, you can create it with:

```zsh
obs create notes/2021-01-01.md --vault <vault-name>
```

To create a note with content in your default vault:

```zsh
obs create <note-name> --content <content>
```

By default, if the note already exists, a new note will be created with a number appended to the end of the note name. For example, if you have a note called `2021-01-01.md` and you try to create a note with the same name, the new note will be called `2021-01-01-1.md`. 

You can override the note content with the `--override` flag:

```zsh
obs create <note-name> --content <content> --override
```

Or you can append the content to the end of the note with the `--append` flag:

```zsh
obs create <note-name> --content <content> --append
```