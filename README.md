# dotfiles

The `.dotfiles` directory for my system. 

## Requirements

Ensure you have the following installed on your system:

### Git

```bash
sudo apt install git
```

### Stow

[GNU Stow](https://www.gnu.org/software/stow)

```bash
sudo apt install stow
```

## Installation

Clone this repositpry to your `~` (`$HOME`) directory:

```bash
cd ~
git clone git@github.com:rotemhoresh/dotfiles.git .dotfiles
```

Then use Stow to create the symlinks:

```bash
cd ~/.dotfiles && stow .
``` 
