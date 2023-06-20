---
title:  "Como hacer hola mundo en C++"
mathjax: true
layout: post
categories: c++
---

Para poder crear nuestro programa de hola mundo en Windows o Linux debemos de tener un compilador de c++ o un editor de codigo como Dev-C++ para Windows,
usan el que mas les guste.

* Creamos nuestro archivo `hola.cpp`
* Editamos nuestro archivo(En linux pueden usar el comando `nano hola.cpp`)

```bash
#include <iostream>
using namespace std;

int main(){
	cout<<"Hola mundo.!";
	get.cin();
	return 0;
}
```
En C++ al igual que en C, se trabajan con librerias, para C++ la libreria que debemos de incluir es `iostream`, y luego usamos `using namespace std`
para evitar escribir `std::cout` y `std::cin`; por ultimo ponemos `return 0` al final para que el programa termine.

Si estan en Dev-C++ presionan la tecla `F11` y el codigo se compilara y ejecutara.




