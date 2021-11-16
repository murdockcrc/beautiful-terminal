# Run

## Initial install

Run this script. If you did not have oh my zsh installed, you will have to run this twice, since the installation of oh my zsh stop the execution of the script.

```
bash -c "$(curl -fsSL https://raw.githubusercontent.com/murdockcrc/beautiful-terminal/master/configure.sh)"
```

## Install Oh My Posh
```
zsh -c "$(curl -fsSL https://github.com/murdockcrc/beautiful-terminal/raw/master/oh-my-posh.sh)"
```

You may have to execute this line manually in the terminal:

```
eval "$(oh-my-posh --init --shell zsh --config ~/.poshthemes/jandedobbeleer.omp.json)"
```

## Install colorls

```
zsh -c "$(curl -fsSL https://github.com/murdockcrc/beautiful-terminal/raw/master/colorls.sh)"
```