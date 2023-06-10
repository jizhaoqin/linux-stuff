# Some Useful Tips When Using Linux

## Commands

- clean up

  - rm -rf "$(brew --cache)" : to remove the cache of brew, like the tar.gz files for installing packages but now useless.
  - ./clean-snap.sh: script to clean snap cache
  - journalctl --vacuum-size=20M: clean log files bigger than 20M
- shells
  - chsh -s $(which zsh) : change shell to zsh (need to logout to take effect)
  - cat /etc/shells : check installed shells
- GUI and tty
  - CTRL+ALT+F1 : lock screen
  - CTRL+ALT+F2 : back to Linux GUI
  - CTRL+ALT+F3 : to tty3
  - CRTL+ALT+Fn : to ttyn
- user management
  - su - username: switch to username, if switch to the same user as current, will reload all the config without closing any windows, which is convenient when adjusting system value.
- system config
  - sudo update-alternatives --config x-terminal-emulator: change default terminal emulator
- C & C++
  - g++ -dM -E -x c++  /dev/null | grep -F __cplusplus: check default compile standard for c++
