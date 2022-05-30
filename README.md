## NeoVim Personalization

This repository was created to pre-config the WSL/Ubuntu enviroment
for download the Neovim Code Editor. Also, it sets the plugins and
personalization to make easily the programmer's life.

#### Installing neovim
```bash
sudo apt install neovim
```
#### Checking the neovim version
```bash
nvim --version
```

### Installing pre-requisites plugins

#### Tagbar for code navigation requisites
```bash
sudo apt install exuberant-ctags
```

#### COC - Conquer of Completion requisites

###### nodejs
```bash
\\ might be >= v12.22.12
sudo apt-get install nodejs
```

###### npm
```bash
sudo apt-get install npm
```

###### yarn
```bash
sudo apt-get install yarn
```

###### clangd for C/C++ programming language
```bash
sudo apt-get install clangd-12
```

##### Import the clangd to each file to use, if neccessary

###### If you're programming in C/C++ language
```bash
:CocInstall coc-clangd
```
###### If you're programming in Python language
```bash
:CocInstall coc-python
```

### Downloading Nerd Fonts

#### Developer Icons requisites

1 - Install the Hack Nerd Font in [Nerd Fonts](https://www.nerdfonts.com/font-downloads) <br>
2 - Extract .zip folder <br>
3 - Install each compatible font into the folder <br>
4 - Set font on Terminal to Hack NF and save! <br>

