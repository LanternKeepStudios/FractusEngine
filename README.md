# Fractus Game Engine

Fractus is being designed as a lightweight 3D engine,
we are not trying compete with full-featured engines. if you
 are after that, I recommend Ogre3D.


## Dependencies

Fractus requires the following:
* GLFW [minimum 3.3.2] : https://www.glfw.org/
    - (FRACTUS_GLEW_INCLUDES)
* GLM [minimum 1.0.3] : https://github.com/g-truc/glm
    - FRACTUS_GLM_INCLUDES
* STB - stb_image.h is part of repo
    - [https://github.com/nothings/stb]

## Building On Linux / Mac

```
export FRACTUS_GLEW_INCLUDES=<DIR>
export FRACTUS_GLFW_INCLUDES=<DIR>
export FRACTUS_GLM_INCLUDES=<DIR>
export FRACTUS_ASSIMP_INCLUDES=<DIR>

export FRACTUS_GLEW_LIBS=-lGLEW
export FRACTUS_GLFW_LIBS=-lglfw
export FRACTUS_ASSIMP_LIBS=-lassimp

glibtoolize
aclocal
autoreconf -fi
automake --add-missing --copy
./configure
make V=1
```
