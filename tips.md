# Some Useful Tips when Using Linux

## Homebrew

- commands:
  - rm -rf "$(brew --cache)" : to remove the cache of brew, like the tar.gz files for installing packages but now useless.
  - journalctl --vacuum-size=20M : to clear the log files bigger than 20M
