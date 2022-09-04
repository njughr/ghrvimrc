# Vimrc Repo
**my vim configurations and more**

## vim shortcuts

```
hjkl "move the cursor"
ZQ=:q! "force exit"
ZZ=:wq "write and quit"
<ESC> " back to normal mode"
u "undo"
U "undo the whole line"
^R "redo"
x "delete current character"
X "delete character before"
^f "Page Down"
^b "Page Up"
^d "Half Page Down"
^u "Half Page Up"
^e "scroll one line down"
^y "scroll one line up"
^g "show where you current are"
^o "go back to the next position"
^i "go forward to the next position"
^z "suspend vim. type fg to go back"
i "insert"
a "append"
A "apend after the end of the line"
r<x> "replace a character with x"
R "continue replace a lot of characters"
s "delete character and insert"
S "delete line and insert"
^a "add 1"
<n>^a "add n"
^x "minus 1"
<n>^x "minus n"
e "next end of a word"
w "next start of a word"
W "next WORD, sep by BLANK"
b "front start of a word"
ge "front end of a word"
p "paste, or put"
0 "move to the start of the line"
$ "go to end of a line"
gg "go to start of the file"
G "go to the end of the file"
<n>G "go to line n"
<p>% "go to location <p>%"
yy=Y "copy current line"
dd "delete and copy current line"
cc "change the whole line "
zz "current line move to screen center"
zt " current line move to screen top"
zb " current line move to screen bottom"
o "open a new line and start insert"
O "open a new line above and start insert"
de "del to the end space without space"
dw "del to the end space with space"
. "repeat the last OPERATION"
d$ "delete to the end of the line"
<n>fx "find the n-th character x" 
/abc "search abc"
?abc "backward search abc"
n "next search"
N "backward next search"
<n>s "del n characters and insert"
ce "change the word until the end"
c$ "change the line until the end"
cw "change the word, seems equal to ce"
<n>G=:<n> "move to line n"
% "find a matching bracket"
:s/a/b "replace one a with b"
:s/a/b/g "replace all in current line"
:s/a/b/gc "ask for yes and replace"
:%s/a/b "replace in the whole file"
:#,#s/a/b/g "#,# are the line numbers"
:! <bash> "execute a bash command"
:w filename "write to file filename"
v "start visual mode"
V "select the whole line"
^V "start block select v mode"
:r FILENAME "insert a file"
:r !cmd "insert cmd output"
y "copy text"
yw "copy one word"
^W^W "jump within windows"
:e^D "cmd completion. ^D=<TAB> "
ciw "change in word, all word "
<sym>=b() [] B{} <> '' ""
ci<sym> "change in <sym>"
di<sym> "delete in <sym>"
yi<sym> "copy in <sym>"
vi<sym> "select in <sym>"
ca<sym> "change include <sym>"
da<sym> "delete include <sym>"
ya<sym> "copy include <sym>"
va<sym> "selet include <sym>"
^ "go to the first NOT blank char"
:n "edit next file"
:N "edit last file"
:files "list all files opened"
:sp filename "open a newfile"
^w<hjkl> "move current window, hjkl"
q<n> " recording start/stop. save to reg n"
@q "exe the macro recording in reg n"
<n>@q "exe the macro n times"
<ins>^u "delete all before cursor"
<ins>^w "delete word before cursor"
<ins>^o "execute a normal cmd once"
set nocp "not in compatible mode"
set ic "ignore case when search"
set hls is"high light search, incremental search"
set noic nohls nois "disable"
F1 "start help"
:help w "getting help"
:help c_CTRL-D "getting help"
:help insert-index "getting help"
:help user-manual "getting help"
:g/V/t.|-d<CR>ZZ "hello vimgolf!"
```
