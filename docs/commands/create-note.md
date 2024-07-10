---
layout: single
title: "Create Note"
sidebar:
    nav: "docs"
---

The `create` command creates (or update if one exists) a note in Obsidian. The `<note-name>` is the note name which will be created in top level of the vault, but you can instead pass a path instead to create a note in a subfolder of the vault.

To create a note in your default vault:

```zsh
obsd create <note-name>
```

To create a note in a specific vault:

```zsh
obsd create <note-name> --vault <vault-name>
```

To create a note a where `<note-name>` is the path from the top folder of the vault to the note. For example, if you want to create a note in `vault-name/folder/another folder/cookies`, you can create it with:

```zsh
obsd create "folder/another folder/cookies"
```

To create a note with content:

```zsh
obsd create <note-name> --content <content>
```
For example 

```zsh
obsd create cookies --content "I like cookies"
```

By default, if the note already exists, a new note will be created with a number appended to the end of the note name. For example, if you have a note called `cookies` and you try to create a note with the same name, the new note will be called `cookies1`. 

You can overwrite the note content with the `--overwrite` flag which will replace the content of the note with the new content:

```zsh
obsd create <note-name> --content <content> --overwrite
```

Or you can add more content to the end of the note with the `--append` flag:

```zsh
obsd create <note-name> --content <content> --append
```

To open the created note, you can use the `--open` flag:

```zsh
obsd create <note-name> --open
```