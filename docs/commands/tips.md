---
layout: single
title: "General Tips"
sidebar:
    nav: "docs"
---

**Tip 1:** You don't have to manually navigate to the vault directory unless you want to. All commands will function as if you're already in the vault directory. However, if you need to access it, you can use the [Print Default Vault]({{ site.baseurl }}{% link docs/commands/print-default-vault.md %}) command to obtain the path.
{: .notice--info}

**Tip 2:** When working with text containing spaces, you need to wrap them in quotes. For example, `obs open "My Note"` or `obs create "My Note" --content "My note content"`.
{: .notice--info}

**Tip 3:** You can rename files by using the [Move Note]({{ site.baseurl }}{% link docs/commands/move-note.md %}) command which will also update all the links in other notes.
{: .notice--info}