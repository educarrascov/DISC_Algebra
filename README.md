# DISC_TMAD <img src="img/logo.png" align="right" width = "95px"/>
    
Repositorio creado para el curso de **Álgebra Lineal y Optimizzación para Ciencia de datos** en el programa de **Doctorado en Ingeniería de Sistemas Complejos** de la Universidad Adolfo Ibáñez.

Profesor: 
- Martín Ríos-Wilson. 

Facultad de Ingeniería y Ciencias, UAI.

**Eduardo Carrasco Vidal**
 
![Python](https://img.shields.io/badge/python-%2314354C.svg)![GitHub](https://img.shields.io/badge/github-%23121011.svg)

## I. Tareas:
1. [Trabajo Práctico N° 1 - Álgebra - Código](https://github.com/educarrascov/DISC_Algebra/blob/main/Trabajo%201.ipynb)
2. [Trabajo Práctico N° 1 - Álgebra - Informe (pdf)](https://github.com/educarrascov/DISC_Algebra/blob/main/Trabajo%201%20-%20ecarrascov.pdf)
3. [Trabajo Práctico N° 2 - Álgebra - Código](https://github.com/educarrascov/DISC_Algebra/blob/main/Trabajo%202.ipynb)
4. [Trabajo Práctico N° 2 - Álgebra - Informe (pdf)]()

## II. Adicionales:

1. [Ejemplo funciones benchmark de optimización más comunes](https://github.com/educarrascov/DISC_Algebra/blob/main/Respaldo%20Fun%20Optimizacion.ipynb)
   - Ackley function.
   - Rastringin function.
   - Beale function.
   - Goldstein-Price function.
   - Himmelbau function.
   - Lévi function.
   - Schwefel function.
   - Booth function.
   - Rosenbrock function.

| Nombre            | Descripción                                         | Función Matemática                                                                                                             | Valor(es) Mínimo(s) |
|-------------------|-----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|---------------------|
| Ackley            | Paisaje complejo con un mínimo global rodeado de mínimos locales. | `f(x, y) = -20 e^{-0.2\sqrt{0.5(x^2 + y^2)}} - e^{0.5(\cos(2\pi x) + \cos(2\pi y))} + e + 20`                                 | `f(0, 0) = 0`       |
| Rastrigin         | Superficie ondulada con muchos mínimos locales.     | `f(x, y) = 20 + x^2 - 10\cos(2\pi x) + y^2 - 10\cos(2\pi y)`                                                                    | `f(0, 0) = 0`       |
| Beale             | Función con un valle estrecho y un único mínimo global. | `f(x, y) = (1.5 - x + xy)^2 + (2.25 - x + xy^2)^2 + (2.625 - x + xy^3)^2`                                                      | `f(3, 0.5) = 0`     |
| Goldstein-Price   | Paisaje complejo con múltiples mínimos locales.     | `f(x, y) = [1 + (x + y + 1)^2(19 - 14x + 3x^2 - 14y + 6xy + 3y^2)] [30 + (2x - 3y)^2(18 - 32x + 12x^2 + 48y - 36xy + 27y^2)]` | `f(0, -1) = 3`      |
| Himmelblau        | Varias mínimos locales y globales idénticos.        | `f(x, y) = (x^2 + y - 11)^2 + (x + y^2 - 7)^2`                                                                                 | `f(3, 2) = f(-2.805118, 3.131312) = f(-3.779310, -3.283186) = f(3.584428, -1.848126) = 0` |
| Lévi              | Paisaje ondulado con un único mínimo global.        | `f(x, y) = \sin^2(3\pi x) + (x-1)^2[1 + \sin^2(3\pi y)] + (y-1)^2[1 + \sin^2(2\pi y)]`                                         | `f(1, 1) = 0`       |
| Schwefel          | Mínimo global en el límite del dominio de búsqueda. | `f(x, y) = 418.9829 \times 2 - x\sin(\sqrt{\lvert x \rvert}) - y\sin(\sqrt{\lvert y \rvert})`                                  | `f(420.9687, 420.9687) \approx 0` |
| Booth             | Función de optimización simple.                     | `f(x, y) = (x + 2y - 7)^2 + (2x + y - 5)^2`                                                                                    | `f(1, 3) = 0`       |
| Rosenbrock        | Largo y estrecho valle parabólico con un mínimo global. | `f(x, y) = (1 - x)^2 + 100(y - x^2)^2`                                                                                         | `f(1, 1) = 0`       |
