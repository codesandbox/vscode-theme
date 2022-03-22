# Contributing

Thank you for deciding to contribute to our Visual Studio Code Theme! Please read through the page below that will take you through everything you need to know to land your first contribution. See you in the pull requests!

## Development

### Create a fork

First, create a fork (your own copy) of this repository by clicking on the "Fork" button in the upper right corner of this page.

### Clone

```sh
git clone <YOUR_FORK_URL>
cd vscode-theme
```

### Install locally

To use this extension locally, it must be copied to the Visual Studio Code Extensions folder on your machine.

#### Copy automatically

Use the following command to do that:

```sh
./sync.sh
```

#### Copy manually

```sh
cd vscode-theme
cp -r . ~/.vscode/extensions/codesandbox-theme
```

### Preview

It's always more pleasant to develop when you see your changes take effect in real time. Below you can find the instructions on how to preview your local version of this theme.

1. Open the repository in Visual Studio Code.
1. Click <kbd>F5</kbd> to switch to the "Debugger" section.
1. Click on the "Play" button to run the theme in a separate extension window.
1. In the newly opened VS Code window, press <kbd>CMD + SHIFT + P</kbd>, then type "Color Theme".
1. Choose "CodeSandbox" from the themes list. If you don't see this option in the list, please make sure to [have installed the theme locally](#install-locally).

Editing the theme files under `./themes` will update the running extension window automatically.
