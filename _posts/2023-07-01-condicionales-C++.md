---
title:  "Condicionales en C++"
mathjax: true
layout: post
categories: c++
---

Podemos usar un condicional cuando tenemos dos opciones o queremos forzar algun evento; para esto C++, C y algunos lenguajes mas tienen el 
comando `if` y `else`. Por ejemplo:

```c++
//Se quiere que una persona ingrese su edad, y si su edad es mayor o igual de 18 años se le 
//Imprima que "Debe sacar su DNI".Si no muestre "Usted es menor de edad." 
#include <iostream>
using namespace std;

int main(){
	int edad;
	cout<<"Ingrese sus edad: ";
	cin>>edad;
	if (edad >= 18){
		cout<<"Debe sacar su DNI";
	}
	else{
		cout<<"Usted es menor de edad";
	}
	cin.get();
	return 0;
}

```

Explicaremos un poco el codigo, incluimos librerias, luego agregamos la linea `using namespace std` para no estar aumentando `std::` antes de cada `cout` y `cin`, 
luego como ya sabemos `cout` nos imprime en la consola y `cin` recibe el input que es la edad, luego la variable "edad" la comparamos con el comando `if` 
y le ponemos la condicion de que sea mayor de 18, y para el caso que no cumpla usamos `else`, y al final `cin.get()` sirve para que el programa no se cierre solo 
y espere que presionemos cualquier tecla para que el programa finalice.




