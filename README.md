## 3D Equation Grapher

See it in action [here!](https://zsteinberg.github.io/3DGrapher)

## What is it?
A webGL program to graph functions of the form f(x,y,z)=0 in interactive 3D! Made for a presentation and hosted here because others might find it useful. Fancy equation rendering included.

To use, mouse over the bottom part of the page and type in a function involving the variables x, y, z, and time. You need to enter multiplications with a *, but they'll be hidden in the fancy LaTeX-ed output once you stop editing.

# Credits

Code adapted from [threejs.org's marching cubes example](https://threejs.org/examples/webgl_marchingcubes.html). It's unpolished and unoptimized, but it graphs things in 3D well. Simulation resolution will automatically drop until 30FPS or greater is maintained. Math rendering done with [MathQuill](https://mathquill.com).
