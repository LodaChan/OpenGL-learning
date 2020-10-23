# openGL语法与库

https://www.bilibili.com/video/BV1bA411Y7Gz?from=search&seid=16030957692515792854

所有函数都以字符gl作为前缀

要AGL、WGL、GLX这些库里的接口来建立。
这几个库分别对应苹果系统、Windows、还有Linux的X-Window，没有实现跨平台。

这也是为什么存在glut（已经不更新了，代替者freeglut，不支持macOS）、glfw这些“半”跨平台的框架帮助你轻松地在各平台下使用OpenGL。

在嵌入式设备上、手机还有浏览器里的OpenGL实现使用的是OpenGL ES的说明书。

浏览器的WebGL是对OpenGL ES的js封装。建立环境用的是EGL库



glfw 跨平台窗口和键盘、鼠标、手柄处理；偏向游戏
GLFW

gl3w
GL3W

glew
GLEW