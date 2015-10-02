### Install Sublime Text

It's time to install [Sublime Text](http://www.sublimetext.com/), a sophisticated text editor for code, markup and prose.

To get started, run the following command in your terminal to check your operating system’s type:

```
uname -m
```
Depending on whether your operating system's type is i386 or x64, follow the guide below.

For i386, run this command:

```
cd ~
wget http://c758482.r82.cf2.rackcdn.com/sublime-text_build-3083_i386.deb
```

For x64, run this command:

```
cd ~
wget http://c758482.r82.cf2.rackcdn.com/sublime-text_build-3083_amd64.deb
```

Now, regardless of your operating system type, run the following command to move the files:

```
sudo mv Sublime\ Text\ 3 /opt/
```
Finally, run this command to create a symbolic link. This will allow you to launch Sublime Text from the Terminal.

```
sudo ln -s /opt/Sublime\ Text\ 3/sublime_text /usr/bin/subl
```

Once installed, use the Dash to launch Sublime Text.

![](https://i.imgur.com/urq6WwX.png)


Next, navigate to the `Preferences > Settings - User` menu item.

Copy the settings below and paste them into the file. These are basic preferences to get you started.

```
{
  "font_size": 18.0,
  "ensure_newline_at_eof_on_save": true,
  "rulers": [80],
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true,
  "update_check": false,
  "save_on_focus_lost": true
}
```

**WARNING:** Punctuation errors with either curly-brackets, double-quotes, colons, square-brackets, or commas will be highlighted in red. If one of these symbols is missing, Sublime Text will highlight the next closest symbol. Analyze the above example preferences carefully. :eyes:

Remember to save the file and you'll see something like this.

![](https://i.imgur.com/dGUbd34.png)

When you're done, close the file.

### subl

You'll find it insanely useful to open files and directories into Sublime Text from the Terminal.

To verify Sublime Text is wired up correctly, run the following command in Terminal:

```
subl 
```

If the program Sublime Text opens, then you're good to go.


### [⇐ Previous](2_apt.md) | [Next ⇒](4_git.md)
