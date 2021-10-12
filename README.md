# myVimEditor
Exportable Vim Editor (Autocompletion, Syntax Highlighting, Linter, Directory...) which utilizes Vundle.

## Installation

**1.** Install Vim (Optional)

``` console
sudo apt install vim
```
**2.** Run Bash Script

If Linux AMI / Redhat / OSX:

``` console
bash makeVimAWS.sh
```
If Debian / Ubuntu

``` console
bash makeVimPi.sh
```
**2.** Open Vim and type ***:PluginInstall***

**Important: If Vim version on OS doesn't support python 2/3**

1.

``` console
sudo apt install libncurses5-dev
```
2. 

``` console
bash compileVim.sh
```
