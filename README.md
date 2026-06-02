# SistemaNotas

## Descripción

SistemaNotas es una aplicación de consola desarrollada en C# que permite registrar el nombre de un estudiante y su nota. El programa valida que la nota ingresada sea numérica y que se encuentre dentro del rango de 0 a 100, utilizando el manejo de excepciones con Try-Catch-Finally.

## Objetivo

Aplicar el uso de estructuras de control de excepciones para prevenir errores durante la ejecución del programa y mejorar la experiencia del usuario.

## Funcionalidades

* Registro del nombre del estudiante.
* Registro de una nota.
* Validación de notas entre 0 y 100.
* Manejo de errores con Try-Catch-Finally.
* Determinación automática de aprobado o reprobado.

## Tecnologías Utilizadas

* C#
* .NET
* Visual Studio

## Funcionamiento

1. El usuario ingresa el nombre del estudiante.
2. El usuario ingresa una nota.
3. El sistema valida que la nota sea numérica.
4. El sistema verifica que la nota esté entre 0 y 100.
5. Se muestra el estado del estudiante:

   * APROBADO (70 o más)
   * REPROBADO (menos de 70)

## Manejo de Excepciones

El bloque Try contiene el código principal del programa. Los bloques Catch capturan errores de formato y otros errores inesperados. El bloque Finally se ejecuta siempre para indicar la finalización del proceso.

## Autor

Leslye Avril Valdez De La Cruz

## Asignatura

Diseño y Desarrollo de aplicaciones 

## Centro Educativo

Instituto Politécnico Pedro Feliciano Martínez
