# glinf

This is a simple tool that prints information about OpenGL or OpenGLES
contexts.

It is roughly comparable to `glewinfo` or `glxinfo`, with the following differences:

- it uses Qt for platform abstraction
- it focusses on modern OpenGL
- it prints implementation limits such as `GL_MAX_DRAW_BUFFERS`
- it omits information about GLX and visuals
- it prints information about available GPU memory
