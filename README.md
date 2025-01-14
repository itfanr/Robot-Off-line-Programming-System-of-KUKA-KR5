# Robot-Off-line-Programming-System-of-KUKA-KR5
The off-line programming system was developed using OpenGL and C# in the Visual Studio 2017 development environment.
It accomplished the 3D modeling function by reading the STL format file exported by CAD software and using OpenGL to reconstruct and render the model.
Taking the KUKA six-axis robot as the research object, the improved D-H modeling method is used to establish the kinematics equation of the robot, and the kinematics forward and inverse solution algorithm is realized. Aiming at the existence of multiple sets of inverse solutions, an optimization algorithm of robot position and posture is proposed to select the optimal solution.
It realized the machining simulation of robots based on vector graphics. The G code format path information of the vector diagram is generated by the CAM software, and the G code is converted into the discrete path point coordinate information by the linear interpolation algorithm, and then the position and posture of the robot tool at the path point are determined by the trajectory planning algorithm.

### How to use?
To simplify the procedure of extracting G code information, some .tap files are available in the path "\Robot-Off-line-Programming-System-of-KUKA-KR5\SharpGLWinformsApplication1\bin\Debug\Data\Tap".
Open one of them and then the robot will simulate.

