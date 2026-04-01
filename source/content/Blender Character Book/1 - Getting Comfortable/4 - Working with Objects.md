### Video: Select, Delete, Add

![](https://youtu.be/H8Ycy28JCTU)

---

By default, Blender loads up this scene:
![[Pasted image 20260331114557.png]]
## Selecting
```
Select : LMB
Select Multiple : Shift-LMB
Select All : A
Select None : Double Press A
```
On the left is a Camera object. These are used as points to render from. Left click on it, and it will turn orange to indicate it is selected. If you look at the upper right, you can see it selected in the Outliner.
![[Pasted image 20260331125405.png]]
You can click here to select objects as well. Click 'Cube', and the cube will be outlined in orange to show it's selected. 

Press `A`, and everything visible will be selected. Press `A` twice quickly, and everything will be deselected.

`Shift-LMB` on each object in the 3D viewport in turn. You'll notice the last one you clicked on is always highlighted in a brighter color than the others. That is the one that is our _active object_. This is an important concept for many operations we'll run into.
## Deleting
```
Delete : X
```
Now with everything selected, press `X` and choose Delete. Congratulations! You've performed the time honored Blender tradition of erasing everything in the default scene. Untold default cubes have met this fate.
## Adding
```
Add Object : Shift-A
```
Now press `Shift-A`. A menu pops up with things you can add to the scene. Click Mesh > Monkey to create a copy of Suzanne, the Blender mascot.
![[Pasted image 20260331130415.png]]

## The 3D Cursor
### Video:  The 3D Cursor

![](https://youtu.be/c3Gc1EWMXEY)

---

```
Move 3D Cursor to Mouse Cursor : Shift-RMB
Move 3D Cursor Menu : Shift-S
```
The location the new mesh was created was determined by the _3D Cursor_. That's the little white and red crosshair in the center of the world. `Shift-RMB` in the 3D viewport moves the 3D cursor to where you clicked. By default, it will stick to the surface of any objects you click on. Try moving it onto Suzanne's head and adding a torus.
![[Pasted image 20260331130727.png]]

We can also move the 3D cursor around with `Shift-S`. Press it now and select 'Cursor to World Origin' to return it to its default location.
## The Redo Menu
### Video: Redo Menu

![](https://youtu.be/M5wF1EpcChg)

---

```
Redo Menu : F9
```
What if you want a torus that's thicker, or thinner, or more or less polygons? When we perform many actions in Blender, we can use the Redo menu to alter their result. 

Press `A`, then `X`, and clear the scene. Now press `Shift-A` and add a cone. In the lower left of the 3D viewport, you'll see a little box labeled 'Add Cone.' Click on it to expand it:
![[Pasted image 20260331132906.png]]
These are all the parameters of the last operation that can be changed. Try either clicking on the boxes and changing the numbers, or by clicking and dragging left or right on the boxes to make them act like sliders. The resulting cone changes.

If you happen to click somewhere else in the 3D viewport the Redo menu may disappear, but you can recall it by pressing `F9`. As long as you haven't performed another operation, you can keep editing the cone's parameters. 

However, you can only ever redo the _last_ operation you made. As soon as you add another object, for instance, this cone's parameters are locked in.
