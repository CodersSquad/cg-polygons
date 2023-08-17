# Polygon drawing

By using [`mousePtPlot.cpp`](./mousePtPlot.cpp) and also [polygon.cp](polygon.cpp) create a new [polygons.cpp](./polygons.cpp) program with the following specs. The base code is implemented with OpenGL, but you can alternatively use [ModernGL](https://moderngl.readthedocs.io/en/latest/) or [Processing](https://processing.org/) for implenting it. 

- By default the program will start drawing a random-color filled pentagon (5 sides)
- Then, for every left-button mouse click, the polygon will increase its sides by one and it will be filled with a new random color
- The maximun number of sides is 12
- Once your program reach the maximum number of sides, it will go back to the pentagon