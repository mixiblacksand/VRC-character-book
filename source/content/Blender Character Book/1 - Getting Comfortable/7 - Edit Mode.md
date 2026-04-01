### Video: Edit Mode

pending upload

---

```
Mode Menu : Tab
Toggle Edit Mode : Ctrl-Tab
```
We've been in Object Mode this whole time, as indicated by the dropdown in the upper left of the 3D viewport:

![[Pasted image 20260331141711.png]]

If we want our cube mesh to be anything more complex than a cube, we need to use these other modes. Our first stop is Edit Mode. You can change to it using the dropdown, but I prefer to use `Tab` (or `Ctrl-Tab` if you elected not to change that option during [[1 - Installing Blender Portable#Configure]].)

![[Pasted image 20260331141947.png]]
## Transformations in Edit Mode
```
Vertex Select : 1
Edge Select : 2
Face Select : 3

Slide Element : Double Press G
Push/Pull Element : Alt-S
```
Either way, once you enter edit mode you should see your cube's edges and vertices stand out. You'll default into vertex mode, so try clicking on a vertex and using `G` to move it around just like you did the cube.

![[Pasted image 20260331142208.png]]

Pressing `1`, `2`, or `3` on the keyboard will switch between vertex, edge, and face mode. If you grab an edge or face, you can scale or rotate them.

Something new you can do in Edit mode is _sliding_ elements. Select a vertex and press `G` twice. Now when you move your mouse, the vertex should move along its connected edges.

You can also _push and pull_ elements. Select one and press `Alt-S`. It will move along a line perpendicular to its surface (a thing called its _normal_ - a word we'll be using a lot later on.)
