### Install VSCode Text Editor

Now it's time to install VSCode Text Editor, a sophisticated text editor for code, markup, and prose.

To get started, download [VSCode](https://code.visualstudio.com/download) and put the application in your Applications folder.

[VSCode's documentation](https://code.visualstudio.com/docs) is excellent. Review it now to familiarize yourself with the basics.

**TIP:** Remember to eject the disk image after installing the app.

Once installed, launch VSCode using Spotlight Search, or navigate to the Applications directory.

### Install shell commands

You'll find it useful to open files and directories into VSCode from the Terminal.

Navigate to the following menu item in VSCode: `VSCode->Install Shell Commands` (After you select this option from the menu, VSCode will alert you when the commands have completed)

To verify VSCode is wired up correctly, run the `code` command from your terminal.

If VSCode opens, you're good to go.

If VSCode does not open, try the above process again. If it still does not work, we will remedy it during lab on the first day of class.

### Associate VSCode with Git

It's important to establish a default editor with Git, as it's the program that will be used to open up all of your files.

Type the following command in your terminal:
`git config --global core.editor "code --wait"`

### [⇐ Previous](2_homebrew.md) | [Next ⇒](4_git.md)
