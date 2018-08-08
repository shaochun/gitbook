# Pipeline: Surface Scattering

**Created the translucency map and the GUI panel for Three.js**

- [https://threejs.org/examples/webgl_materials_translucency](https://threejs.org/examples/webgl_materials_translucency)
- The thickness map is generated using Substance Painter. Used to create it using Arnold's AO with reversed normal option checked in Maya 2017, but the generated map doesn't look quite right.
SP gives a better result since it offers more params, and generates the map based on reversed normals. Invert it should give the desired result.

![](/.gitbook/assets/three-bunny.png)

![](/.gitbook/assets/three-bunny-pos-map.png)
