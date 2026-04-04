# Addons
We're going to want two small addons in this process.

Go to Edit > Preferences > Get Extensions. In the search bar, search for 'F2' and install it, then 'LoopTools' and install it.
# F2
F2 does one thing that is incredibly useful. If we have a corner vert like this and press F, it will fill in the next quad in the sequence:

![](Pasted%20image%2020260403224436.png)

![](Pasted%20image%2020260403224447.png)

By default Blender will just make a triangle there. F2 will save us a lot of clicks.

# LoopTools
LoopTools has a few useful functions, but a big one for us is the Relax function. 

![](Pasted%20image%2020260403225305.png)

![](Pasted%20image%2020260403225344.png)

# Retopo Overlay
While in Edit Mode, the overlay menu has a Retopology option:

![](Pasted%20image%2020260403225859.png)

This makes the mesh you're working on visible through other meshes, up to the distance you set. You will likely find the default distance too small, so turn it up until you have a good view of the side you're working on without seeing the back of the mesh as well.

# Creating Strings of Vert and Faces
While in Edit Mode, `Ctrl-RMB` will create a new vertex or face depending on your selection.

With vertex mode enabled but nothing selected, it will create a single new vert.
With a vertex selected, it will connect the new vert to the old.
With one or more edges selected, it will create new edges with faces bridging them.
With a face selected, it will extrude the face to the cursor position.

If you have Face Project snapping enabled, the creation of these new elements will obey that snapping.