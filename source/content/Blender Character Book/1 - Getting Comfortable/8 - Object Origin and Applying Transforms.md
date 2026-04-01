### Video: Object Origin and Applying Transforms

pending upload

---

In edit mode, press `A` to select your whole cube, then press `G` and move it somewhere to the side of the screen.

![[Pasted image 20260331142915.png]]

Now go back to Object mode and try rotating or scaling your cube. Suddenly, the significance of this orange dot in the scene will become apparent. Your transformations aren't relative to where you _see_ the cube, they're relative to the Object - at least by default.

This is a very important concept to get a handle on, as it can either confound you or be a powerful tool depending if you understand what's going on or not.

If you recall when we discussed object properties, we saw each object carries its own transform data.
![[Pasted image 20260331143413.png]]

This transform data can have a huge impact on other operations. For example, I have two cubes that are visually the exact same size. One of them has an object scale of 2 due to me editing it in Edit mode and then scaling it up in Object mode.

![[Pasted image 20260331143952.png]]

Now what happens if I run the exact same Bevel modifier on both of them with default settings?

![[Pasted image 20260331143829.png]]

You can see that the high level Object scale can affect other things we do with those objects. 

## Apply Transforms
```
Apply Transform : Ctrl-A
```
To make our objects behave consistently, we want to be able to return them to a consistent baseline without changing their visual appearance. Modify a cube, select it, and press `Ctrl-A`.

![[Pasted image 20260331144413.png]]

The options in this menu important to us now are the first section. 

Applying Location will keep the object where it is, but return the Object Origin back to the World Origin.

Applying Rotation will make the object's axes of rotation align with the world.

Applying Scale will return its scaling back to 1 on all axes.

All Transforms will do all three, and Rotation and Scale will do just those two. It's important that they're broken up like this - often you will only want to normalize scale while retaining your other transforms, as you'll see over time.