# 2021-Spring-NTU_ICG-hw
Professor: M Ouhyoung  

Class: Interactive Computer Graphics, 2021, Spring

# HW Requirement
* Implemetation of three different Shadings with Phong model
  1. Flat Shading 
  2. Gouraud Shading
  3. Phong Shading
  Needed: loaded Three things, three light sources.

* Bonus: 
  1. Five things
  2. Five light sources
  3. Sliver Kangaroo model
    * By changing the Front color and back color of the origin Kangaroo model.json
  4. Shiness
    * By adjusting the parameter of "Specular"
  5. Gloden 
    * By adjusting the parameter of "gl_FragColor"
  6. Reflection
    * reflected by y axial
  7. Saturation  (Only for Flat and Phong shading)
   * By changing the value of cosine, range from (-3.0, 0.0), initial: 0.0
  8. Clipping_line (Suggested for Phong Shading!)
   * As the vertex position is larger than the clipping line, then change the color of the polygon to the background color
   * Note: Approriate for Phong Shading, Flat Shading may be fine, but not appropriate to Gouraud Shading
  9. Front Shading (only color the front phase) 
   * By changing the value of cosAlpha.
   * demo: 