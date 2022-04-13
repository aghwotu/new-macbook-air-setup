# new-macbook-air-setup
Documenting the resources I use to setup my MacBook M1 Air for development. The tools I need are:
- [Homebrew](https://brew.sh/): a package manager for macOS
- [Git](https://git-scm.com/download/mac)
- [Node.js](https://nodejs.org/) and [NVM](https://github.com/nvm-sh/nvm). NVM is a package manager to manage different Nodejs versions
- [iTerm](https://iterm2.com/downloads.html): macOS terminal replacement
- [Oh My Zsh](https://ohmyz.sh/): terminal shell


## Installing Homebrew
[Homebrew](https://brew.sh/) is a package manager for macOS
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Installing NVM and Node.js
For this I installed the Node Version Manager - NVM. This tutorial - [How to Install Node on a MacOS, Linux, or Windows Machine Using NVM](https://www.freecodecamp.org/news/how-to-install-node-in-your-machines-macos-linux-windows/) - was a good guide. It also contains a guide on how to uninstall NVM.

> **NOTICE**: Node.js may revert to the first installed version.
I ran into an issue where the Node.js version was reverting to the version that was first installed with the Node Version Manager. This [Stackoverflow Answer](https://stackoverflow.com/a/70356014/7935926) was helpful. You can also check the other answers if you have this challange too.


## Uninstalling Node.js 
In the event that you installed Node.js without a version manager like NVM:
- [How To Uninstall Node JS and (NPM) from MacOS?](https://www.positronx.io/how-to-uninstall-node-js-and-npm-from-macos/)
- [Steps To Uninstall NodeJS](https://stackoverflow.com/a/70507486/7935926)

