dotfiles
========

Steps to setup
1. Install iterm2 (or use your preferred terminal) -> https://www.iterm2.com/
2. Follow the steps listed here: https://jasoncharnes.com/install-ruby (_the commands to paste are between the <code></code> tags_)
3. `brew install git`
4. Clone this repo to the root of your computer (type `cd` with nothing following it to jump to if needed)
5. `cd ./dbc-dotfiles`
6. `sudo chmod +x ./install`
7. `./install`

These are a collection of dotfiles.

+ Either copy paste install these or run ./install to copy over your local settings
+ Sublime symlinking for both Sublime text 2 and 3 can be run with ./sublimelink
+ A Standard install will overwrite your .gitconfig removing your github username and email. To set them again type
``` bash
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
