# Vimrc Repo

**IMPORTANT NOTICE: This repository is out of maintenance, please check [dotfiles](https://github.com/njughr/dotfiles) for the latest updates.**

**my vim configurations and more**

u can find the most popular vim plugins on **[VimAwesome](https://vimawesome.com/)**

## vim shortcuts

> Stick with it because I'd say that in about 20 hours of programming using a new editor you'll be back to the same speed at which you programed using your old tool and then after that the benefits will start, and you'll get faster and faster as you learn more.
>
> Once this becomes muscle memory you can basically **edit files at the speed at which you think**.

```css
hjkl "move the cursor"
ZQ=:q!<CR> "force quit"
ZZ=:wq<CR> "write and quit"
<ESC> " back to normal mode"
u "undo"
U "undo, whole line"
^R "redo"
x=dl "delete current character"
X "delete character before"
zz "curnt line scroll to center"
zt "curnt line scroll to top"
zb "curnt line scroll to bottom"
H "cursor move to top"
M "cursor move to middle"
L "cursor move to bottom"
^f "Page Down FForward"
^b "Page Up BBackward"
^d "Half Page DDown"
^u "Half Page UUp"
^e "scroll one line down"
^y "scroll one line up"
^g "show where you current are"
^o "go back to the next position"
^i "go forward to the next position"
^z "suspend vim. type fg to go back"
^a "add 1"
<n>^a "add n"
^x "minus 1"
<n>^x "minus n"
i "insert"
I "insert at the begin of the line"
a "append"
A "apend after the end of the line"
r<x> "replace a character with x"
R "continue replace a lot of characters"
s=cl "delete character and start insert"
S "delete line and start insert"
e "next end of a word"
w "next start of a word"
W "next WORD, sep by BLANK"
b "front start of a word"
ge "front end of a word"
f<x> "find char x on the curnt line"
F<x> "backward find char x"
; "navigating f matches"
, "backward navigating f matches"
t<x> "move cursor till char x"
T<x> "move cursor back till char x"
/{regex} "search regular expression"
?{regex} "backward search regex"
n "next search"
N "backward next search"
% "find a matching bracket"
^ "go to the first NOT blank char"
0 "move to the start of the line"
$ "go to end of a line"
gg "go to start of the file"
G "go to the end of the file"
<n>G=<n><CR>=:<n> "go to line n"
<p>% "go to location <p>%"
p "paste, or put"
y "yank, copy text"
yw "yank, copy one word"
v "start visual mode"
V "select the whole line"
^v "start block select v mode"
yy=Y "copy current line"
dd "delete and copy current line"
ddp "swap lines"
cc "change the whole line"
o "new line and start insert"
O "new line above and start insert"
de "del to the end space without space"
dw "del to the end space with space"
diw "can delete all blank char"
ce "change the word until the end"
c$ "change the line until the end"
cw "change the word, seems equal to ce"
ciw "can change all blank char"
. "repeat the last OPERATION"
d$ "delete to the end of the line"
~ "flips the case of a character"
gu{motion} "to lowercase"
gU{motion} "to uppercase"
<sym>=b() [] B{} <> '' ""
ci<sym> "change in <sym>"
di<sym> "delete in <sym>"
yi<sym> "copy in <sym>"
vi<sym> "select in <sym>"
ca<sym> "change include <sym>"
da<sym> "delete include <sym>"
ya<sym> "copy include <sym>"
va<sym> "selet include <sym>"
qq "reg q recording start/stop "
@q "exe reg q macro"
<n>@q "exe reg q macro n times"
<ins>^u "delete all before cursor"
<ins>^w "delete word before cursor"
<ins>^o "execute a normal cmd once"
set nocp "not in compatible mode"
set ic "ignore case when search"
set hls "high light search"
set is "incremental search"
set noic nohls nois "disable"
:s/a/b "replace one a with b"
:s/a/b/g "replace all in current line"
:s/a/b/gc "ask for yes and replace"
:%s/a/b/g "replace in the whole file"
:#,#s/a/b/g "change in line #,#"
:! <cmd> "execute a bash cmd"
:w filename "write to file filename"
:r FILENAME "insert a file"
:r !cmd "insert cmd output"
:e^D "cmd completion. ^D=<TAB>"
:n "edit next file"
:N "edit last file"
:files "list all files opened"
:sp "split horizontally"
:vsp "split vertically"
^w<hjkl> "change current window"
^W^W "jump between windows"
F1 "start help"
:help w "getting help"
:help c_CTRL-D "getting help"
:help insert-index "getting help"
:help user-manual "getting help"
:g/V/t.|-d<CR>ZZ "hello vimgolf"
```

## MyKeyMap

```css
vnoremap <C-Y> "+y	"Vim Ctrl+C"
vnoremap <C-D> "+d	"Vim Ctrl+X"
nnoremap <C-P> "+p	"Vim Ctrl+V"
nnoremap QQ :q!<CR>	"QQ not ZQ"
```

## Thanks

[MIT instructor Anish's vimrc](https://github.com/anishathalye/dotfiles/blob/master/vimrc)

[MIT instructor Jon's nvimrc](https://github.com/jonhoo/configs/blob/master/editor/.config/nvim/init.vim)

[MIT instructor Jose's vimrc](https://github.com/JJGO/dotfiles/blob/master/vim/.vimrc)

[上古神器Vim：进阶使用/配置、必备插件介绍 - 终极Vim教程02 - 带你配置属于你自己的最强IDE](https://www.bilibili.com/video/BV1e4411V7AA/?spm_id_from=333.788.recommend_more_video.0&vd_source=14d31885014e67975c65bd7a2dedbc60)

[theniceboy](https://github.com/theniceboy) / **[vimrc-example](https://github.com/theniceboy/vimrc-example)** [TheCW]

[最强Vim新手指南，手把手教你打造只属于自己的代码编辑器！](https://www.bilibili.com/video/BV1UQ4y1z7q5?spm_id_from=333.337.search-card.all.click&vd_source=14d31885014e67975c65bd7a2dedbc60)

[MarsWang42](https://github.com/MarsWang42) / **[My-Vim-Conf](https://github.com/MarsWang42/My-Vim-Conf)** [MARS]
