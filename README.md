## spaceship-git-user plugin

## Preview
[](https://user-images.githubusercontent.com/8085088/195627784-bc5ed2cb-d516-4761-8cea-7e351188ba18.png)

### install plugin
```git clone https://github.com/brucejcw/spaceship-git-user.git "$ZSH/plugins/spaceship-git-user"```

### update .zshrc
```
vim ~/.zshrc
plugins=(... spaceship-git-user)

source $ZSH/oh-my-zsh.sh
# add spaceship after source command
spaceship add git_user
```

## configuration
SPACESHIP_GIT_USER_PREFIX
SPACESHIP_GIT_EMAIL_SYMBOL
SPACESHIP_GIT_USER_SYMBOL
SPACESHIP_GIT_USER_COLOR
