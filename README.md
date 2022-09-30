# My ZSH Config

This configurations is a **minimal config** for your zsh (autosuggestions, syntax highlighting etc..) no oh-my-zsh required.

I'm not the author of the original configuration. I followed a tutorial on Youtube to custom this configuration, you can follow along with this [video](https://www.youtube.com/watch?v=bTLYiNvRIVI) to.

## Try out this config

**IMPORTANT** Requires [Zsh](https://www.geeksforgeeks.org/how-to-install-z-shellzsh-on-linux/). 

Make sure to remove or move your current `zsh` directory in your `~/.config`

If your zsh directory is not currently in `~/.config`, please put these following lines to your `.zprofile`.

```
# XDG Paths
export XDG_CONFIG_HOME=$HOME/.config
export XDG_CACHE_HOME=$HOME/.cache
export XDG_DATA_HOME=$HOME/.local/share

# zsh config dir
export ZDOTDIR=$HOME/.config/zsh
```

Now clone this repo to your `~/.config` by run the command below.

```
git clone https://github.com/voanhhieu10250/zsh-configuration.git ~/.config/zsh
```

## Packages need to install:

fzf (command-line fuzzy finder; `Ctrl+r` to find previous commands) - [install](https://github.com/junegunn/fzf#using-homebrew:~:text=the%20extra%20stuff.-,Using%20Homebrew,-You%20can%20use)


## References & Credit

[chris@machine](https://www.youtube.com/c/ChrisAtMachine)

