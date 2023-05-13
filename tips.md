# Some Useful Tips when Using Linux

## Homebrew

- commands:
  - rm -rf "$(brew --cache)" : to remove the cache of brew, like the tar.gz files for installing packages but now useless.
  - journalctl --vacuum-size=20M : to clear the log files bigger than 20M
  - chsh -s $(which zsh) : change shell to zsh (need to logout to take effect)
  - cat /etc/shells : check installed shells
  - CTRL+ALT+F1 : lock screen
  - CTRL+ALT+F2 : back to Linux GUI
  - CTRL+ALT+F3 : to tty3
  - CRTL+ALT+Fn : to ttyn
  - su - username: switch to username, if switch to the same user as current, will reload all the config without closing any windows, which is convenient when adjusting system value.
  - sudo update-alternatives --config x-terminal-emulator: change default terminal emulator
