### Install Sublime Text

Now it's time to install [Sublime Text](http://www.sublimetext.com/), a sophisticated text editor for code, markup, and prose.

To get started, download [Sublime Text 3]http://www.sublimetext.com/3) and run the installer. Again, go with the default installation options, unless you really know you want to change something.

Once installed, use the Start Menu to launch Sublime Text 3.

![](http://i.imgur.com/mnR5naJ.png)

Next, navigate to the `Preferences > Settings - User` menu item.

Copy and paste the text that's in the box below into that file.

```
{
  "font_size": 15.0,
  "ensure_newline_at_eof_on_save": true,
  "rulers": [80],
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true,
  "save_on_focus_lost": true
}
```

**WARNING:** Punctuation errors with either curly-brackets, double-quotes, colons, square-brackets, or commas will be highlighted in red. If one of these symbols is missing, Sublime Text will highlight the next closest symbol. Analyze the above example preferences carefully. :eyes:

Remember to save the file and you'll see something like this.

![](https://imgur.com/Gzz7ojR.png)

When you're done, close the file.

### subl

You'll find it insanely useful to open files and directories into Sublime Text from the Terminal.

To get started, run the following command:

If you installed Sublime Text 2:
```
/c/Program\ Files/Sublime\ Text\ 2/sublime_text.exe .bash_profile
```
If you installed Sublime Text 3:
```
/c/Program\ Files/Sublime\ Text/sublime_text.exe .bash_profile
```

Bash's startup file will open in Sublime Text like this:

![](https://i.imgur.com/PAjlVZf.png)
**UPDATE to be .bash_profile**

Create an alias to open Sublime Text from your command line.

If you installed Sublime Text 2, type this:

alias subl="/c/Program\ Files/Sublime\ Text\ 2/sublime_text.exe"
 
If you installed Sublime Text 3, type this:

alias subl="/c/Program\ Files/Sublime\ Text/sublime_text.exe"

Now save this file by pressing CTRL + S on your keyboard.

Exit Sublime Text.

Now, regardless of your Sublime Text version, to verify if Sublime Text is wired up correctly, run the following command:

```
subl ~/.bash_profile
```

And Bash's startup file will open in Sublime Text like this.

![](https://i.imgur.com/PAjlVZf.png)

If Sublime Text launched, then you are good to go. Now close Sublime Text to continue on with this guide.

### Edit .bashrc

Many command line tools, like Git, use the `EDITOR` environment variable to open your preferred text editor.

While Bash's startup file is handy, add the following settings.

```
# Sublime Text
export EDITOR='subl -w'
```

**TIP:** Environment variables, like `EDITOR`, must be written in all capital letters.

Save the file and you'll see something like this.

![](https://i.imgur.com/Ber0ICU.png)

Now, relaunch the Terminal and verify these settings with the following command.

```
echo $EDITOR
```

**TIP:** Environment variables must be written in all capital letters.

And you'll see something like this.

![](https://i.imgur.com/KrRgLm1.png)


### Inspect the PATH

Like most shells, Bash relies on the `PATH` environment variable to specify a set of directories where other commands can be found.

To see the contents of the PATH environment variable, run the following command.

```
echo $PATH
```

**TIP:** Environment variables, like `PATH`, must be written in all capital letters.

And you'll see something like this.

![](https://i.imgur.com/lLcHHTA.png)

### [⇐ Previous](1_terminal.md) | [Next ⇒](3_git.md)
