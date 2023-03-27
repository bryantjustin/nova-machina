# nova-machina
For setting up a new machine.

## Install Oh My Zsh
```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install Home Brew
1. Open terminal and run: 
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
2. Copy `.zshrc` from this repository to `~/.zshrc`
```bash
cp Downloads/nova-machina/.zshrc ./.zshrc
```
3. Install Cask
```bash
brew install cask
```

# Install Fira Code
```bash
brew tap homebrew/cask-fonts \
brew install font-fira-code
```

# Install Powerline fonts
```bash
# clone
git clone https://github.com/powerline/fonts.git --depth=1
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts
```

# Install applications
```bash
brew install --cask \
    cacher \
    expressvpn \
    google-chrome \
    iterm2 \
    karabiner-elements \
    p4v \
    paragon-ntfs \
    proxyman \
    postman \
    raycast \
    slack \
    spotify \
    sublime-text \
    tower \
    visual-studio-code \
    zoom \
```
