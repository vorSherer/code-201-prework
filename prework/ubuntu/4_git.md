### Install Git

Using APT, you can also install [Git](http://git-scm.com/), the version control system of choice among choosy developers.

Version control systems let programmers share and collaborate on code. With Git, multiple programmers can work on the same files, and Git keeps track of who made what changes, when. Git is usually used with a website, GitHub, that stores code (in "repositories") and lets programmers review and discuss changes before they are added. In short, Git makes everyone's lives easier.

To get started, run the following command.

```
sudo apt-get install -y git
```

Once it finishes, run the following command.

```
git --version
```

And you'll see something like this.

![](https://i.imgur.com/YmUQzF0.png)

### Git Config

Like artists, programmers sign their work. Let's configure Git to sign your commits with your name and email address.

Make sure you sign up for an account at Github [here](https://github.com).

**WARNING:** Before running the following commands, replace `YOUR FULL NAME` and `YOUR EMAIL ADDRESS` with the name and email from [your GitHub account](https://github.com/settings/profile).

```
git config --global user.name 'YOUR FULL NAME'
git config --global user.email 'YOUR EMAIL ADDRESS'
```

The terminal does not send success messages, in order to double check that you have successfully assigned your username and email: 

```
git config --list
```

Your terminal should output the following lines:

```
user.email='YOUR EMAIL ADDRESS'
user.name='YOUR FULL NAME'
```

### Congratulations!

Time for a frosty beverage. :beers:


### [⇐ Previous](3_atom.md) | [README ⇒](../../../../)
