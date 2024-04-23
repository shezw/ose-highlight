# ose-language-highlight README

This extension only provides syntax highlight for .ose files in vscode. 

```vim
let s:str = "HelloWorld!"

function s:Hello()
    echom s:str
endfunction
```


```ose
Package highlight

Class Main

" @accessible
function! s:Main() 
    echom "This is ose"
endfunc

UnitTest
function! s:TestMain() dict
    echom "Running Test"
    return 0
endfunc
```

based on [vscode-viml](https://github.com/XadillaX/vscode-language-viml)
