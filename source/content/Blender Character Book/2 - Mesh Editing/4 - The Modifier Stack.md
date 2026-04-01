Modifiers are a non-destructive way to affect objects. Arrays, mirroring, deformations, subdivision, they do a lot.
![[Pasted image 20260331190449.png]]
_The object on the right is the cube on the left with a stack of modifiers turned on._

We access the modifier stack by selecting an object that supports them, the clicking the wrench icon in the properties panel.
![[Pasted image 20260331191307.png]]
Clicking 'Add Modifier' will present us with a menu full of modifiers. There's a search option at the top, which we can click and start typing 'subdivision' to find the Subdivision modifier and add it.

If we go into edit mode with the modifier added, we can see what's happening.
![[Pasted image 20260331191342.png]]

The mesh data hasn't changed. The vertices are still in the same position in the mesh data. There is just now a procedural step being applied between the data and the rendering step that divides each face and smooths their positions.

If we add an Array modifier, it appears below the SubD modifier in the stack. Some modifiers like Array provide a 3D gizmo to tweak their effects if you click them in the stack while the object is selected.
![[Pasted image 20260331191551.png]]

Then we can add a Simple Deform modifier, and it appears last. I've collapsed the other modifiers to save space.
![[Pasted image 20260331191711.png]]

Once we have a few modifiers, we can move them up and down the stack by clicking and dragging on the right side of their headers. If you try reordering them, you'll see the result changes. The stack is resolved from top to bottom. 

You can toggle a modifier on and off by clicking the monitor or camera icons. The monitor will disable it in the viewport, while the camera will disable it in the final render. 

The two icons to the left control the modifier's visibility in Edit mode. The leftmost one will make the mesh data appear in its modified location instead of its absolute one.
![[Pasted image 20260331192551.png]]
_A cube with a SubD modifier and cage display on._

Turning off the button second from the left will disable the modifier entirely while in Edit mode.