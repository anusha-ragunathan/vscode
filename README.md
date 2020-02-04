my vscode config

- Prefer Folders (vs Workspaces)
- User settings in ~/.config/Code/User/settings.json to customize config
- Key bindings in ~/.config/Code/User/keybindings.json to customize keybindings
- User code snippets at ~/.config/Code/User/snippets/go.json to add custom snippets

Debug:
If extension doesnt work, look at Tools-> Toggle Developer Tools -> Console
Plenty of useful info.
eg. if extension crashed, panic stack available there.
reinstall an extension by
```cd ${HOME}/.vscode/extensions/ms-vscode.go-{your  version}
npm install```
