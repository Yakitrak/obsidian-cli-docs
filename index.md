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
      url: "/docs/installation/mac-and-linux"
excerpt: |+
  You are able to open, create, update and move notes from your vault without leaving your terminal.
  ```zsh
   brew tap yakitrak/yakitrak
   brew install yakitrak/yakitrak/obs
  ```
intro:
  - excerpt: "Obsidian CLI allows you to interact with your vault from the terminal without being in the vault folder or using the full path, just type name of the note and it will take care of the rest"
feature_row:
  - title: "Open Note"
    url: "docs/commands/open-note"
    btn_label: "More Information"
    btn_class: "btn--small"
    excerpt: |+
      ```zsh
      # opens cake.md from default vault
      $ obs open cake
      # opens cookies.md from recipes vault
      $ obs open cookies --vault other-vault
      ```
      Notes can be opened in Obsidian just by note name, no matter where in the vault they are.
  - title: "Search Note"
    excerpt: |+
      ```zsh
      # Opens with search query in default vault
      $ obs search stars
      # Opens with search query in other-vault
      $ obs create stars --vault other-vault
      ```
      Search for any text, it will open the vault with the search query.
    url: "/docs/commands/search-notes"
    btn_label: "More Information"
    btn_class: "btn--small"
  - title: "Delete Note"
    excerpt: |+
      ```zsh
      # Deletes the note in default vault
      $ obs delete abc
      # Deletes the note in other-vault
      $ obs default abc --vault other-vault
      ```
      Deleting the note is as easy as creating it.
    url: "/docs/commands/delete-note"
    btn_label: "More Information"
    btn_class: "btn--small"
feature_row2:
  - image_path: /assets/images/terminal-create-note.gif
    alt: "create note"
    title: "Create Note"
    excerpt: "Simply type the name of the note you want to create. You can also update notes by `--overwrite` or `--append` flags"
    url: "/docs/commands/create-note"
    btn_label: "More Information"
    btn_class: "btn--small"
feature_row3:
  - image_path: /assets/images/terminal-move-note.gif
    alt: "move note"
    title: "Move Note"
    excerpt: "Move notes with ease, just type the current name and the new path. All other notes that link to the note will also be updated. Notes can also be renamed easily in the same way!"
    url: "/docs/commands/move-note"
    btn_label: "More Information"
    btn_class: "btn--small"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row %}

{% include feature_row id="feature_row3" type="right" %}



