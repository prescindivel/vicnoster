# vicnoster
### vicnoster is a [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) theme based on the [Powerline Vim](https://github.com/Lokaltog/vim-powerline) plugin & [Agnoster](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#agnoster) theme.

It currently shows:

- timestamp
- battery life
- user & host status
- current directory
- git branch
- git file counter not sent
- git commits counter uncommitted
- [awesome terminal icons](https://github.com/gabrielelana/awesome-terminal-fonts/)

## Previews

![preview home directory](images/preview-home.png)
![preview home directory](images/preview-git.png)

## How to install

1. install [awesome terminal icons](https://github.com/gabrielelana/awesome-terminal-fonts/)

2. select a monospaced font from your system to you installed
	* in Ubuntu install Ubuntu Tweak tool to change the font

3. install [vicnoster zsh theme](https://github.com/victordev/vicnoster) in your themes folder`~/.oh-my-zsh/themes/` 

	```shell
	$ curl -o ~/.oh-my-zsh/themes/vic.zsh-theme https://raw.githubusercontent.com/victordev/vicnoster/master/vicnoster.zsh-theme
	```
4. select the theme vicnoster in your `.zshrc` file

	1. open the `.zshrc` file
		```shell
		$ vim ~/.zshrc
		```
	2. find `ZSH_THEME` and change to:
		```shell
		ZSH_THEME="vicnoster"
		```
5. reload `.zshrc`
	```shell
	$ source ~/.zshrc
	```


