# Development environment configs

## Visual Studio Code 

### Plugins

```bash
code --install-extension christian-kohler.npm-intellisense
code --install-extension christian-kohler.path-intellisense
code --install-extension dbaeumer.vscode-eslint
code --install-extension eamodio.gitlens
code --install-extension eg2.vscode-npm-script
code --install-extension esbenp.prettier-vscode
code --install-extension jasonnutter.search-node-modules
code --install-extension jawandarajbir.react-vscode-extension-pack
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-vscode-remote.remote-containers
code --install-extension xabikos.JavaScriptSnippets
code --install-extension xabikos.ReactSnippets
```

### Regenerate list

```bash
code --list-extensions | xargs -L 1 echo code --install-extension
```


### Keybindings

```json
// Place your key bindings in this file to override the defaults
[
  {
    "key": "ctrl+alt+[",
    "command": "workbench.action.navigateBack"
  },
  {
    "key": "ctrl+alt+]",
    "command": "workbench.action.navigateForward"
  }
]
```

## vim

```bash
cp vimrc ~/.vimrc
```

## zsh

Overwrite relevant parts in ~/.zshrc.
