We frequently make things that are symmetrical, and the Mirror modifier is a powerful way to do that.

![](Pasted%20image%2020260403170717.png)

![](Pasted%20image%2020260403170705.png)

This Suzanne model has the default mirror modifier applied. Looking at it in Edit mode, we can see that when we select the geometry and move it to one side of its object origin, the modifier creates mirror geometry for us. You'll notice the duplicate has no verts or edges highlighted on it, as we cannot select and manipulate it directly.

# Bisect

![](Pasted%20image%2020260403170930.png)

If we enable the Bisect option, the mesh will be cut down the axis of symmetry and anything on the destination side ignored.

# Flip 
The Flip option will change which side of the axis is the source and the destination.

# Mirror Object

![](Pasted%20image%2020260403171109.png)
Mirror object allows us to mirror across something other than the object origin.

# Clipping
The clipping option will make the axis of symmetry 'sticky.' Any verts exactly on it will stay on it. This is useful when working with a mesh that has been cut in half to prevent gaps appearing down the axis.

# Merge
When applying the modifier, any of the generated verts within the range specified here will be merged with their mirror pair. Again this is useful when working with a bisected mesh.