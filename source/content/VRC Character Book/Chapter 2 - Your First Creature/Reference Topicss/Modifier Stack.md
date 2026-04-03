Modifiers are a non-destructive way to affect objects. Arrays, mirroring, deformations, subdivision, they do a lot.

![](Pasted%20image%2020260403130811.png)
_The object on the right is the cube on the left with a stack of modifiers turned on._

We access the modifier stack by selecting an object that supports them, the clicking the wrench icon in the properties panel.
![](Pasted%20image%2020260403130830.png)

Clicking 'Add Modifier' will present us with a menu full of modifiers. There's a search option at the top, which we can click and start typing 'subdivision' to find the Subdivision modifier and add it.

If we go into edit mode with the modifier added, we can see what's happening.
![](Pasted%20image%2020260403130843.png)

The mesh data hasn't changed. The vertices are still in the same position in the mesh data. There is just now a procedural step being applied between the data and the rendering step that divides each face and smooths their positions.

If we add an Array modifier, it appears below the SubD modifier in the stack. Some modifiers like Array provide a 3D gizmo to tweak their effects if you click them in the stack while the object is selected.
![](Pasted%20image%2020260403130857.png)

Then we can add a Simple Deform modifier, and it appears last. I've collapsed the other modifiers to save space.
![](Pasted%20image%2020260403130907.png)

Once we have a few modifiers, we can move them up and down the stack by clicking and dragging on the right side of their headers. If you try reordering them, you'll see the result changes. The stack is resolved from top to bottom. 

There are some important buttons on the modifier next to its name:

![](Pasted%20image%2020260403131034.png)

From left to right, they:
1. Toggle the cage in Edit mode to reflect the modified positions.
2. Enable the modifier while in Edit mode.
3. Toggle the modifier in the viewport.
4. Toggle the modifier in renders.

The little arrow next to those is a menu for applying, removing, duplicating, or sorting modifiers.