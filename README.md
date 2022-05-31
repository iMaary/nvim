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

### Installing pre-requisites plugins - UBUNTU

#### Tagbar for code navigation requisites
```bash
sudo apt install exuberant-ctags
```

#### COC - Conquer of Completion requisites

###### nodejs
```bash
// might be >= v12.22.12
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

### Installing pre-requisites plugins - MacOS

#### Tagbar for code navigation requisites
```bash
brew install ctags
```

#### COC - Conquer of Completion requisites

###### nvm for install node
```bash
brew install nvm
```

###### nodejs
```bash
// might be >= v12.22.12
nvm install --lts
```
###### set LTS nodejs version

Here is 16 but it can be whatever lts version is installed in your enviroment.
```bash
nvm use 16
```
###### uninstall older nodejs version

Here is 16 but it can be whatever older version is installed in your enviroment.
```bash
nvm uninstall v10.2.0
```

###### clangd for C/C++ programming language
```bash
brew install llvm
```

##### Import the clangd to each file to use, if neccessary - NEOVIM (UBUNTU/MacOS)

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

