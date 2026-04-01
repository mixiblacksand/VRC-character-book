Often you want to select a whole bunch of vertices at once. There's quite a few different ways to accomplish this, depending on what you want.
## Loop Select
```
Loop Select : Alt + LMB on an edge or between faces
```
In Edit mode, holding Alt while clicking will select an edge or face loop as far as it can. Certain types of geometry like corners or triangles will stop it. The [[4 - Working with Objects#The Redo Menu|redo menu]] will allow you to toggle when it stops to some degree.
![[Pasted image 20260331211813.png]]
![[Pasted image 20260331211859.png]]
_Edge and Face Loop selections._

As with most selections, you can hold `Shift` while selecting to select multiple things.

## Shortest Path Select
```
Path Select: Ctrl + LMB
```

Sometimes you don't want a whole loop, just part of one - or a selection that isn't quite a proper loop. In this case, you can hold `Ctrl` and click on elements to select a path between them. You can keep clicking while holding down control to keep extending the path.
![[Pasted image 20260331212728.png]]
_The result of Ctrl-LMB on 1 and then 2._

## Select More/Less
```
Select More : Ctrl + Num Plus
Select Less : Ctrl + Num Minus
```
Selecting an element and pressing More will select all adjacent elements. Pressing Less will deselect the outermost elements.

If you do not have a numpad, these options can be found in Select > More/Less. You can right click on them and change the shortcut to something you like.

