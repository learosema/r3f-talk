# React-Three-Fiber aka R3F

---

# Hi! I'm Lea Rosema

- she/her, Digital Artist @ S2
- [https://lea.codes/](https://lea.codes/)
- [https://codepen.io/terabaud/](https://codepen.io/terabaud/)
- [@terabaud](https://twitter.com/terabaud)

---

# Slides to my talk

- [https://terabaud.github.io/r3f-talk](https://terabaud.github.io/r3f-talk/)

---

# What is React Three Fiber?

- React and Three.js, together
- Three.js is a 3D engine for the web
- React is a component-driven JS library for building UI

---

# Anatomy of a three.js application

- create scene
- setup lights
- add meshes to the scene
- initialize renderer
- add objects to the scene
- initialize resize event
- initialize render loop

---

# Hard things

- hard to interact with objects inside the canvas
- no onClick, onHover handlers on objects
- state management is up to you
- manual handling of render loop
- manual handling of window resize

---

# This is where React comes in

- Declarative language
- built-in state management (useState hook)
- built-in onClick handlers
- rendering is handled by React
- but React itself can only handle DOM elements

---

# R3F to the rescue

- React has a "Reconciler"
- allows React to handle things other than the DOM
- R3F creates the bridge between JSX and Three.js
- Think of Spheres, Lights, Cameras as React Components
- There can even be a storybook containing these components

---

# DEMO

- [https://codesandbox.io/s/r3f-helloworld-wyi53](https://codesandbox.io/s/r3f-helloworld-wyi53)
- This demo uses TypeScript + React
- react-three-fiber
- @react-three/drei which is a library that contains Three.js components for R3F

---

# Thank you 👩‍💻

## Further Resources

- [https://threejs.org](https://threejs.org)
- [https://github.com/pmndrs/react-three-fiber](https://github.com/pmndrs/react-three-fiber)
- [https://github.com/pmndrs/drei](https://github.com/pmndrs/drei)
