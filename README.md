# mac-setup
List when setting up new mac

## Setup system preferences
- [ ] Show all files
  - [ ] `defaults write com.apple.finder AppleShowAllFiles true;killall Finder`
- [ ] Keyboard and Trackpad
  - [ ] Increase trackpad speed(System Preferences -> Trackpad -> Point&Click)
  - [ ] Increase keyboard key repeat speed(System Preferences -> Keyboard -> Keyboard)
  - [ ] Decrease keyboard key delay(System Preferences -> Keyboard -> Keyboard)
  - [ ] Change spotlight shortcut to `⌥ + space`
  - [ ] Change `caps lock` key to `control` 
- [ ] Dock
  - [ ] Cut animation runnning application(System Preferences -> Dock&Menu bar)
  - [ ] Dock automatically show/hide(System Preferences -> Dock&Menu bar)
  - [ ] Delete all icon from Dock
- [ ] Menu bar
  - [ ] Hide date and day of week(System Preferences -> Dock&Menu bar)
  - [ ] Hide Spotlight from menu bar(System Preferences -> Dock&Menu bar)
  - [ ] Hide all applications from menu bar(System Preferences -> Dock&Menu bar)
  - [ ] Menu bar automatically show/hide(System Preferences -> Dock&Menu bar)
- [ ] Security & Privacy
  - [ ] Require password `immediately`
  - [ ] Turn on FileVault
  - [ ] Turn on Firewall
- [ ] Cut animations
  - [ ] `defaults write NSGlobalDomain NSAutomaticWindowAnimationsEnabled -bool false`
  - [ ] `defaults write com.apple.finder DisableAllAnimations -boolean true; killall Finder`
- [ ] Enable zoom for `control + scrolling`(System Preferences -> Accessibility -> Zoom)

## Terminal
- [ ] Install [Homebrew](https://brew.sh/)
- [ ] Install [Brewfile](./Brewfile) `$ brew bundle install`
- [ ] Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
- [ ] Install [powerline-shell](https://github.com/b-ryan/powerline-shell)
- [ ] Setup [Meslo powerline font](https://github.com/powerline/fonts)
- [ ] Setup [Dotfiles](https://github.com/kotalab/dotfiles)

## Github
- [ ] Login Github
```shell
$ gh auth login
```

## Alfred
- [ ] Enable shortcut `CMD + space`
- [ ] Activate Powerpack
- [ ] Sync settings from Alfred repo(https://github.com/kotalab/Alfred)

## Hazel
- [ ] Setup license and rule from Dropbox
