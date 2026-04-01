We often need symmetry in character art. The mirror modifier is one of my most used. For best results, it requires a little bit of prep. I'll show you how to use it manually, and then we'll install our first extension to automate this common process.
## Mirroring Manually
Make a cube and add a Mirror modifier to it. Go into Edit mode and move a vertex around. You'll see you get mirrored geometry, but it is fully duplicated across the object origin.
![[Pasted image 20260331193415.png]]

We can improve the situation by enabling the Bisect X option in the modifier. Now the final geometry is sliced down the X axis, but we still have extraneous data on the target side. There are also no points along the middle line for us to edit.
![[Pasted image 20260331193556.png]]

We can quickly cut the mesh down the center like with [[3 - Edit Mode Symmetry#Symmetrize|symmetrize]]. If we check Clipping in the mirror modifier, the verts on the center line will 'stick' to that plane, making sure we don't get a gap.

## Select Side of Active
Now we just have the extra geometry on the destination side confounding things. To quickly delete this, select one of the center verts. Go to Select > Side of Active. All the verts to the positive X side of the chosen vert will be selected. I personally prefer to work on the positive side, so I open the [[4 - Working with Objects#The Redo Menu|redo menu]] and change the selection to Negative Axis. Then press X and choose Faces.

Now if we turn off the Mirror modifier, we'll see that we only have 'real' data for half of the cube, and the other half is entirely handled by the modifier.
![[Pasted image 20260331194619.png]]

## Extension: Auto Mirror
That's a lot of steps for something I do over and over. Let's install our first extension to simplify our lives. Go to Edit > Preferences > Get Extensions. If you didn't allow online access when setting up Blender, do so now. Type 'auto mirror' into the search box and click Install on the result that comes up. The name should change from greyed out to white, indicating a successful install and activation.
![[Pasted image 20260331195100.png]]

## Side Panel
```
Toggle Side Panel: N
```
Auto Mirror, like many extensions, puts its menu in a side panel we have not talked about yet. Press `N` in the 3D viewport to toggle it on. A collection of panes and tabs will slide in from the right.
![[Pasted image 20260331195234.png]]

By default we can get some information on the selected object, tool, and camera here. Now that we've added Auto Mirror, the 'Edit' tab has appeared. If we click that, we can expand the Auto Mirror panel and see its controls.
![[Pasted image 20260331195353.png]]

Make a new mesh, select it, and click 'AutoMirror.' All the work we did above will be done in one step. This is great, but going into the side panel to access it can be cumbersome. Luckily, Blender has a place to store commonly used functions.

