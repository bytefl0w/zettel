So i just went through the trouble of creating the initial NewZettel command for whenever I want to create a new Zettel. Below is currently how I know to make vimscript commands and make them callable by mapping them.

```
function! Foobar()
    ...
endfunction

nmap <leader>foo :call Foobar()<CR>
```

I'll probably find a better way of making functions within vim, but this is good for now.

```
#vim #vimscript
```
