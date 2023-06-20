---
title:  "Mi primer post"
mathjax: true
layout: post
categories: C++
---

# Bienvenidos a mi primer post en esta web
Les saluda clun0x y hoy vamos a estar posteando algo bien basico que es el hola mundo en C.
Para esto si estan en Linux van a tener que instalar `gcc`.

* Primero creamos un archivo con el comando `touch hola.c`.
* Luego editamos con `nano hola.c`

{% highlight c %}
#include <stdio.h>

int main(){
    printf("Hola mundo");
    return 0;
}
{% endhighlight %}

* Para poder compilar debemos ejecutar el commando `gcc -o FileName hola.c`
 
Y listo ahora podemos ejecutarlo con el comando `./FileName`.

