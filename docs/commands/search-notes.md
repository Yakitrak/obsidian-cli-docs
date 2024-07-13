---
layout: single
title: "Search Notes"
sidebar:
    nav: "docs"
---

The `search` commands opens Obsidian on the search tab with the search query provided. The `<search-query>` is the search query to be used in Obsidian.


To search in your default vault:

```zsh
obsidian-cli search <search-query>
```

To search in a specific vault:

```zsh
obsidian-cli search <search-query> --vault <vault-name>
```