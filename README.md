# Plug And Play GLFW + GLAD + GLM + ImGui + Other OpenGL stuff Code::Blocks setup!

---

## What is it?

---

I already configured a Code::Blocks project with everything that you need to start learning OpenGL!
I even added GLM, Imgui with extensions, and stb_image for you!

![image](https://github.com/user-attachments/assets/8eb5c970-880f-4495-a910-d007deca01b8)



---

## How to use?

If you just want to learn OpenGL from the https://learnopengl.com/ you can just delete the content from main.cpp and start from scratch!
*BUT* re-add ```#include <openglErrorReporting.h>``` and the ```enableReportGlErrors();``` line after you enable opengl!!!!!!!!
(it might not work on apple)

They are very important because they will enable OpenGL error reporting for you!!!!!!!!! And trust me you want that!

Other than that this is a normal code blocks project, enjoy!

Note that you might need to enable the 64 bit compiler
 -> settings -> compiler -> top dropdown select GNU GCC TDM-64 Compiler  and press set as default compiler, or 

If you want other templates that use CMake, or a Visual Studio Template, check out this video:
https://www.youtube.com/watch?v=FrVABOhRyQg
