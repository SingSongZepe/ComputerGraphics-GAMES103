# ComputerGraphics-GAMES103

Thanks for GAMES platform, which let Chinese native speakers learn Computer Graphics easier.

[games-cn.org](https://games-cn.org/)

This is my solutions for assignments of GAMES103.

### Assignments

pay attension to that in the `assignment${i}` dictory, the unitypackage file with prefix `sszp` is my work, while the other one is the origin environment file

- first assignment: rigid bunny

> path: `./assignments/assignment1/sszp_rigid_bunny.unitypackage`

> when implement, pay attension to:
> 
> - how to eliminate sliding effect.
> 
> - how to do impluse method to a rigid body.
> 
> - how to do penalty method to a particle of the rigid body in shape matching.

- second assignment: cloth

> path: `./assignments/assignment2/sszp_cloth.unitypackage`

> when implement, pay attension to:
> 
> - how the edges are constructed.
> 
> - how to calculate the gradient of a vertex and apply to its velocity updating.
> 
> - how to fix some vertex so that its position doesn't change (when you fix some vertices you'll easily to notice that the cloth easily intersect with itself).
> 
> > ![](./res/img/p1.png)
> 
> -  how to implement the chebyshev acceleration.
> 
> - how to use projection function to do strain limit to correct the mesh.
