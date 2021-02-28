# vim配置文件

## 文件路径： ~/.vimrc

## 常用配置

关闭兼容功能 set nocompatible
显示行号 set number
编辑时 backspace 键设置为2个空格 set backspace=2
编辑时 tab 键设置为4个空格 set tabstop=4
设置自动对齐为4个空格 set shiftwidth=4
搜索时不区分大小写 set ignorecase  
搜索时高亮显示 set hlsearch


## 常用命令

### 跳转类

跳转至文件末尾 G  

跳转至文件开头 gg  

跳转至指定行 ngg（跳转至第n行）  

跳转至当前行行首 数字0

跳转至当前行行尾 shift + 4

### 复制、粘贴

复制当前行 yy

复制当前行及其后的n-1行(n是数字） nyy

粘贴 P

### 查找、替换

从光标开始处向文件尾搜索pattern，后按下n或N /pattern

n在同一个方向重复上一次搜索命令
N在反方向重复上一次搜索命令

n(N)来源于next

### 进入编辑模式

在光标前开始插入文本 i

在光标后开始插入文本 a 

在当前行之后插入一行，并跳转到行首 o
