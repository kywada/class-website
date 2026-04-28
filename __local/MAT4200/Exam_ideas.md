Ideas: You can work with anyone that you have not worked with before.

- Prove that normal curvature only depends on tangent direction.
- Define isometry
- You prove it with Lagrange multipliers. We want to maximize f(v) = v^T A v subject to the constraint g(v) = v^T v - 1 = 0.

The Lagrange condition is grad f = lambda * grad g. Computing:

- grad f = 2Av (using symmetry of A)
- grad g = 2v

So the condition becomes:

2Av = 2 lambda v

i.e. Av = lambda v, which is exactly the eigenvector equation. []

The symmetry of A is essential -- it's what gives you grad(v^T A v) = 2Av rather than (A + A^T)v. Without it the critical points of the Rayleigh quotient are not eigenvectors of A but of its symmetrization (1/2)(A + A^T).

Problem 1. Normal curvature and geodesics.
- Derive curvature formula in terms of \frac{\| \text{r1}\times \text{r2}\| }{\| \text{r1}\| ^3}
- Compute the normal curvatures via Frenet Frame, finding normals of surface, etc.
- Then up to principal curvatures, seeing that they maximize/minimize normal curvatures.
- Geodesic curves measured extrinsically, verify that some curve is a geodesic.

Problem 2.
- Hyperbolic geometry and the hyperbolic plane.
- Hyperbolic trig functions.
- Horocycle? Idk.
- Embedding of torus vs flat torus?

Problem 3.
- Modern differential geometry
- Covariant derivative
- Connection
- Etc?
