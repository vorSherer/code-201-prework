### Install Atom Text Editor

It's time to install <a href="http://atom.io" target="_blank">Atom</a>, a sophisticated text editor for code, markup and prose.

To get started, run the following command in your terminal to check your operating system’s type:

```
uname -m
```

If your computer is an i386 system, you will not be able to install and use Atom. Please notify an instructor or TA in the Slack channel, and we will help coordinate installing another very similar text editor.

Currently only a 64-bit version is available.

Download atom-amd64.deb from the <a href="https://github.com/atom/atom/releases/latest" target="_blank">Atom releases page</a>.
Run `sudo dpkg --install atom-amd64.deb` on the downloaded package.

Once installed, launch Atom using Spotlight Search.

### `atom` & `apm` (shell commands)

You'll find it insanely useful to open files and directories into Atom from the Terminal.

To verify Atom is wired up correctly, run the following command from your terminal.

```
atom
```
If Atom opens, you're good to go.

If Atom does not open, please notify an instructor or TA in your class Slack channel.

### Associate Atom with Git

It's important to establish a default editor with Git, as it's the program that will be used to open up all of your files.

Type the following command in your terminal:
```
git config --global core.editor "atom --wait"
```

### Congratulations!

Time for a frosty beverage. :beers:

### [⇐ Previous](3_git.md) | [README ⇒](../../../../)
