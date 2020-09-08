# mac-setup
List when setting up new mac

## Github
- [ ] Create rsa key and add ssh key [Github](https://github.com/settings/keys)
```shell
$ cd ~/.ssh
$ ssh-keygen -t rsa
```
- [ ] Login [Github](https://github.com)

## Terminal
- [ ] Install [Homebrew](https://brew.sh/)
- [ ] Install [Brewfile](./Brewfile) `$ brew bundle install`
- [ ] Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
- [ ] Install [powerline-shell](https://github.com/b-ryan/powerline-shell)
- [ ] Setup [Meslo powerline font](https://github.com/powerline/fonts)
- [ ] Setup [Dotfiles](https://github.com/kotalab/dotfiles)

## Alfred
- [ ] Enable shortcut `CMD + space`
- [ ] Activate Powerpack
- [ ] Sync settings from Alfred repo(https://github.com/kotalab/Alfred)

## Hazel
- [ ] Setup license and rule from Dropbox

## Other
- [ ] Show all files
  - [ ] `defaults write com.apple.finder AppleShowAllFiles true;killall Finder`
- [ ] Keyboard and Trackpad
  - [ ] Increase trackpad speed(System Preferences -> Trackpad -> Point&Click)
  - [ ] Increase keyboard key repeat speed(System Preferences -> Keyboard -> Keyboard)
  - [ ] Decrease keyboard key delay(System Preferences -> Keyboard -> Keyboard)
  - [ ] Change spotlight shortcut to `⌥ + space`
- [ ] Dock
  - [ ] Cut animation runnning application(System Preferences -> Dock)
  - [ ] Dock automatically show/hide(System Preferences -> Dock)
  - [ ] Delete all icon from Dock
- [ ] Security & Privacy
  - [ ] Require password `immediately`
  - [ ] Turn on FileVault
  - [ ] Turn on Firewall
- [ ] Cut animations
  - [ ] `defaults write NSGlobalDomain NSAutomaticWindowAnimationsEnabled -bool false`
  - [ ] `defaults write com.apple.finder DisableAllAnimations -boolean true; killall Finder`
- [ ] Enable zoom for `control + scrolling`(System Preferences -> Accessibility -> Zoom)
