# Minhas configurações do Oh-My-Zsh

## Instalação do Oh-My-Zsh

```sh
sudo apt install zsh 
```

```sh 
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

```

Referencia: https://pt.linux-console.net/?p=29502


## Install zsh-autosuggestions

```sh
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions

```

## Install zsh-syntax-highlighting

```sh
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting

```


Adicinar em `~\.zshrc`

`plugins=(git zsh-autosuggestions zsh-syntax-highlighting)`

