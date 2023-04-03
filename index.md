---
title: "Take Obsidian to the terminal"
layout: splash
# date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "black"
  # overlay_filter: "0.5"
  # overlay_image: /assets/images/unsplash-image-1.jpg
  actions:
    - label: "Or Download Manually"
      url: "https://github.com/Yakitrak/obsidian-cli/releases/latest"
excerpt: |+
  You are able to open, search, create, update and move notes from your vault without leaving your terminal.
  ```bash
   brew tap yakitrak/yakitrak
   brew install yakitrak/yakitrak/obs
  ```
intro:
  - excerpt: "Obsidian CLI allows you to interact with your vault from the terminal without being in the vault folder or using the path - just type name of the note and it will take care of the rest"
feature_row:
  # - image_path: https://raw.githubusercontent.com/Yakitrak/obsidian-cli/main/docs/obs-usage.png
  - title: "Open Note"
    url: "#test-link"
    btn_label: "More Information"
    btn_class: "btn--small"
    excerpt: |+
      ```bash
      # opens cake.md from default vault
      $ obs open cake
      # opens cookies.md from recipes vault
      $ obs open cookies --vault recipes
      ```
      Notes can be opened easily just by name no matter where in the vault they are.
  - title: "Search Note"
    excerpt: |+
      ```bash
      # Creates stars.md in default vault 
      $ obs create stars
      # Creates stars.md with given content
      $ obs create stars --content "abcde"
      ```
      The notes are created in your vault and opened in Obsidian automatically.
    url: "#test-link"
    btn_label: "More Information"
    btn_class: "btn--small"
  - title: "Delete Note"
    excerpt: |+
      ```bash
      # abc
      $ obs move
      # abc
      $ obs move
      ```
      Moves the notes within the vault and updates links wherever notes was linked.
    url: "#test-link"
    btn_label: "More Information"
    btn_class: "btn--small"
feature_row2:
  # - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
  - title: "Create Note"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "More Information"
    btn_class: "btn--primary"
  - excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
  - title: "Update Existing Note"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "More Information"
    btn_class: "btn--primary"
feature_row3:
  - title: "Create / Update Note"
    image-path: ""
    excerpt: |+
      ```bash
      # Creates stars.md in default vault 
      $ obs create stars
      # Creates stars.md with given content
      $ obs create stars --content "abcde"
      ```
      The notes are created in your vault and opened in Obsidian automatically.
    url: "#test-link"
    btn_label: "More Information"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" %}

{% include feature_row id="feature_row3" type="left" %}
