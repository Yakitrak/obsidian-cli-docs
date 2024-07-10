---
title: "Take Obsidian to the terminal"
layout: splash
# date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "black"
  # overlay_filter: "0.5"
  # overlay_image: /assets/images/unsplash-image-1.jpg
  actions:
    - label: "Full instructions"
      url: "/docs/install/mac-and-linux"
excerpt: |+
  Seamlessly manage notes in your vaults without leaving the terminal!
  ```zsh
   brew tap yakitrak/yakitrak
   brew install yakitrak/yakitrak/obs
  ```
intro:
  - excerpt: "Obsidian CLI enables you to conveniently access your vault from the terminal, without having to navigate to the vault folder or provide the full file path. Simply enter the name of the desired note, and the CLI will take care of the rest."
feature_row:
  - title: "Open Note"
    url: "docs/commands/open-note"
    btn_label: "More Information"
    btn_class: "btn--small"
    excerpt: |+
      ```zsh
      # opens cake.md from default vault
      $ obsd open cake
      # opens cookies.md from recipes vault
      $ obsd open cookies --vault other-vault
      ```
      Open notes in Obsidian by simply typing the note name, regardless of their location within the vault.
  - title: "Search Note"
    excerpt: |+
      ```zsh
      # Opens with search query in default vault
      $ obsd search stars
      # Opens with search query in other-vault
      $ obsd search stars --vault other-vault
      ```
      Perform text searches with ease, Obsidian will open with the query results displayed in the search tab.
    url: "/docs/commands/search-notes"
    btn_label: "More Information"
    btn_class: "btn--small"
  - title: "Delete Note"
    excerpt: |+
      ```zsh
      # Deletes the note in default vault
      $ obsd delete abc
      # Deletes the note in other-vault
      $ obsd delete abc --vault other-vault
      ```
      Deleting a note is just as straightforward as creating one.
    url: "/docs/commands/delete-note"
    btn_label: "More Information"
    btn_class: "btn--small"
feature_row2:
  - image_path: /assets/images/terminal-create-note.gif
    alt: "create note"
    title: "Create Note"
    excerpt: "Effortlessly create new notes by typing the desired note name. Additionally, you can update existing notes using the convenient `--overwrite` or `--append` flags."
    url: "/docs/commands/create-note"
    btn_label: "More Information"
    btn_class: "btn--small"
feature_row3:
  - image_path: /assets/images/terminal-move-note.gif
    alt: "move note"
    title: "Move Note"
    excerpt: "Relocate notes by specifying the current and new paths, and watch as linked notes are automatically updated. Notes can also be renamed in the same way!"
    url: "/docs/commands/move-note"
    btn_label: "More Information"
    btn_class: "btn--small"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row %}

{% include feature_row id="feature_row3" type="right" %}



