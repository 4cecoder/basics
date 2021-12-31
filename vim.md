# modes

"i" is insert mode (edit mode)

escape key is escape mode (navigation)


## use in escape mode:
```vim
r         " = replace character with what you type next
s         " = delete character and insert

shift + i " = begining of the line
shift + a " = go to end of line
u         " = undo 
```
## MOVEMENT:
```vim
b   " = go back one word
w   " = go forward one word
h   " = left
j   " = down
k   " = up
l   " = right  
```
## ERASE:
```vim
dd  " = delete line
dj  " = delete down
dk  " = delete up 
dw  " = delete word ahead
db  " = delete word behind
```
## COPY:
```vim
yy  " = copy line
yj  " = copy down (2 lines)
yk  " = copy up (2 lines)
p   " = paste
```
