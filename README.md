# Basic setup

## WSL

```
wsl --install
```

## Update Linux

```
sudo apt-get update
sudo apt-get upgrade -y
```

# Setting up WSL

## Set the beautiful terminal

Run this script. If you did not have oh my zsh installed, you will have to run this twice, since the installation of oh my zsh stop the execution of the script.

```
bash -c "$(curl -fsSL https://raw.githubusercontent.com/murdockcrc/beautiful-terminal/master/configure.sh)"
```

## Install Oh My Posh
```
zsh -c "$(curl -fsSL https://github.com/murdockcrc/beautiful-terminal/raw/master/oh-my-posh.sh)"
echo 'eval "$(oh-my-posh --init --shell zsh --config ~/.poshthemes/jandedobbeleer.omp.json)"' >> ~/.zshrc
```

## Install colorls

```
zsh -c "$(curl -fsSL https://github.com/murdockcrc/beautiful-terminal/raw/master/colorls.sh)"
```

## Install fonts

https://ohmyposh.dev/docs/installation/fonts

Assign the installed font to the WSL terminal

# VScode extensions

* [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
* [ESLint](https://github.com/Microsoft/vscode-eslint)
* [Prettier](https://github.com/prettier/prettier-vscode)
* [Vue](https://github.com/LiuJi-Jim/vscode-vue)
* [Azure CLI tools](https://github.com/Microsoft/vscode-azurecli)
* [Azure Resource Manager tools](https://github.com/Microsoft/vscode-azurearmtools)
* [Open API Editor](https://github.com/42Crunch/vscode-openapi)
