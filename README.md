
## 开发环境

### 总环境
* [https://github.com/mathiasbynens/dotfiles](https://github.com/mathiasbynens/dotfiles) 快速搭好`bash_rc`和`vim_rc`
* **特别注意，下载的脚本会用它们的`bash_profile`和`vim_rc`替换之前的环境**

### bash
* git自动补全
	* https://github.com/bobthecow/git-flow-completion/wiki/Install-Bash-git-completion

### vim 
* 颜色配置
	* 原来默认的使用的solarized
	* tomorrow night

	
* 各种插件在http://vimawesome.com/可以找到
	* 	https://github.com/gmarik/Vundle.vim vim插件
	*  https://github.com/Valloric/YouCompleteMe 自动补全插件
		* **需要拿源码编译7.4版本的vim：http://zhouyichu.com/vim/Vim-in-Mac.html**
		* **需要安装cmake**
		* 需要对JS支持自动补全：http://tilvim.com/2013/08/21/js-autocomplete.html。使用tern_for_vim 
	* 工程树结构：https://github.com/scrooloose/nerdtree
	* 搜索代码
		* brew install ack安装外部命令
		* 安装ack的vim plugin
	* 优化的状态栏 airline
	* 语法检查 syncastic
	* git快速命令 fugitive.vim