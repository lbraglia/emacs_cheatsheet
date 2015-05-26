## An(other, minimal,) `emacs` cheat sheet

### Help

|Keystrokes  | Action     |
|------------|------------|
|`C-h k`| Describe command from keystrokes|
|`C-h f`| Describe command from function name|
|`C-h ?`| help suggestions|
|`C-x 1`| to close `*Help*` buffer|

### Files/Buffers

|Keystrokes  | Action|
|------------|------------|
|`C-x C-f`   | Create buffer/Open file|
|`C-x C-s`   | Save buffer to file|
|`C-x C-w`   | Save to file named as|
|`C-x i`     | Insert|
|`C-x C-b` | list available buffers
|`C-x b`   | move to a given buffer or create a new one
|`C-x ->`   | move to next buffer in the list
|`C-x <-`   | move to previous buffer in the list
|`C-x k`   | kill a buffer (remove from the list)

### Managing windows

|Keystrokes  | Action|
|------------|------------|
|`C-x 2`   | split windows horizontally
|`C-x 3`   | split windows vertically
|`C-x o`   | go to another other window
|`C-x 0`   | close the current window 
|`C-x 1`   | close all but the current window 


### Moving

|Keystrokes  | Action|
|------------|------------
|`C-p `      | previous line|
|`C-n `      | next line|
|`C-a `      | line beginning|
|`C-e `      | end of line|
|`C-f `      | forward a character|
|`C-b `      | backward a character|
|`M-f `      | forward a word|
|`M-b `      | backward a word|
|`M-a `      | beginning of sentence|
|`M-e `      | end of sentence|
|`M-{ `      | beginning of paragraph|
|`M-} `      | end of paragraph|
|`C-q C-l`   | insert a page break |
|`C-x [`     | previous page|    
|`C-x ]`     | next page|    
|`C-v`       | next screen|    
|`M-v`       | previous screen|    
|`M-< `      | beginning of buffer|
|`M-> `      | end of buffer|
|`M-g M-g`   | go to line|
|`C-l`       | (repeated) center display as desired|

### Select/mark region

|Keystrokes  | Action|
|------------|------------
|`C-space`     | by line
|`C-x space`   | by column
|`C-x C-x`| go to the other end of marked region
|`M-h` | mark paragraph
|`C-x C-p` | mark the current page
|`C-x h` | mark the whole buffer

### Editing

|Keystrokes  | Action|
|------------|------------
|`C-d`       | Delete one char forward|        
|`M-d`       | Cut one word forward   |
|`C-d`       | Delete one char backward|        
|`M-DEL`     | Cut one word backward  |
|`C-k `      | Cut to the end of line|
|`C-w `      | Cut selected region|
|`M-w`       | Copy selected region|
|`C-y`       | Paste last cut things|
|`M-y`       | repeatedly after a `C-y`: go through the ring of killed stuff to choose what to paste|
|`C-x u`     | Undo|

### Search

|Keystrokes  | Action|
|------------|------------
|`C-s` | Incremental search forward, type
|`C-r` | Incremental search backward, type
|`C-s C-w` | Incremental search forward, following word
|`M-x word-search-forward` | Exact search forward
|`M-x word-search-backward` | Exact search backward
|`C-M-s` | incremental regexp search forward
|`C-M-r` | incremental reg-ex search backward
|`C-g` | Interrupt search, go where search began

### Replace

|Keystrokes  | Action|
|------------|------------
|`M-%` | Query replace
|`C-M-%` | Regexp query replace 
|`M-x replace-string`| Replace string without querying

### Abbreviations

|Keystrokes  | Action|
|------------|------------
|`C-x aig` | add a global abbreviation (with last word as abbrev)
|`C-x ail` | add abbreviation for a mode (with last word as abbrev)
|`M-x unexpand-abbrev` | undo last word abbreviation

### Wrapping/Indenting/commenting text

|Keystrokes  | Action|
|------------|------------
|`M-q `      | wrap paragraph|
|`M-x fill-region`  | wrap paragraphs from selected region|
|`M-x indent-region`  | indent lines from selected region|
|`M-;`  | comment line or selected region

### Accessing menu

```
M-`
```

### Shell

|Keystrokes  | Action|
|------------|------------
|`M-! `      | execute shell command|


### Repeating a command

|Keystrokes  | Action|
|------------|------------
|`M-n CMD_KEYSTROKES` | repeat n times `CMD_KEYSTROKES`|
|`C-u CMD_KEYSTROKES` | repeat 4 times `CMD_KEYSTROKES`|
|`C-u C-u CMD_KEYSTROKES` | repeat 16 times `CMD_KEYSTROKES`|
|`C-u C-u C-u CMD_KEYSTROKES` | repeat 64 times `CMD_KEYSTROKES`|

and so on

### Spell checking

|Keystrokes  | Action|
|------------|------------
|`M-x ispell-change-dictionary` | set spelling dictionary|
|`M-$` | ispell check a single word
|`M-x ispell-region` | check selected region|
|`M-x ispell-buffer` | check current buffer|
|`M-x flyspell-mode` | use flyspell for spelling on the fly|
|`C-g` | Stop spell checking


