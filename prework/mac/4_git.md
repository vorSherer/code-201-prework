### Install Git

Check if you already have Git installed by running the following command.

```
git --version
```

You'll see something like this if it's installed. If it is, skip to Git Config, otherwise continue below.

![](https://i.imgur.com/jBSs1qR.png)

Figure out what version of OS X you are running. From the Apple menu, choose About This Mac. The version of OS X installed appears directly below “OS X.” Click the version number to see the build number. You can also use [System Information](https://support.apple.com/en-us/HT203001) to find these numbers.

![](https://support.apple.com/library/content/dam/edam/applecare/images/en_US/osx/yos_build_version.png)

If you are running:

- 10.6 Snow Leopard: download and install this: [git-*-snow-leopard](http://sourceforge.net/projects/git-osx-installer/files/git-2.3.5-intel-universal-snow-leopard.dmg/download)
	
- 10.7 Lion: download and install this [git-*-snow-leopard](http://sourceforge.net/projects/git-osx-installer/files/git-2.3.5-intel-universal-snow-leopard.dmg/download)
	
- 10.8 Mountain Lion: download and install this [git-*-snow-leopard](http://sourceforge.net/projects/git-osx-installer/files/git-2.3.5-intel-universal-snow-leopard.dmg/download)
	
- 10.9 Mavericks: download and install this [git-*-mavericks](http://sourceforge.net/projects/git-osx-installer/files/git-2.5.3-intel-universal-mavericks.dmg/download)
	
- 10.10 Yosemite: continue below

Now go [here](http://git-scm.com/download/mac) to install Git, the version control system of choice among choosy developers.

Version control systems let programmers share and collaborate on code. With Git, multiple programmers can work on the same files, and Git keeps track of who made what changes, when. Git is usually used with a website, GitHub, that stores code (in "repositories") and lets programmers review and discuss changes before they are added. In short, Git makes everyone's lives easier.

Once it is fully installed, open Terminal and run the following command.

```
git --version
```

And you'll see something like this.

![](https://i.imgur.com/jBSs1qR.png)


### Git Config

You're on the home stretch now! :racehorse:

Like artists, programmers sign their work. Let's configure Git to sign your commits with your name and email address.

Sign up for an account at Github [here](https://github.com).

**WARNING:** Before running the following commands, replace `YOUR FULL NAME` and `YOUR EMAIL ADDRESS` with the name and email from [your GitHub account](https://github.com/settings/profile).

```
git config --global user.name 'YOUR FULL NAME'
git config --global user.email 'YOUR EMAIL ADDRESS'
```

### Congratulations!

Time for a frosty beverage. :beers:


### [⇐ Previous](3_sublime_text.md) | [README ⇒](../../../../)
