### Install Sublime Text

Now it's time to install [Sublime Text](http://www.sublimetext.com/), a sophisticated text editor for code, markup, and prose.

To get started, download [Sublime Text 3](http://www.sublimetext.com/3) and drag the app icon into your `/Applications` folder.

**TIP:** Remember to eject the disk image after installing the app.

Once installed, use Spotlight to launch Sublime Text 3.

![](https://i.imgur.com/rrHkcoy.jpg)

Next, navigate to the `Sublime Text 3 > Preferences > Settings - User` menu item.

Ensure the file contains the following preferences.

```
{
  "font_size": 18.0,
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

![](https://i.imgur.com/W7P51S3.png)

When you're done, close the file.


### [⇐ Previous](1_terminal.md) | [Next ⇒](3_git.md)
