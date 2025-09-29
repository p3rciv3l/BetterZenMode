# BetterZenMode
A better version of Cursor's ZenMode. Allows users to easily hide nearly every UI element with a simple keyboard shortcut.

## Installation and Setup
1. Download the `better_zen_mode.vsix` file
2. In Cursor, open the command search bar (⌘ + Shift + P)
3. Type "Install from VSIX" and click the first option
4. Open the `better_zen_mode.vsix` file
5. Add these keybindings to your `keybindings.json` file (likely located at `~/Cursor/User/keybindings.json`):

```json
{
  "key": "cmd+shift+a",
  "command": "cursorToggleAll.toggle"
},
{
  "key": "cmd+shift+f",
  "command": "cursorToggleTabs.toggle"
},
{
  "key": "cmd+shift+t",
  "command": "cursorToggleTopbar.toggle"
},
{
  "key": "cmd+shift+n",
  "command": "cursorToggleNotebookToolbar.toggle"
}
```

## Usage
- **⌘/Ctrl + Shift + A** - Toggle everything
- **⌘/Ctrl + Shift + F** - Toggle file tabs
- **⌘/Ctrl + Shift + T** - Toggle toolbar  
- **⌘/Ctrl + Shift + N** - Toggle notebook toolbar