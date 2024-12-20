# VSCode Vim Settings

```
Warning:

Some of my commands use `cmd` key, but this key does not exist on Windows.
So you might need to be cautious here and see what VSCode on Windows uses.
```

This is the repo for my collections of useful Vim shortcuts and bindings for VSCode.

My goal is to keep it as simple as possible, so we can stick with Vim Motions for the most part.

But of course, I have added some of my preferences for VSCode.

- `settings.json`: This is for `Preferences: Open User Settings (JSON)`

- `keybindings.json`: This is for `Preferences: Open Keyboard Shortcuts (JSON)`

- You can search for these settings by using `Cmd + Shift + P`

## VSCode Shortcuts for Command Palette

- `Cmd + p`: Open global file search panel

- `Cmd + Shift + p`: Open command search panel

  - Here, you can search for settings and many other things too!

- `Cmd + Shift + r`: Open most recently used editors

## VSCode Shortcuts for Terminals

- `` Ctrl + ` ``: Open terminal

- `` Ctrl + Shift + ` ``: Create new terminal

- `Ctrl + Shift + Backspace`: Delete terminal

- `Cmd + Shift + [` / `Cmd + Shift + ]`: Navigate between terminals

## VSCode Shortcuts on Tabs

- `Cmd + Shift + [` / `Cmd + Shift + ]`: Navigate between opened tabs

- `Ctrl + Tab` / `Ctrl + Shift + Tab`: Navigate virtually between opened tabs

## VSCode Shortcuts for Side Panels

- `Cmd + Shift + e`: Switch focus among current Editor and Explorer

- `Cmd + b`: Toggle Explorer

- `Cmd + Shift + b`: Open tabs (open editors) side panel

- `Cmd + Shift + x`: Focus Extensions panel

- `Cmd + Shift + g`: Focus Git panel

- `Cmd + Shift + c`: Close all panels on two sides

## VSCode Shortcuts for Panes

- `Ctrl + h`: Focus left pane
- `Ctrl + j`: Focus bottom pane
- `Ctrl + k`: Focus top pane
- `Ctrl + l`: Focus right pane

## VSCode Shortcuts for File Tree

- `a`: New file
- `x`: Cut file
- `y`: Copy file
- `p`: Paste file
- `c`: Collapse all folders
- `r`: Refresh file explorer
- `/`: Find file/folder in explorer

## VSCode Shortcuts for Codeium

- `Alt + f`: Hide Codeium suggestions
- `Alt + Tab`: Accept Codeium suggestions
- `Alt + [` / `Alt + ]`: Navigate between Codeium suggestions
- `Alt + \`: Trigger Codeium suggestions

## Vim keybindings

- `<leader>d` = Permanently delete instead of saving deleted text into Vim register

### Normal mode

- `jk` = Escape
- `K` = Show definition under cursor
- `]d` / `[d` = Next/previous diagnostic
- `]h` / `[h` = Next/previous git change
- `<leader>nh` = No highlight after searching
- `<leader>hb` = Toggle git blame
- `<leader>hr` = Revert selected git ranges
- `<leader>rn` = Rename symbol
- `<leader>pc` = Copy file path
- `<leader>pa` = Toggle bookmarks
- `<leader>pl` = Toggle bookmark labels (naming)
- `<leader>po` = Focus bookmarks sidebar
- `<leader>sv` = Split editor vertically
- `<leader>sh` = Split editor horizontally
- `<leader>sm` = Maximize current editor view

### Visual mode

- `<leader>p` = Paste and continue with the same text instead of default vim behavior for pasting
- `<` = Decrease indentation and keep visual mode
- `>` = Increase indentation and keep visual mode

## Resources to learn Vim Motions

- For some references, I practiced Vim by doing `vimtutor` on Mac Terminal. I think this exists on Windows too.

- I also watch some parts of the series `Vim as your editor` on Youtube by `ThePrimeagen`

## Cool extensions with VS Code

- Vim: Vim emulation for VSCode

- For cool themes:

  - Bearded Theme
  - Kanagawa
  - Catpuccin

- Material Icon Theme: For icon themes

- Bookmarks: For bookmarks

- Codeium: Free AI coding autocomplete

- Markdown All in One: For better support for markdown file editing
