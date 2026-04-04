What we mean by retopology is taking a mesh with a form we want and remaking it with an edge flow and poly count that suits our needs. 

Consider our sculpt as we left it last time and a retopologized version next to each other:

![](Pasted%20image%2020260403221634.png)

That's not a darker material on the sculpt, it just has that many verts and edges. While it may be the shape we want, we can't go further with that model alone.

We'll accomplish this by using a handful of tools, the retopo display mode, and some problem solving skills to trace the new topology over the top of the sculpt.

![](Pasted%20image%2020260403221918.png)
_The two meshes on top of each other, but with retopo display active on the lower poly one._

Once we have good edge flow established, we'll subdivide the mesh and use a Shrinkwrap modifier to conform the result to the original mesh.

On a more complex project we would then refine the result manually, but we'll leave it at that point for our simple learning character.

# Edge Flow and Face Loops

When I say edge flow, what I mean is that we want to lay out our edges in such a way that they follow the underlying form instead of working against it.

![](Pasted%20image%2020260403222443.png)

Not only will it look the way we want, good edge flow makes everything else we do easier. We can easily select parts of our mesh if the edges are orderly, which makes UV unwrapping, weight painting, and texture paint masking easier. When the mesh animates, having the edges running orthogonal to the direction of bending joints will let them compress and stretch smoothly.

Manual retopo takes practice, but it gives you a lot of power compared to using an automatic solution and then struggling with later steps because your edges spiral all over your body.

# My Approach to Retopo
As I already mentioned, I like to work big first and then subdivide. On a more detailed model, I'll do a loose retopo, subdivide, shrinkwrap, and then do another pass of retopo where I refine details like mouths and ears.

While I normally use a few bigger addons for retopo, in this book we're going to stick to the basics. We'll use the *F2* plugin that comes with Blender to improve the functionality of the `F` key and *LoopTools* to help smooth out our edge loops, but nothing fancy.