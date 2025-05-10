# CSE-333-533-Assignment-2-Transformation-Viewing-and-Projection-solved

Download Here: [CSE 333/533 Assignment 2: Transformation, Viewing and Projection solved](https://jarviscodinghub.com/assignment/assignment-2-transformation-viewing-and-projection-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

The given program renders a cube in orthographic projection. Study the program and understand how transformation, viewing and projection matrices are applied in the OpenGL programmable pipeline. Different parts of the assignment are divided into various ﬁles (transformations.cpp, viewing.cpp, and torus.cpp) under StudentCode folder. Look for TODO comments to know what to implement. Transformation 1. Generate screenshots after applying the following transformations (not successively) to the cube a. Rotate about the z-axis by 15 degrees [1 mark] b. Scale along the y-axis by 2.0 [1 mark] c. Translate by (20, 10) [1 mark] 2. Compose the above transformations in the order <a, b, c and <c, b, a. Generate screenshots. Give reasons why the result is identical or different in the two cases [2 marks]
Viewing 3. GLM provides a lookAt function to construct the viewing matrix. a. Write your own version of the same as myLookAt(). [3 marks] b. Verify correctness of your routine by comparing it with the GLM function used in the provided code (i.e., by generating screenshots for comparison).   In case of any differences, explain. [2 marks]
Projection 4. Perform appropriate projection transformations and generate screenshots for the following views of the cube: a. Orthographic: top, front elevation, side elevation, and isometric. [2.5 marks] b. Perspective: one-point, two-point, three-point (bird’s eye view), three-point (rat’s eye view). [2.5 marks]
Modelling 5. A torus is given by this equation
where , is the radius of the center of the hole to the center of the torus tube, and is the radius of the tube. Generate a torus object and display it. [5 marks]
x =( c + acosv)cosu y =( c + acosv)sinu z = asinv u,v∈[0,2π) c a
of 1 2
Deliverables • C/C++ code (make sure to upload full Cmake Project). • 2~3 page PDF Report written with Latex/MS Word. Use the acmlarge option (single column) (see sample-acmlarge.tex if writing with Latex).
Total marks for this assignment: 20 marks
Bonus (bonus marks to a maximum of 5 will be awarded for the following features. This part is completely optional) • Implement a trackball to rotate the cube with mouse. Doing so, you will have to appropriately convert screen (x, y) coordinates into camera (x, y, z) position, and rotation. [5 marks]

You may want to understand Trackball for the same:  https://www.opengl.org/wiki/Object_Mouse_Trackball
Note: Your code should be written by you and be easy to read. You are NOT permitted to use any code that is not written by you. (Any code provided by the TA can be used with proper credits within your program)
