# VSCode Vim Settings 

```
Some of my commands use `Cmd`, but this key does not exist on Windows.
So you might need to be cautious here and see what VSCode on Windows uses.
```

This is the repo for my collections of useful Vim shortcuts and bindings for VSCode.

My goal is to keep it as simple as possible, so we can stick with Vim Motions for the most part.

- `` settings.json ``: This is for `Preferences: Open User Settings (JSON)` 

    - **NOTE**: settings.json inside .vscode is just for me to format my repo, not relevant to our Vim settings
 
    - You can search for this setting by using `` Cmd + Shift + P ``

- `` keybindings.json ``: This is for `Preferences: Open Keyboard Shortcuts (JSON)`

## VSCode Shortcuts for Command Palette

- `` Cmd + P ``: Open global file search panel

- `` Cmd + Shift + P ``: Open command search panel

    - Here, you can search for settings and many other things too!

## VSCode Shortcuts for Terminals

- `` Ctrl + ` ``: Open terminal (**Default**)

- `` Ctrl + Shift + ` ``: Create new terminal (Must be set on our own)

    - Search for `Terminal: Create New Terminal` and set the shortcut yourself if you want. But the newest `keybindings.json` should already include it

- `` Ctrl + Shift + Backspace ``: Delete terminal (Must be set on our own)

    - Search for `Terminal: Kill the Active Terminal Instance` and set the shortcut yourself if you want. But the newest `keybindings.json` should already include it

- `` Cmd + Shift + [ `` or `` Cmd + Shift + ] ``: Navigate between terminals (**Default**)

## VSCode Shortcuts on Tabs

- `` Cmd + Shift + [ `` or `` Cmd + Shift + ] ``: Navigate between opened tabs (**Default**)

- `` Ctrl + Tab `` or `` Ctrl + Shift + Tab ``: Navigate virtually between opened tabs (**Default**)

## VSCode Shortcuts for Editor and Explorer

- `` Ctrl + e ``: Switch focus among Editor and Explorer

  - Should be set with the newest `keybindings.json`

- `` Ctrl + Shift + e ``: Very similar to above shortcut but don't close the Explorer

## Resources to learn Vim Motions

- For some references, I practiced Vim by doing `vimtutor` on Mac Terminal. I think this exists on Windows too.

- I also watch some parts of the series `Vim as your editor` on Youtube by `ThePrimeagen`

## Cool extensions with VS Code

- Beared Theme: For cool themes

- Error Lens: Improve highlighting of errors and warnings

- Material Icon Theme: For icon themes