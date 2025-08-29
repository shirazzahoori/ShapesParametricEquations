# ShapesParametricEquations
Developed a dataset for a gear type and parameter prediction model, focusing on four types of gears: Spur Gear, Crankshaft Gear, Reduction Gear, and Worm Gear. A total of 540 images were generated for each of the four gear types, resulting in 2,160 images overall.

These gear images were generated using parametric equations by varying the following nine parameters.
<pre>
**| Parameter Count |Parameter Name |          Spur Gear  | Crankshaft Gear |   Reduction Gear |       Worm Gear |**
  
|                  1|           type|                   1 |                2|                 3|                4|
  
|                  2|   number_turns|                  -1 |               -1|               -1 |10 variants:10-55|

|                  3|     num_teeth1|    6 variants:10-35 | 6 variants:10-35|  6 variants:10-35|               -1|

|                  4|   tooth_depth1|     6 variants:1-3  | 5 variants:1-2.5|    3 variants:1-2|               -1|
  
|                  5|    hole_radius|  5 variants:0.5-2.5 |  2 variants:1-2 |  2 variants:1-1.5|               -1|
  
|                  6|  num_teeth2   |         -1          |    -1           | 5 variants:10-30 |               -1|

|                  7|  tooth_depth2 |         -1          |    -1           |         1        |               -1|

|                  8| indent_radius |         -1          |3 variants:3-5   |         -1       |               -1|
  
|                  9|Elevation      |  3 variants:30-50   |3 variants:30-50 |  3 variants:30-50|  54 variants:0-53|
</pre>


