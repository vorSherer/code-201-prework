### Install Sublime Text

Using APT, it's time to install [Sublime Text 3](http://www.sublimetext.com/), a sophisticated text editor for code, markup and prose.

To get started, run the following command.

```
sudo apt-get install -y sublime-text-installer
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

### [⇐ Previous](2_apt.md) | [Next ⇒](4_git.md)
