# macbook-setup

### 1. Brew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

### 2. Install formulas
```
brew install \
  git \
  terraform \
  doctl \
  azure-cli \
  kubectl \
  zsh-autosuggestions \
  dotnet-sdk
```

### 3. Install casks
```
brew cask install \
  homebrew/cask/google-chrome \
  homebrew/cask/visual-studio-code \
  homebrew/cask/hyper \
  homebrew/cask/docker \
  homebrew/cask/jetbrains-toolbox \
  slack \
  telegram \
  transmission
```

### 4. Other, automatic
```
xcode-select --install
```

### 5. Other, manual
```
https://dist.scaleft.com/client-tools/mac/latest/ScaleFT.pkg
```

### 6. Other actions
1. Install Rider
2. Install DataGrip
3. Add `source /usr/local/share/zsh-autosuggestions/zsh-autosuggestions.zsh` to `~/.zshrc`
4. Change hostname `https://support.apple.com/en-gb/guide/mac-help/mchlp2322/mac`
