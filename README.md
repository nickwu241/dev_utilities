# devkit
Make sure you have `git` installed, then to clone this repo:
```shell
git clone https://github.com/nickwu241/devkit.git
```

### Git
Requires `git` to be installed.
```shell
# Change these values as needed
git config --global user.name "Nick Wu"
git config --global user.email nickwu241@gmail.com

git config --global core.editor vim
git config --global push.default current

git config --global alias.br branch
git config --global alias.co checkout
git config --global alias.st 'status -s'
git config --global alias.cm 'commit -m'
git config --global alias.cam 'commit -am'
git config --global alias.sl 'log --oneline -n 10'
git config --global alias.slo 'log --oneline'
git config --global alias.diffc 'diff --cached'
git config --global alias.pub '!git push origin $(git rev-parse --abbrev-ref HEAD)'
git config --global alias.brc '!git branch --merged | egrep -v "(^\*|master|dev)" | xargs git branch -d'
```

### Vim
Requires `git` and `vim` to be installed.
```shell
./vim-setup.sh
```

### macOS
```shell
./macos/defaults.sh
./macos/brew-setup.sh
```

### Other
My rough notes will be in [this gist](https://gist.github.com/nickwu241/1abc77d7352c6252127f16a1af6ceb45).
