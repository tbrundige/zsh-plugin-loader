# zsh-plugin-loader

A lightweight plugin loader used to load plugins hosted on github.com.

## Usage
Add the desired plugin to github_plugins in the following format, `<github organization name>/<repo name>`

Add `source ~/.zsh/zsh-plugin-loader/zsh-plugin-loader.zsh` to `~/.zshrc`
e.g. `echo source ~/.zsh/zsh-plugin-loader/zsh-plugin-loader.zsh >> ~/.zshrc`

Plugins will be install in `~/.zsh_plugins/<github organization name>/<repo name>`

To update plugins, run `pu`
