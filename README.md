# 2021-Spring-NTU_ICG-hw
Professor: M Ouhyoung  
Class: Interactive Computer Graphics, 2021, Spring.
# HW Requirement
* Implemetation of three different Shadings with Phong model:
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
  
  # demo
  * Initial (Flat Shading): 
  <img width="1440" alt="截圖 2021-05-11 22 09 09" src="https://user-images.githubusercontent.com/41279685/117829604-84113400-b2a5-11eb-9396-0999ef9f3950.png">
  * Gouraud Shading:
  <img width="1419" alt="截圖 2021-05-11 22 10 05" src="https://user-images.githubusercontent.com/41279685/117829773-a5722000-b2a5-11eb-9ab6-c676d1941c21.png">
  * Phong Shading:
  <img width="1438" alt="截圖 2021-05-11 22 10 35" src="https://user-images.githubusercontent.com/41279685/117829865-b7ec5980-b2a5-11eb-87c7-f7078f39eebc.png">
  * Shiness: 
  <img width="1439" alt="截圖 2021-05-11 22 11 03" src="https://user-images.githubusercontent.com/41279685/117829940-c8043900-b2a5-11eb-9964-1e6f4dcd7ca2.png">
  * Gloden:
  <img width="1440" alt="截圖 2021-05-11 22 11 28" src="https://user-images.githubusercontent.com/41279685/117830014-d7838200-b2a5-11eb-95c0-80a1920550d5.png">
  * Reflection (Compared with the inital state)
  <img width="1436" alt="截圖 2021-05-11 22 12 01" src="https://user-images.githubusercontent.com/41279685/117830127-ea965200-b2a5-11eb-92c6-8a27fd9bf065.png">
  * Saturation (Compared with the inital state):
  <img width="1440" alt="截圖 2021-05-11 22 13 09" src="https://user-images.githubusercontent.com/41279685/117830290-131e4c00-b2a6-11eb-8dfd-e25e73f5169d.png">
  * Clipping_line (Set the Clipping line @ aVertexPositoin = 3.0):
  <img width="1440" alt="截圖 2021-05-11 22 13 49" src="https://user-images.githubusercontent.com/41279685/117830399-2af5d000-b2a6-11eb-9431-76802bbbd876.png">
  * Front Shading:
  <img width="1439" alt="截圖 2021-05-11 22 14 21" src="https://user-images.githubusercontent.com/41279685/117830462-3e08a000-b2a6-11eb-870e-6e3e7429bccd.png">

  
