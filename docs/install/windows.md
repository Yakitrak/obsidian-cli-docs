---
layout: single
title: "Windows Installation"
sidebar:
  nav: "docs"
---

#### Step 1: Download the latest release

---

Visit the [releases page](https://github.com/Yakitrak/obsidian-cli/releases/latest) and download the most recent release for your system architecture. Choose between `obsidian-cli_x.x.x_windows_amd64.tar.gz` or `obsidian-cli_x.x.x_windows_386.tar.gz`, depending on your system. You can determine your system architecture by running `systeminfo` in a command prompt.

#### Step 2: Extract the file

---

Extract the downloaded file to a folder of your choice using 7zip or WinRAR.

#### Step 3: Set the PATH environment variable

---

Locate the extracted `.exe` file and run it from the command prompt. To make the program accessible from any location on your system, add the folder containing the file to your PATH environment variable. You can refer to [this guide](https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/) for instructions.

#### Step 4: Confirm installation

---

```zsh
obs --version
```

After installation, you can now run `obs` from anywhere on your system. To set up your default vault, please refer to [Set Default Vault]({{ site.baseurl }}{% link docs/commands/set-default-vault.md %}).
