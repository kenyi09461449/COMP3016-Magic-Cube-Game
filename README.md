Unzip 'exe. zip'

Click 'Code.exe' file to run Rubik's cube game

Use the right mouse button to drag and drop to rotate one layer of the Rubik's Cube

Use the left mouse button to rotate the perspective.

Use the mouse scroll wheel to zoom in on the perspective.

![ClickExe](https://github.com/kenyi09461449/COMP3016-Magic-Cube-Game/assets/115618256/b1da5579-8c8e-420f-ae31-bde9edc46382)



![image](https://github.com/kenyi09461449/COMP3016-Magic-Cube-Game/assets/115618256/b21b1a2a-6003-4454-a903-b4ab919ef61b)


Code structure: The code I wrote is located in the 'src' directory

| Entry Name  | Remark                                       |
| ----------- | -------------------------------------------- |
| Camera.h    | Create a camera                              |
| Cube.h      | Build Magic Cube   shape                         |
| GlfWindow.h | Setting Viewports                            |
| main1.cpp   | Main program                                 |
| pch.h       | The direction and colors of the Rubik's Cube |
| Shader.cpp  | Shader                                       |
| Shader.fs   | Fragment shader                              |
| Shader.h    | Shader                                       |
| Shader.vs   | Vertex shader                                |
| Texture.h   | Render Texture                               |
| Tool.h      | Tool                                         |
| TraceBall.h | TraceBall                                    |
| RubikCube.h | The Movement and Interaction of Rubik's Cube |



I initially studied and analyzed this opengl program:

 

https://blog.csdn.net/wphkadn/article/details/105027482

 ![image](https://img-blog.csdnimg.cn/20200322142310606.gif)


There is no user interaction in this program, and the Rubik's Cube will automatically rotate when after click once. I mainly analyzed and designed the shape, matrix and vector of the cube through this program. On this basis, I have added the function of player interaction with the Rubik's Cube and the ability to rotate and zoom the perspective.

 

Regarding interaction methods, in my initial plan. The operation method is:

 

Left mouse button: Rotate this face 


Right mouse button: Reverse rotate this face

 

But I found several online Rubik's Cube games, and their operation methods are: 

  Use mouse button to drag and drop to rotate the layer of Cube. 
  Such as:



https://suke.kim/app/3dCube.html

 

http://www.ip33.com/rubik/index.html

 

https://rubikscu.be/

 

Therefore, with the current mouse drag and drop interaction.
