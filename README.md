# threejs-playground

Experimenting with Three.js

## Setup

Clone the repo. No npm/yarn install required.

## Run

Just open `index.html` in a web browser.
Recommended for dev: install the `Live Server` extension of VSCode and click on "Go Live" in the status bar.

## Notes

### WebGL

- Before WebGL: only desktop could do 3D graphics.
- Why WebGL?
  - Draw in 3D
  - Raw power, even in 2D

### Three.js

- Three.js: WebGL library. WebGL uses `<canvas>`.
- Without three.js: huge amount of code needed (ex: rotating cube, 200 loc VS 25 loc)

3 things to set up:

1. **Scene** (description of the 3D world)
2. **Camera** (ex: PerspectiveCamera, which uses a FOV, aspect ratio, near plane and far plane)
3. **Renderer** (WebGL, CSS 2D, CSS 3D, SVG)

=> We _render_ a _scene_ with a _camera_.

- Many building blocks: cube, cone, sphere, ...
- Can import 3D models from tools such as Blender
- **Vertex**: a point. Triangle = 3 vertices.
  - Position (x, y, z), but also rendering info (color, reflectance, ...)
- **Geometry**: vertex data of some piece of geometry like a sphere, cube, ...
- **Material**: color or texture (rock, wood, skin, ...). Can react or not to shadows.
- **Mesh**: geometry + material. Complete object that can be added to the scene.
- **Shader**: a script for scene post-processing such as filters and special effects (ex: blur, volumetric lighting, bump mapping, ...)

## Online resources

- [Official docs](https://threejs.org/docs/index.html#manual/en/introduction/Creating-a-scene)
- [Crash course YouTube video (43min)](https://youtu.be/6oFvqLfRnsU)
- [An introduction to Three.js (from Humaan studio)](https://humaan.com/blog/web-3d-graphics-using-three-js/)
- [Three.js fundamentals](https://threejsfundamentals.org/)
- [WebGL fundamentals](https://webglfundamentals.org/)
- [Official examples](https://threejs.org/examples/#webgl_animation_cloth)
- [GreenSock (timeline animations)](https://greensock.com/gsap/)
- [PlayCanvas (web-based game engine and editor)](https://playcanvas.com/)
- [PixiJS (2D WebGL renderer)](https://www.pixijs.com/)
- [Vertex (Wikipedia)](<https://en.wikipedia.org/wiki/Vertex_(geometry)>)
- [Shader (Wikipedia)](https://en.wikipedia.org/wiki/Shader)

## Books

<img src="https://static.packt-cdn.com/products/9781788833288/cover/smaller" alt="Learn Three.js" />
