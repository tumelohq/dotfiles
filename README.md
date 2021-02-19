# dotfiles

A repo with some useful dotfiles and software installation scripts to get `Tumelo` workstations up and running fast.

## Installing the basic software

The following section explains how to install the basic software that you may use a 

To install the basic steps you'll use at Tumelo copy the following bit of code into a terminal. You can open the `Terminal` app by searching by clicking on the eyeglass in the top right. Once opened, copy the below lines of code

```shell
xcode-select --install
git clone https://github.com/tumelohq/dotfiles.git
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
cd dotfiles/base
brew bundle

```
