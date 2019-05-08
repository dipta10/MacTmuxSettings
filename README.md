First install Tmux.
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null
brew install tmux
```
Kill all the session (if any):
```
pkill -f tmux
```
Now just clone the repository.
```
git clone https://github.com/dipta10/MacTmuxSettings.git ~/.tmux
```