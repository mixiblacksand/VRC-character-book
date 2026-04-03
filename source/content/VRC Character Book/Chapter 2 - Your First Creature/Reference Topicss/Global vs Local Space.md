In our 3D scene, we orient ourselves with the X,Y, and Z axes. There are a number of different sets of axes we can refer to, however. This menu at the top of the 3D viewport lets us pick an orientation.

![](Pasted%20image%2020260403123955.png)

Most commonly, we care about Global or Local orientation.

# Global Orientation
When we speak about Global Space, we're referring to the axes that we see on the ground plane. They're a constant, fixed reference point in our scene.

![](Pasted%20image%2020260403123553.png)

This cube has been rotated in object mode. If we turn on the move gizmo set to global space, we see the axes don't align with the faces of the cube.

# Local Orientation

![](Pasted%20image%2020260403123611.png)

Here we've switched the orientation to Local space. Now we can move the cube along its own axes, taking into account its rotation relative to the world.
# Why This Matters To Us

In this course, we're mostly interested in how we can use this knowledge as a modeling tool. Consider this scenario: You've made a shape by extruding up along the Z axis.

![](Pasted%20image%2020260403125027.png)

You use it somewhere in the scene, snapping it onto a surface, rotating it in the process.

![](Pasted%20image%2020260403125150.png)

Now you realize you want to reshape this cylinder a bit, pulling out the top face. If you try to move it in the global Z, this happens:

![](Pasted%20image%2020260403125257.png)

However, the _local_ Z axis is still oriented along the cylinder, so moving it along that axis produces this:

![](Pasted%20image%2020260403125336.png)

We can see that keeping our object's rotation - that is, not applying it after rotating in object mode - can be a helpful modeling tool. It's also crucial in animation, though we won't be touching that much if at all.
# Shortcut to Local Transform
If you're performing a transformation like grab, scale, or rotate, you can press an axis letter _twice_ to lock to the local instead of global axis.