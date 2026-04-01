So far we've only been manipulating the cube as an _object_. Objects are a sort of container for related data in Blender. If I go into the outliner and expand the entry for the cube, we can see it is an object (orange icon) that contains mesh data (green icon,) and that mesh data is associated with material (red icon.)

![[Pasted image 20260331135717.png]]
### Video: Properties Panel

pending upload

---

If we want to see and edit the data the object contains, the first place we want to look is the Properties pane.

![[Pasted image 20260331140218.png]]

The properties pane contains a LOT of data. The upper tabs control information about the scene, world, rendering, and other things we won't worry about just yet. 

The tabs circled in red are the ones for the currently selected object. If you click on the light, cube, and camera, you'll see they have some different tabs because they contain different data. The camera has options for focal length, the light has options for color and intensity, and the mesh has all sorts of toys we'll play with throughout the course.

For instance, if you grab, rotate, and scale your cube, you can see those values are changing in the Object Properties tab. If you want a precise value, you can come here and type it in. You can also type math into these text fields. If you wanted its X location to be the square root of 22 divided by 2.3 for some reason, you could type `sqrt(22)/2.3` into the Location X field and press enter and it would move to 2.03931 meters.