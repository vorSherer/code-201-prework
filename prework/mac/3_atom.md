### Install Atom Text Editor

Now it's time to install Atom Text Editor, a sophisticated text editor for code, markup, and prose.

To get started, download [Atom]([Atom](https://atom.io/)) and drag the app icon into your `/Applications` folder.

**TIP:** Remember to eject the disk image after installing the app.

Once installed, launch Atom using Spotlight Search.

### `atom` & `apm` (shell commands)
**atom**

You'll find it insanely useful to open files and directories into Atom from the Terminal.

Navigate to the following menu item in Atom: `Atom->Install Shell Commands` (After you select this option from the menu, Atom will alert you when the commands have completed)

To verify Atom is wired up correctly, run the `atom` command from your terminal.

If Atom opens, you're good to go.

If Atom does not open, please notify an instructor or TA in your class Slack channel.

**apm**

Once you've verified that your `atom` shell command is functional, run the following command in your terminal, from any directory, to install the base packages which will add additional functionality to your editor.

- `apm install open-in-browser minimap highlight-selected linter linter-eslint tree-view-git-status file-icons`

This will install the following packages:
1. Open In Browser: Right-click an HTML file, to open the page in the browser from within Atom
2. Mini-Map: Installs a mini map (useful for seeing your code at a high level) in the right hand column of the editor window
3. Highlight Selected: Highlights all instances of a word or phrase when one instance in double-clicked or cursor-highlighted
1. Linter: Alerts you to any typos or incorrect code syntax, as you type
1. Tree view for git status: Color indicators in your file tree will tell you want files have changed since your last commit
1. File Icons: Your tree view will identify file types with an appropriate icon 

### Associate Atom with Git

It's important to establish a default editor with Git, as it's the program that will be used to open up all of your files.

Type the following command in your terminal:
`git config --global core.editor "atom --wait"`


### [⇐ Previous](2_homebrew.md) | [Next ⇒](4_git.md)
