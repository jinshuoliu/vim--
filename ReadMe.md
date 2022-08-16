# Vim插件

## netrw

vim 自带路径管理功能, 我们可以使用vim 自带的 netrw 进入路径管理窗口

***操作命令***

| 命令 | 功能 |
|--|--|
| :Ex | 全屏进入 netrw, 全称是 :Explorer |
| :Sex> | 水平分割进入 netrw |
| :Vex> | 垂直分割进入 netrw |
| < F1> | 在 netrw 界面弹出帮助信息 |
| < CR> | 打开光标下文件/夹 |
| - | 进入上一级目录 |
| p | 预览文件(光标保持不动) |
| P | 打开文件, 会在上一个使用的窗口一侧的第一个窗口打开文件 |
| < C-w>z| 关闭预览窗口 |
| gn | 使光标下的目录作为目录树最顶部, 在 tree style 下与 < CR> 是不同的 |
| d | 创建文件夹 |
| D | 移除文件/夹 |
| cd | change 工作目录到当前路径 |
| I | 显示/隐藏顶部 banner |
| o | 以水平分割窗口方式打开光标下文件 |
| v | 以垂直分割窗口方式打开光标下文件 |
| % | 在当前目录下新建一个文件并编辑 |
| r | 翻转排序方式 |
| qb | 列出所有的目录以及历史路径 |
| qf | 显示文件详细信息 |
| R | 重命名文件/文件夹 |
| s | 在 name, time 和 file size 之间切换排序 |
| t | 新 tab 中打开文件 |
| < c-h> | 编辑隐藏列表 |
| < c-l> | 更新 netrw 列表内容 |
| a | 隐藏/显示由 g : netrw_list_hide 所控制的文件 |
| C | 设置编辑窗口 |
| gb | 跳转到上次标记的书签 |
| gd | 强制作为目录 |
| gf | 强制作为文件 |
| gh | 快速隐藏 . 开头的文件 |
| i | 在 thin, long, wide, tree listings 状态之间切换 |
| mb | 将当前目录存为书签 |
| mc | Copy marked files to marked-file target directory |
| mm | Move marked files to marked-file target directory |
| md | 对标记的文件做 diff 操作 |
| me | 将标记的文件放入参数列表中并进行编辑 |
| mf | 标记一个文件 |
| mF | 取消标记一个文件 |
| mg | 对标记的文件使用 vimgrep 命令 |
| mp | 打印标记的文件 |
| mr | 使用 shell-style 标记文件 |
| mt | 使当前目录成为标记文件目标 |
| mT | 对标记文件应用 ctags |
| mu | 对所有标记文件取消标记 |
| mz | 压缩/反压缩标记文件 |
| O | Obtain a file specified by cursor |
| qF | Mark files using a quickfix list |
| S | 确认在 name 排序状态下的扩展名优先级 |
| u | 跳转到上一次浏览的目录 |
| x | 使用系统中与之关联的程序打开光标下文件 |
| X | 执行光标下的文件 |

## NerdTree

替代 netrw

***文件操作***

| 命令 | 功能 |
|--|--|
| e | 进入文件夹内部浏览, 会在右侧开启小窗口进入文件夹列表 |
| o | 在预览窗口中打开文件, 左侧 NerdTree 仍然被保留(事实上除非打开新 tab 或手动退出, 否在会一直存在) |
| O | 递归地打开其内所有文件夹 |
| go | 在预览窗口中打开文件, 光标将仍然保留在小窗口中, 非常好用, 用于预览多个文件特别有用. |
| i | 以分割视图打开文件 |
| gi | 以分割视图打开, 但是光标仍然保留在小窗口 |
| s | 以分割视图打开文件 |
| gs | 以分割视图打开文件, 但是光标仍然保留在小窗口 |
| t | 在新标签页打开选择的文件, 全屏 |
| T | 在新标签页静默打开选择的文件, 全屏, 因为是静默, 所以不会跳转到新窗口 |
| C | 将当前所选文件夹改为根目录, 即进入到所选择的文件夹, 与 o 不同, o 是在当前视图下将文件夹展开, C 则是直接进入到文件夹. |
| cd | 将当前文件夹改为 cwd(当前工作目录) |
| CD | 将文件夹目录跳转到 CWD(当前工作目录)中 |
| m | 对所选择的文件或文件夹弹出编辑菜单. 包括修改文件名, 复制, 移动, 删除等操作 |
| B | 隐藏 / 显示书签, 如果显示书签, 还会将光标自动跳转至书签 |
| I | 显示系统隐藏文件 |

***关闭移动系列***

| 命令 | 功能 |
|--|--|
| Ctrl+W l | 光标向右分屏移动 |
| Ctrl+W q | 关闭当前分屏, 如果是最后一个, 则出 vim |
| Ctrl+W + o | 关闭其他窗口只留下当前窗口 |
| q | 直接退出 NerdTree |
| Ctrl+W L | 分屏向右移动 |
| Ctrl+W + + | 分屏增加或减少高度 |
| Ctrl+W + < | 分屏增加或减少宽度 |
| gt | 跳转到下一个 tab |
| gT | 跳转到上一个 tab |
| D | 删除书签 |
| F | 隐藏文件, 只保留文件夹在视图中 |
| ⌃ j | 当同一个 NerdTree 有多个目录级别时, 只在同一级别下向下移动 |
| ⌃ k | 当同一个 NerdTree 有多个目录级别时, 只在同一级别下向上移动 |
| J | 移动到同一级别的最下方 |
| K | 移动到同一级别的最上方 |

***其他***

| 命令 | 功能 |
|--|--|
| A | 全屏进入 NerdTree 窗口 |
| r | 刷新当前文件夹的缓存, 使界面刷新 |
| R | 刷新整个文件夹树的缓存, 使整个界面更新 |
| ? | 快速显示帮助, 非常有用, 忘记功能时使用! |

## xkbswitch 未设置

vim 下的输入法自动切换工具, 在进入命令模式时自动切换至英文输入法, 回到插入模式时返回到上一次选择的输入法(在需要中英文切换的环境中非常有用)

下载基础工具xkbswitch-macosx(每个系统有不同的实现工具, 这里以 macOS 为例)
将该项目下的 /bin/xkbswitch 文件复制到 /usr/local/bin 目录中(任意 $PATH 中的目录都可以)
先在 .vimrc 文件中添加 Plug 名称及设定:
Plug 'lyokha/vim-xkbswitch', {'as': 'xkbswitch'} let g:XkbSwitchEnabled = 1
运行 vim, 输入命令 :PlugInstall

## tabular

一款对齐插件, 快速按照给定的分隔符号完成指定范围内的对齐操作

|||
|--|--|
| :Tabularize /,/ | 将整个缓冲区的所有行按照 , 符号进行对齐 |
| :'<,'>Tabularize /,/ | 对高亮选中范围内的行进行对齐 |
| :Tabularize /,/l1/c1/r0 | 按照 , 进行对齐, 并且为每个分割的文本区域内的文本指定对齐方式, l, c, r 分别为左中右对齐, 1 代表空距离分隔符一个空格 |

**例：**abc,def,ghi a,b a,b,c :Tabularize /,/r1c1l0 abc , def, ghi a , b a , b , c

## Markdown-preview

一款在浏览器中预览 markdown 文件的插件

| 语法 | 含义 |
|--|--|
| :MarkdownPreview | 开启预览 |
| :MarkdownPreviewStop | 停止预览 |
| :MarkdownPreviewTroggle | 开关预览 |

***使用***

只要在 vim 界面中使用 :TagbarToggle 即可调出 Tagbar 界面, 即可显示 markdown 的目录结构.

### markdown2ctags

在窗口右侧显示 markdown 目录结构的一个插件, 此插件基于 ctags 和 tagbar(Tagbar 是一个著名的文档目录显示插件, 但是不支持 markdown, 此插件在 Tagbar 的基础上添加了对 markdown 的支持). 因此此插件必须同时安装以上两种插件方可正常工作

***使用***

只要在 vim 界面中使用 :TagbarToggle 即可调出 Tagbar 界面, 即可显示 markdown 的目录结构.

### markdownlint 未安装

一款 markdown 语法检查工具, 可以根据预设的规则进行 markdown 语法错误警告或提示, 可根据需要进行规则自定义

安装
brew install markdownlint-cli
使用
配合 ALE 插件一起使用

let g:ale_linters = {
            \   'c': ['clangd'],
            \   'swift': ['swiftlint'],
            \   'markdown': ['markdownlint'],
            \   'sh': ['shellcheck'],
            \   'zsh': ['shellcheck']
            \}
配置规则
在项目根目录下建立 .markdownlint.json 配置文件, 在其中对默认的规则进行配置, ale markdownlint 工具在被调用的时候会自动去查找该名称配置文件

{
  "default": true,
  "MD013": false,
  "MD014": false,
  "MD024": false,
  "MD029": false,
  "MD033": false,
  "MD040": false,
  "no-hard-tabs": false,
  "no-inline-html": {
    "allowed_elements": [
      "a"
    ]
  }
}

## fzf

fuzzy find, 快速模糊搜索查找工具

❝fzf.vim 与 终端工具 fzf 配合使用, 在 vim 中的 :FZF 与 Files 命令都会调用 export FZF_DEFAULT_COMMAND='...' 这个参数, 需要在 .zshrc 中配置好

| 命令 | 功能 |
|--|--|
| :Files [path] | 列出 path 路径下的所有文件 (功能等价于 :FZF 命令) |
| :Buffers | 文件缓冲区切换 |
| :Colors | 选择 Vim 配色方案 |
| :Tags [QUERY] | 当前项目中的Tag (等价于: ctags -R) |
| :BTags | [QUERY] 当前活动缓冲区的标记 |
| :Marks | 所有Vim标记 |
| :Windows | 窗口 |
| :Lines [QUERY] | 在所有加载的文件缓冲区里包含目标词的所有行 |
| :BLines [QUERY] | 在当前文件缓冲区里包含目标词的行 |
| :Locate PATTERN | locate command output |
| :History: v |oldfiles and open buffers |
| :History: | 命令行命令历史 |
| :History/ | 搜索历史 |
| :Commands | Vim 命令列表 |
| :Maps | 普通模式下的按键映射 |
| :Snippets | Snippets ([UltiSnips][us]) |
| :Commits | Git commits (requires [fugitive.vim][f]) |
| :BCommits | 查看与当前缓冲区有关的 commit |
| :GFiles [OPTS] | Git files (git ls-files) |
| :GFiles? | Git files (git status) |
| :Ag [PATTERN] | [ag][ag] search result (ALT-A to select all, ALT-D to deselect all) |
| :Rg [PATTERN] | [rg][rg] search result (ALT-A to select all, ALT-D to deselect all) |
| :Filetypes | File types |

## YouCompleteMe

命令补齐插件, 支持 c, c++, java, python, PHP 等多语言

## ludovicchabant/vim-gutentags

管理 tag 文件, tag 文件关乎着项目的引用与跳转

https://zhuanlan.zhihu.com/p/36279445

## vim-surround

一款超级强大的快速添加/删除/改变包围符号的神器

| 命令 | 功能 |
|--|--|
| ds | 删除包围符号 |
| cs | 改变包围符号 |
| ysw | 当前至下一个词尾添加一个包围符号 |
| ysW | 当前至至下一个空格添加一个包围符号 |
| ySw | 当前至下一个词尾添加一个包围符号并将焦点移至下一行 |
| ySW | 当前至下一个空格添加一个包围符号并将焦点移至下一行 |
| yss | 整行添加包围符号 |
| S"| Visual 模式下对选中区域添加包围符号 " |
| gS"| Visual 模式下对选中区域进行换行并添加包围符号 |
| ⌃-s | Insert 模式下插入包围符号 |
| ⌃-s, ⌃-s | Insert 模式下在插入包围符号并将焦点移至下一行 |
| dst | 删除 html/xml 的标签内部的所有字符 |
| cst | 删除 html/xml 的标签内部的所有字符并进入插入模式 |
| ysa<'| 在 <> 包裹的范围上加符号 ' |

范例

| Old text              | Command    | New text                    |
| :-------------------: | :-----:    | :-----------------------:   |
| "Hello *world!"       | ds"        | Hello world!                |
| [123+4*56]/2          | cs])       | (123+456)/2                 |
| "Look ma, I'm *HTML!" | `cs"<a>`   | `<a>Look ma, I'm HTML!</a>` |
| if *x>3 {             | ysW(       | if ( x>3 ) {                |
| my $str = *whee!;     | vlllls'    | my $str = 'whee!';          |
| < div>Yo!*< /div>       | dst        | Yo!                         |
| < div>Yo!*< /div>       | `cst<p>`   | `<p>Yo!</p>`                |

## nerdcommenter

快速注释插件

| 命令 | 功能 |
|--|--|
| < leader>cc | NERDCommenterComment, 注释当前行或所选择行(文本) |
| < leader>cu | NERDCommenterUncomment, 取消当前所处位置的注释状态 Uncomments the selected line(s). |
| < leader>ci | NERDCommenterInvert, 反转所选择行的注释状态(逐个地反转) 仅支持行 |
| < leader>c< space> | NERDCommenterToggle (反)激活所选择行的注释状态, 依据最顶部行的注释状态进行判断, 执行命令后, 所选择行的注释状态均为最顶部行注释状态的相反状态. 仅支持行 |
| < leader>cn | NERDCommenterNested, 与 cc 相同, 不过嵌套地进行注释 |
| < leader>cs | NERDCommenterSexy, 将当前选择文本以块的方式进行注释(即在选择文本的上方与下方加上单行注释) 仅支持行 |
| < leader>cy | NERDCommenterYank, 与 cc 完全相同, 不过会先进行复制操作 |
| < leader>c$ | NERDCommenterToEOL Comments the current line from the cursor to the end of line. |
| < leader>cA | NERDCommenterAppend, Adds comment delimiters to the end of line and goes into insert mode between them. |
| < leader>ca | NERDCommenterAltDelims Switches to the alternative set of delimiters. |
| < leader>cm | NERDCommenterMinimal, Comments the given lines using only one set of multipart delimiters. |

## tpope/vim-commentary

快速注释插件, 相比于 nerdcommenter 更加简洁实用

| 命令 | 功能 |
|--|--|
| gcc | 注释或反注释 |
| gcap | 注释一段 |
| gc | visual 模式下直接注释所有已选择的行 |

## terryma/vim-multiple-cursors

实现真正的多光标的一个插件, vim 的 visual block 模式并不是多光标, 如果想将 visual block 模式下被选中的多行的当前单词推进到每个单词的末尾, 那么就需要使用到多光标的概念.

❝我理解的此多光标插件的使用分为两种状态
从 normal 模式直接使用 < C-n> 进入多光标状态并选中当前光标下的单词, 然后再次使用 < C-n> 选择下一个, < C-x> 跳过当前符合的单词, 最后进行插入修改等操作
从 visual 或 visual block 模式下使用 < C-n> 进入直接添加光标到当前所有行的选中单词处, 然后移动光标, 在合适位置进行进行插入修改等操作, 最后 esc 两次退出

| 命令 | 功能 |
|--|--|
| < C-n> | 进入多光标状态/或选择下一个符合当前选择的单词 |
| < C-x> | 跳过当前候选 |
| < C-p> | 移除当前单词处的光标及选择状态跳转到上一个光标处 |

## seoul256.vim

一套配色 vim 配色方案,与之匹配的还有一个 iTerm 配色方案, 两者结合的比较好看
