# setup-macos-webdev-steps

## Disclaimer
These steps describe how to setup comfortable environment for web dev on MacOS.
I wrote this manual like a reminder for my own purposes mostly, when I need to setup environment from scratch, but anyway, feel free to use it / fork or ask questions if you'll have :)

## Table of Contents
- [Environment](#environment)
- - [iTerm2](#iterm2)
- - - [Fix option arrow](#arrows-navigation)
- - - [Restore iTerms2 tabs after restart](#restore-tabs)
- - [Xcode dev tools](#xcode-dev-tools)
- - [nvm](#nvm)
- - [node](#node)
- - [yarn](#yarn)
- - [git autocomplete](#git-autocomplete)
- - [use nano for git](#git-nano)


## Environment <a name="environment" />
### iTerm2 <a name="iterm2" />
https://iterm2.com/downloads.html

#### Fix option arrow <a name="arrows-navigation" />
https://www.clairecodes.com/blog/2018-10-15-making-the-alt-key-work-in-iterm2/

#### Restore iTerms2 tabs after restart <a name="restore-tabs" />
I prefer to use MacOS system function "Close windows when closing documents".
Just uncheck this in Settings => General
It affects all apps, but it's convinient anyway.
It's recommended way - https://iterm2.com/documentation-restoration.html

More details
https://appuals.com/how-to-stop-your-macos-from-reopening-apps-after-a-reboot-or-a-crash/

### Xcode dev tools <a name="xcode-dev-tools" />
`xcode-select –install`

### nvm <a name="nvm" />

[Install nvm script](https://github.com/nvm-sh/nvm#install--update-script)

Don't forget to add required env variables to ~/.zshrc to make it available for new terminal sessions.
Necessary exports can be find on the link above.

### node <a name="node" />
use LTS version as default

`nvm install v16`

### yarn <a name="yarn" />
For yarn 1.x.x

`npm install --global yarn`

### Add autocomplete to git <a name="git-autocomplete" />
https://www.macinstruct.com/tutorials/how-to-enable-git-tab-autocomplete-on-your-mac/

### Use nano for git <a name="git-nano" />
`git config --global core.editor "nano"`

