### Tmux

First install Tmux.

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null
brew install tmux
```

Kill all sessions (if any):

```
pkill -f tmux
```

Now clone the repository

```
git clone https://github.com/dipta10/MacTmuxSettings.git ~/.tmux
```

Remove all the files inside the `plugins` directory. Now install [tpm](https://github.com/tmux-plugins/tpm).

```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
tmux source ~/.tmux.conf
```

Create Symblink:

```
ln -s ~/.tmux/.tmux.conf ~/.tmux.conf
```

Now, hit `prefix + I` to fetch all the plugins and source it. Try `prefix + U` if it doesn't work. In my case prefix is `ctrl + a`.
Create Symblink:
