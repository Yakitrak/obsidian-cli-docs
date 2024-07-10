---
layout: single
title: "General Tips"
sidebar:
  nav: "docs"
---

**Tip 1:** You do not have to manually navigate to the vault folder unless you want to. All commands will function as if you're already in the vault folder. However, if you need to access it, you can use the [Print Default Vault]({{ site.baseurl }}{% link docs/commands/print-default-vault.md %}) command to obtain the path.
{: .notice--info}

**Tip 2:** When using the `open` or `create` commands you do not need to specify the full path to note, however for the `delete` or `move` commands, you need to give the path (start from the top level of the vault folder).
{: .notice--info}

**Tip 3:** When working with text containing spaces, you need to wrap them in quotes. For example, `obsd open "My Note"` or `obsd create "My Note" --content "My note content"`.
{: .notice--info}

**Tip 4:** You can rename files by using the [Move Note]({{ site.baseurl }}{% link docs/commands/move-note.md %}) command which will also update all the links in other notes.
{: .notice--info}
