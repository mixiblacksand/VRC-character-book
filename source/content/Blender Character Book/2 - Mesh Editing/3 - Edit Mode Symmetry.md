As soon as you start adding more points, you're probably realizing it's a huge pain to edit them on both sides of the model. You may have even accidentally gotten your model lopsided. Before we go any further, let's address how to enforce symmetry.
## Symmetry Toggles
In the upper right of the 3D viewport, there's a little section with a butterfly for controlling symmetry:
![[Pasted image 20260331155803.png]]
You can select one or more of the axes and Blender will attempt to move elements on the other side of the object on that axis.

Note that I said on the other side of the _object_, not the _world_. This is a case where the location and orientation of the object origin makes a huge difference.

![[Pasted image 20260331160811.png]]

Here X Symmetry works as expected, because the object origin and geometry are in alignment. I've turned off the world grid to emphasize it's not relevant. 

![[Pasted image 20260331160900.png]]

In this case, the object origin is not in the center of the object, nor does it match rotation, so edit mode symmetry does not help.

## Symmetrize
```
Edit Mode > Mesh > Symmetrize
```
So what to do if you're already got a lopsided mesh? You can forcefully copy one side of the model to the other with the symmetrize function. Again, this is an object space function.

Go into Edit Mode. Select the vertexes you want to symmetrize on both sides of the mesh. Go to Mesh > Symmetrize. By default, it copes from the negative X to positive X, but you can change that in the [[4 - Working with Objects#The Redo Menu|Redo Menu]].
![[Pasted image 20260331161455.png]]
![[Pasted image 20260331161515.png]]
_Before and After_

Note that symmetrize is a destructive process. If you select verts on both sides like I've done here, it will delete and replace the verts at the destination, along with any data like vertex colors or UV coordinates they have.

There's a more robust way to enforce symmetry in the form of the Mirror Modifier. First we need to discuss what modifiers are.