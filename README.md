1. check out to linux version
2. execute 'setup'
3. relogin

### key mapping

|normal mode      | description|
|:----------------|:-----------|
|\<Leader\>nh       | clear search|
|\<Leader\>so       | reload vimrc file|
|\<Leader\>vn       | open file to vertical|
|\<Leader\>vi       | edit vimrc file|
|\<Leader\>t        | open terminal|
|\<Space\>          | collapse line|
|\<C-n\>            | create a space to new tab|
|\<C-q\>            | quit|
|\<C-s\>            | save|
|\<C-a\>            | plus one|
|\<C-x\>            | minus one|
|\<C-xx\>           | close tab|
|\<C-k\>            | switch to next tab|
|\<C-j\>            | switch to previous tab|
|\<Leader\>\<Leader\> | check the current cursor synstack|
|\<F2\>             | NERDTree toggle|
|\<F3\>             | Tagbar toggle|
|\<C-p\>            | use `:Files` command in fzf plugin|
|FF               | use `:Ag` command in fzf plugin/
|\<selection\>ga\<selection\>\<rule\> | An alignment rule is a predefined set of options for common alignment tasks, which is identified by a single character, such as `<Space>`, `=`, `:`, `.`, `\|`, `&`, `#`, and `,`.<br><br> e.g. `vipga=`, `gaip=`, `gaip*=`, `gaip**=`.<br><br>p.s.<br>1. `<C-x>` to use regular expression<br>2. `<C-p>` to use live interactive mode<br>3. `<Left>/<Right><character>` to align left/right character<br>4. `-` to align last occurrences|
|gc\<selection\>    | comment out the selection|
|cs\<source mark\>\<target mark\>| change the source mark to target mark, if source mark is text object then add target mark like `cs2w'`|
|ds\<target mark\>  | delete the target mark|
|\<Leader\>hp       | open git diff window|
|\<Leader\>hs       | stage the section of cursor in git|
|\<Leader\>hu       | undo the section of cursor to origin in git|
|[c               | jump to previous diff|
|]c               | jump to next diff|


|insert mode | description|
|:-----------|:-----------|
|;;    | ESC |
|(     | ()  |
|"     | ""  |
|'     | ''  |
|[     | []  |
|{     | {}  |
|\<C-s\> | save|


|visual mode | description|
|:-----------|:-----------|
|\<S-h\>     | Move currently selected block left |
|\<S-j\>     | Move currently selected block down |
|\<S-k\>     | Move currently selected block up   |
|\<S-l\>     | Move currently selected block right|
