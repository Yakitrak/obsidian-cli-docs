---
layout: single
title: "Windows Installation"
sidebar:
  nav: "docs"
---

#### Step 1: Download the latest release
---
Go to [the releases page](https://github.com/Yakitrak/obsidian-cli/releases/latest) and download the latest release. You
will need either:

- `obsidian-cli_x.x.x_windows_amd64.tar.gz`
- `obsidian-cli_x.x.x_windows_386.tar.gz`

This will be depending on your system architecture. You can find this out by running `systeminfo` in a command prompt.

#### Step 2: Extract the archive
---
Extract the archive to a folder of your choice. You can do this by using 7zip or WinRAR.

#### Step 3: Set the PATH environment variable
---
You will see the extracted file `.exe`. You can now run this file from the command prompt. To make the program available from anywhere, you can add the folder to your PATH environment variable. You can do this
by following [this guide](https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/). 

#### Step 4: Confirm installation 
---

```zsh
obs version
```

Now you can
run `obs` from anywhere on your system. Firstly set up your default vault by going
to [Set Default Vault](/docs/commands/set-default-vault/)
        