# VSC Open in Sublime Merge

Adds a command for opening the current project in [Sublime Merge](https://www.sublimemerge.com/).

- If there is a file open, it will open the git repo for that file
- If it is a workspace, it will ask you what folder you would like to open
- It will automatically find the best git repo to open

## Install

Run the following in the command palette:

```shell
ext install vscode-open-in-sublime-merge
```

## Usage

It adds 1 command to the command palette and 1 item to the context menu:

```js
'Open in Sublime Merge' // Open the current project in Sublime Merge
```

## Hints

Map `Open in Sublime Merge` action to this extension, add this to your `keybindings.json` file:

```json
  { "key": "⌘⌃S", "command": "openInSublimeMerge.open" }
``````

## License

MIT © Craig Morris
