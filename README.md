### Installation

Clone the repository and run the deploy script.

    git clone --recursive https://github.com/dwieeb/dotfiles.git ~/.dotfiles
    ~/.dotfiles/bin/deploy.sh

### Updating

Pull recursively, and then update submodules.

    git pull --recurse-submodules
    git submodule init
    git submodule update
