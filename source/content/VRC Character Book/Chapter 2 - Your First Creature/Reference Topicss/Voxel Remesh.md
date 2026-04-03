Blender's has a few ways of taking an existing mesh and giving it new topology automatically. The one we'll use most frequently is Voxel Remesh.

Voxel Remesh creates a new mesh that fits the volume of the existing one using a resolution you set. 

You can interactively set the resolution in Sculpt mode by pressing R and moving the mouse left or right.

![](Pasted%20image%2020260403162231.png)

You can then press `Ctrl-R` to execute a remesh.

![](Pasted%20image%2020260403162332.png)
_Before and after Voxel Remesh_

The big caveat about voxel remesh is that it is very easy to loose detail or get unwanted bridges if your resolution is insufficient. 

![](Pasted%20image%2020260403162813.png)

In this case sharp detail was sculped on the left with crease and pinch brushes. When running remesh with the default setting, the sharpness was lost.

![](Pasted%20image%2020260403162948.png)

In this case, individial parts of a mesh that were meant to be separate were bridged because the remesh resolution was too low. This is a very common problem when working with fingers or toes and remesh. The problem parts will either need to be splayed more (the Pose brush helps here) or a higher resolution is needed.