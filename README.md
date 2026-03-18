# GVIS
Web-based Genome Visualizer. Written in C (WASM) + JS.
Uses the [ALICE engine](github.com/matt-const/alice).

## Integration
The whole application is an *HTML5 canvas*, controlled by gvis_canvas.js. (See index.html)

API example:

```
// NOTE(cmat): Add genomes we want to visualize!
gvis_push("My-Data",  new Float32Array([
  -1, -1, -1,
  +1, -1, -1,
  +1, +1, -1,
  -1, +1, -1,
  -1, -1, +1,
  +1, -1, +1,
  +1, +1, +1,
  -1, +1, +1
]);
````
