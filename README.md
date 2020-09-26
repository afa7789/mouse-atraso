# Mouse Atraso

Tem bastante comentário no código, mas não lembro como instala tudo que precisa p/ rodar opengl.

`gcc mouse.c -o mouse -D FREEGLUT_STATIC -lSOIL -lfreeglut_static -lopengl32 -lwinmm -lgdi32 -Wl,--subsystem,windows`
    #include <stdio.h>
    #include <GL/glew.h>
    #include <GL/freeglut.h>
    #include <stdio.h>
