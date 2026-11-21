# PROYECTO DE PROGRAMACIÓN
## Campeonato de Penaltis – PSeInt

### 1. Descripción del proyecto

El proyecto consiste en desarrollar un algoritmo en PSeInt que simule un pequeño campeonato de lanzamientos de penaltis. El usuario deberá realizar cinco lanzamientos, seleccionando la dirección hacia la cual desea patear el balón. Por su parte, también deberá indicar la dirección hacia la cual se lanza el portero.

El programa comparará ambas direcciones para determinar si el lanzamiento termina en gol o si el portero consigue detener el balón. Al finalizar los cinco lanzamientos, se presentará un resumen con los resultados obtenidos y se determinará el resultado del campeonato.

### 2. Objetivo

Desarrollar un algoritmo que permita aplicar los conocimientos básicos de programación mediante el uso de variables, estructuras condicionales, ciclos y validaciones de datos ingresados por el usuario.

### 3. Funcionamiento del programa

El juego contará con cinco lanzamientos. En cada uno de ellos, el usuario deberá seleccionar una de las siguientes direcciones:

| Opción | Dirección |
|---|---|
| 1 | Izquierda |
| 2 | Centro |
| 3 | Derecha |

Posteriormente, deberá ingresar la dirección hacia la cual se lanza el portero, utilizando las mismas opciones.

El programa comparará las dos selecciones:

- **Gol:** cuando el jugador y el portero seleccionan direcciones diferentes.
- **Atajada:** cuando el jugador y el portero seleccionan la misma dirección.

El sistema llevará un registro acumulado de los goles y las atajadas durante los cinco lanzamientos.

### 4. Reglas del campeonato

Al finalizar los cinco lanzamientos, el programa determinará el resultado de acuerdo con las siguientes condiciones:

- **3, 4 o 5 goles:** el jugador gana el campeonato.
- **2 goles:** el resultado es un empate.
- **0 o 1 gol:** el jugador pierde el campeonato.

Adicionalmente, se deberá calcular y mostrar el porcentaje de efectividad del jugador, tomando como referencia los cinco lanzamientos realizados.

### 5. Requisitos de programación

El algoritmo deberá cumplir con los siguientes requisitos:

1. Implementar un ciclo de tipo `Para`.
2. Implementar un ciclo de tipo `Mientras`.
3. Implementar un ciclo de tipo `Repetir`.
4. Utilizar estructuras condicionales para determinar los resultados de cada lanzamiento y del campeonato.
5. Utilizar variables para almacenar los resultados y controlar el funcionamiento del programa.
6. Presentar un resumen final con los goles, las atajadas, el porcentaje de efectividad y el resultado del campeonato.

### 6. Validación de datos y errores de usuario

El programa deberá contemplar posibles errores durante el ingreso de información. No debe asumir que el usuario siempre ingresará datos correctos.

Se deberán implementar validaciones para situaciones como:

- Ingresar una dirección diferente de las opciones permitidas (1, 2 o 3).
- Ingresar números fuera del rango establecido.
- Evitar que una selección incorrecta interrumpa el funcionamiento normal del programa.

Cuando el usuario ingrese una opción no válida, el sistema deberá mostrar un mensaje de advertencia y solicitar nuevamente el dato hasta recibir una opción correcta.

**Importante:** las validaciones deben garantizar que el programa pueda continuar funcionando correctamente incluso cuando el usuario cometa errores al ingresar información.

### 7. Resultado esperado

Al finalizar la ejecución, el programa deberá mostrar un resumen similar al siguiente:

- Total de lanzamientos: 5.
- Goles marcados: 3.
- Penaltis atajados: 2.
- Efectividad: 60 %.
- Resultado: ¡Felicidades! Has ganado el campeonato.

Los valores anteriores son únicamente un ejemplo del resultado que podría obtenerse.

### 8. Entrega

Se deberá entregar el archivo del algoritmo desarrollado en PSeInt, con extensión `.psc`.

El código deberá estar organizado, utilizar nombres de variables comprensibles y permitir identificar claramente las estructuras de control implementadas.

**Criterio fundamental:** se evaluará que el algoritmo cumpla con los requisitos establecidos, funcione correctamente y contemple los posibles errores de ingreso del usuario. No se requiere implementar funcionalidades adicionales a las descritas en este documento.
