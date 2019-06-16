# Hyper Oh-My-ZSH

> Oh-My-ZSH theme based on hyper terminal default theme 😎 


## Screenshot

> It requires a change on your terminal. Change your cursor color to magenta


### Inside a folder without git configuration

<img width="682" alt="Hyper Oh-My-ZSH - Inside a folder without git configuration" src="https://user-images.githubusercontent.com/1252570/43366463-d48d9f68-9381-11e8-9871-9166c6c29da6.png">

### Inside a folder with git configuration

<img width="682" alt="Hyper Oh-My-ZSH - Inside a folder with git configuration" src="https://user-images.githubusercontent.com/1252570/43366555-1a7e5eb2-9383-11e8-89d5-98b255968bdb.png">


## About the theme

`hyper-oh-my-zsh` is a [z shell](http://www.zsh.org/) theme designed to complement a git-focused workflow based on `Hyper` default terminal theme. It gives you a comprehensive overview of the branch you're working on and the status of your repository throughout the development process without cluttering your terminal.  

It currently shows (in order of the prompt):  
- Current working directory
- Git branch
- Exit code of last command
- Time since last commit
- Git status
- Background Jobs


## Installation

If you're using `oh-my-zsh`, you need to make sure that you have the a `themes` folder inside the oh-my-zsh `custom` folder and you're using the new theme 🎉 🎉 🎉 🎉

To install this theme, open your terminal and paste this command into your command line.

```bash
mkdir -p $ZSH_CUSTOM/themes && wget -O $ZSH_CUSTOM/themes/hyper-oh-my-zsh.zsh-theme https://raw.githubusercontent.com/willmendesneto/hyper-oh-my-zsh/master/hyper-oh-my-zsh.zsh-theme
```

After that, open your `~/.zshrc` file in your prefered code/text editor and set `ZSH_THEME="current_theme"` to `ZSH_THEME="hyper-oh-my-zsh"`. And when you reload your command line it's done! 👏👏👏

## Prompt configuration

### Git Status Indicators

| Variable | Indicator | Meaning |
|----------|-----------|---------|
| `ZSH_THEME_GIT_PROMPT_UNTRACKED` | ◒ | Untracked files |
| `ZSH_THEME_GIT_PROMPT_ADDED` | ✓ | Files added to git |
| `ZSH_THEME_GIT_PROMPT_MODIFIED` | △ | Modified files |
| `ZSH_THEME_GIT_PROMPT_DELETED` | ✖ | Deleted files |
| `ZSH_THEME_GIT_PROMPT_RENAMED` | ➜ | Renamed files |
| `ZSH_THEME_GIT_PROMPT_UNMERGED` | § | Unmerged files |
| `ZSH_THEME_GIT_PROMPT_AHEAD` | ▲ | Repo ahead of current branch |
| `ZSH_THEME_GIT_PROMPT_DIRTY` | ✗ | Dirty repository |


### Right hand prompt  

The right hand prompt displays the current branch, time since last commit, as well as commit status of the repository  

| Variable | Branch Color |
|----------|--------------|
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_SHORT` | Green |
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_MEDIUM` | Yellow |
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_LONG`  | Red |
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_NEUTRAL` | White |


## Author

**Wilson Mendes (willmendesneto)**
+ <https://twitter.com/willmendesneto>
+ <http://github.com/willmendesneto>
