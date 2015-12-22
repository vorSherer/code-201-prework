### Update APT

Now that your Terminal is setup, it's time to update Ubuntu's **Advanced Packaging Tool** or [APT](https://help.ubuntu.com/lts/serverguide/apt-get.html) for short. If you've never heard of a package manager, think of it as an App Store of **free** command line programs.

To get started, run the following commands. Each line is its own commmand, so copy, paste, and run them one at a time.

```
sudo add-apt-repository -y ppa:git-core/ppa
sudo apt-get update
```

**TIP:** This may require your account password which **will not** appear on the screen as you type.

These commands tell APT where to look for certain files (Git). We'll use them in the next step.

### [⇐ Previous](1_terminal.md) | [Next ⇒](3_atom.md)
