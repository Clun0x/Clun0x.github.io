---
title:  "Como hacer el hola mundo en C"
mathjax: true
layout: post
categories: C++
---

# Bienvenidos a mi primer post en esta web
Les saluda clun0x y hoy vamos a estar posteando algo bien basico que es el hola mundo en C.
Para esto si estan en Linux va a ser un poco mas facil solo van a tener que instalar `gcc`, y si estan en Windows necesitan un compilador de C como MinGW
o tambien pueden usar Dev-C++, para realizar el hola mundo tenemos que hacer lo siguiente:

* Primero creamos un archivo con el comando `touch hola.c`.
* Luego editamos con `nano hola.c`


```c
#include <stdio.h>

int main(){
    printf("Hola mundo");
    return 0;
}
```

* Para poder compilar debemos ejecutar el commando `gcc -o FileName hola.c`
 
Y listo ahora podemos ejecutarlo con el comando `./FileName`.

	
