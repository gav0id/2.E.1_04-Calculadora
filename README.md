Ejercicio 2.E.1 04 - Calculadora

Lógica del programa
Definí los métodos `sumar`, `restar`, `multiplicar` y `dividir`, los cuales reciben dos parámetros de tipo `double` y retornan el resultado de la operación. Un detalle importante es que en el método `dividir` agregué una validación condicional (`if/else`) para evitar el error de división por cero, mostrando un mensaje de advertencia y retornando `0.0` si el divisor es cero.

Dentro del método `main`, desarrollé la siguiente lógica:
1. Instancié un único objeto a partir de mi clase `Calculadora`.
2. Llamé a cada uno de los métodos pasándoles distintos valores numéricos (incluyendo una prueba forzada de división por cero) y guardé los valores de retorno en cuatro variables de tipo `double`.
3. Imprimí el valor de estas variables por consola para comprobar que todas las operaciones devuelven el resultado esperado.

Ejecución en consola
<img width="1366" height="723" alt="imagen" src="https://github.com/user-attachments/assets/81cad63b-15eb-4e30-8e56-e0d337b3ba49" />

