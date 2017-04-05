# openGL
    下载 MinGW
    下载 glut包，包括：glut.h, libglut32.a, glut32.dll
    将 glut.h 放入MinGW安装的include目录下
    将 libglut32.a 放入MinGW安装的lib目录下
    将 glut32.dll 放入c:/windows/system32下(64位系统要放入c:/windows/SysWOW64下)。
    配置codeblocks，左侧，当前工程右键，选择Build options，里面linker settings，添加libglut32.a, libglu32.a, libopengl32.a
