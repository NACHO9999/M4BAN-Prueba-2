# M4BAN-Prueba-2

## Introducción

Una empresa de baldosas quiere programar un sistema para calcular los costos de sus trabajos. Las baldosas pueden ser cuadradas o circulares. Además, pueden ser de uno de los siguientes materiales: Cemento ($5) o Ladrillo ($10). El precio de cada baldosa se calcula como área de la baldosa * precio del metro cuadrado * precio del material.

## Se pide:

1. Forkear el repo del ejercicio.
2. Conectar el proyecto de test con el proyecto de backend.
3. Modelar el problema usando TDD. El modelado debe tener una clase CostCalculator con un único método el cual recibe dos parámetros: una lista de baldosas y el precio por metro cuadrado, y devuelve el costo total.
4. En TryOut, se pide calcular el precio de 3 baldosas cuadradas de 2x2 de cemento y 1 circular de radio=3 de ladrillo, a 4 pesos el metro cuadrado.

## Contestar en el README

5. ¿Qué archivo se modificó para lograr el ejercicio 2?
- El archivo que se modifico fue el __BusinessLogic.Test.csproj__ para agregar la referencia a la Baldosas.cs - nameSpace BusinessLogic

6. En su código, ¿Qué pasa si alguien desea agregar un nuevo tipo de figura?
- Si alguien desea agregar un nuevo tipo de figura debera definir una nueva clase que hedere de baldosa y hacer una implementacion para el metodo Area(), tambien habria que hacer pruebas unitarias para esta.

7. Cuando usted compila su código, dotnet genera archivos .DLL, ¿Qué contienen esos archivos y cómo son usados por el CLR?
- Los archivos .DDL tienen codigo en lenguaje intermedio que es independiente de la plataforma. Y el CLR usa estos archivos para ejecutar el codigo, compilandolo rapidamente.