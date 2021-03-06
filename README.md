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
  sshuttle \
  node \
  yarn \
  ffmpeg \
  gifsicle \
  kubectx
```

### 3. Install ui software
```
brew install \
  homebrew/cask/google-chrome \
  homebrew/cask/visual-studio-code \
  homebrew/cask/hyper \
  homebrew/cask/docker \
  homebrew/cask/jetbrains-toolbox \
  slack \
  telegram \
  transmission \
  spotify \
  azure-data-studio \
  dotnet-sdk \
  1password \
  drawio \
  vlc \
  postman \
  flutter
```

### 4. Other
```
xcode-select --install
```

```
sudo gem install cocoapods
```

```
https://dist.scaleft.com/client-tools/mac/latest/ScaleFT.pkg
```

```
https://getoutline.org/ru/
```

```
git config --global user.name "Dmitrii Kochnev"
git config --global user.email "aurokkez@gmail.com"
```

```
sft enroll --team dodopizza
sft login
sft config rdp.screensize 1440x900
```

```
mkdir -p ~/.ssh && chmod 700 ~/.ssh
sft ssh-config >> ~/.ssh/config
```

1. Install Rider
2. Install DataGrip
3. Add `source /usr/local/share/zsh-autosuggestions/zsh-autosuggestions.zsh` to `~/.zshrc`
4. Change hostname `https://support.apple.com/en-gb/guide/mac-help/mchlp2322/mac`
5. Network preferences, advanced, dns — 8.8.8.8, 8.8.4.4, search domains — legacy.dev.net
