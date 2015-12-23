### Install Homebrew

You may already have Homebrew installed. Let's see if you do. Type

```
which brew
```

If you get an error message, then we need to install it. Follow below to install or skip to Update Homebrew if it is installed.

Now it's time to install [Homebrew](http://brew.sh/), the de facto package manager for OS X. If you've never heard of a package manager, think of it as an App Store of **free** command line programs.

To get started, run the following command.

```
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/install/master/install)"
```

**TIP:** Be sure to agree when asked to install the **XCode CommandLine Tools**. This takes about 30 minutes to download and install on average.


### Update Homebrew

If you've previously installed Homebrew, now's a good time to update it by running the following command.

```
brew update
```

If it's been a while since the last update, you'll see something like this.

![](https://i.imgur.com/OCAX71o.png)

Otherwise, you'll see something like this.

![](https://i.imgur.com/JPB9Gnn.png)

**TIP:** Run this command periodically as Homebrew doesn't auto-update itself. :sweat:


### Verify Homebrew

To verify Homebrew is installed correctly, run the following command.

```
brew doctor
```

And you'll see something like this.

![](https://i.imgur.com/DWfdE3D.png)


### [⇐ Previous](1_terminal.md) | [Next ⇒](3_atom.md)
