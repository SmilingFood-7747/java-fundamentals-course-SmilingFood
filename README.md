# Fundamentos de Java para Principiantes — Una aventura en Java

## Resumen del curso

Este curso introduce a estudiantes de secundaria a los fundamentos de la programación con Java mediante una aventura de texto protagonizada por **Dan**. A lo largo de diez videos, el estudiante aprenderá a mostrar mensajes, administrar vidas y energía, resolver desafíos, crear métodos y trabajar con mascotas virtuales llamadas **Luna, Rocky y Nube**. El recorrido culmina con un programa interactivo en consola que integra los conocimientos adquiridos.

**¡No requiere descargas ni instalaciones!** Los ejemplos se ejecutan en **OnlineGDB**, directamente desde el navegador. Cada lección utiliza un ejemplo independiente: el código no se acumula automáticamente entre videos.

- **Duración total estimada:** 62 minutos (10 videos de 5 a 8 minutos).
- **Público objetivo:** estudiantes de 12 a 17 años sin experiencia previa en programación.
- **Prerrequisitos:** ninguno.
- **Herramientas necesarias:** navegador web (Chrome, Firefox, Safari o Edge) y OnlineGDB.
- **Modalidad:** videos breves, demostraciones guiadas, predicciones y prácticas individuales.
- **Proyecto conductor:** *Una aventura en Java*, juego interactivo de texto en consola (no es un videojuego gráfico).
- **Equipo responsable:** SmilingFood.
- **Repositorio de código fuente:** `https://github.com/SmilingFood-7747/java-fundamentals-course-SmilingFood.git`.

## Secuencia de las lecciones

### Lección 1: ¿Qué es programar y qué es Java? (2 minutos)

- **Descripción:** comprende cómo las instrucciones permiten que Dan avance en su aventura. Conoce Java, el editor, el botón **Run** y la consola de OnlineGDB.
- **Objetivo:** entender qué es una instrucción y ejecutar un primer programa.
- **Conclusiones clave:** programar es dar instrucciones claras; `Main` es la clase principal, `main` es el punto de inicio y `System.out.println()` muestra mensajes en consola.
- **Código de demostración:** bienvenida a la aventura de Dan.
- **Práctica principal:** cambia «Dan» por el nombre de tu personaje y ejecuta el programa.
- **Desafío opcional:** agrega una tercera línea con el nombre del mundo o experimenta con un punto y coma faltante y corrige el error.
- **Video:**  https://youtu.be/JbfMz-baFdk

### Lección 2: Variables y tipos de datos (1 minuto 50 segundos)

- **Descripción:** crea la ficha de Dan con su nombre, vidas, velocidad y posesión de una llave.
- **Objetivo:** crear y modificar variables de tipo `String`, `int`, `double` y `boolean`.
- **Conclusiones clave:** una variable guarda un dato; cada tipo representa una clase de valor y una variable existente puede actualizarse sin volver a declarar su tipo.
- **Código de demostración:** `String nombre = "Dan";`, `int vidas = 3;`, `double velocidad = 1.5;` y `boolean tieneLlave = false;`.
- **Práctica principal:** cambia el nombre y las vidas del héroe; predice qué aparecerá en consola.
- **Desafío opcional:** cambia `tieneLlave` a `true` o agrega una variable `puntos`.
- **Video:** https://youtu.be/7V6lv--TAyU

### Lección 3: Operadores y expresiones (1 minuto 50 segundos)

- **Descripción:** calcula monedas, puntos y energía; comprueba si Dan cumple las condiciones para abrir un cofre.
- **Objetivo:** utilizar operadores aritméticos, de comparación y lógicos.
- **Conclusiones clave:** `+`, `-`, `*`, `/` y `%` permiten calcular; `>=` y `==` comparan; `&&` y `||` combinan condiciones. Dividir enteros no produce necesariamente decimales.
- **Código de demostración:** `int monedas = 10 + 5;` y `monedas >= 10 && tieneLlave`.
- **Práctica principal:** modifica las monedas iniciales y predice si Dan puede abrir el cofre.
- **Desafío opcional:** calcula la energía tras dos golpes o identifica rondas pares con `% 2 == 0`.
- **Video:** https://youtu.be/HFNMew4oIoA


### Lección 4: Tomar decisiones con if-else (1 minuto 44 segundos)

- **Descripción:** ayuda a Dan a decidir si puede entrar al castillo y qué hacer según su energía.
- **Objetivo:** utilizar `if`, `else if` y `else` para controlar diferentes caminos del programa.
- **Conclusiones clave:** las condiciones determinan qué instrucciones se ejecutan; `=` asigna valores, `==` compara valores y `equals()` compara el contenido de textos.
- **Código de demostración:** puerta del castillo según `tieneLlave` y estados de energía de Dan.
- **Práctica principal:** prueba los valores de energía `80`, `35` y `0`; explica el resultado de cada uno.
- **Desafío opcional:** cambia `tieneLlave` para abrir la puerta o agrega una condición sobre monedas.
- **Video:** https://youtu.be/RvUtzE8y5vw

### Lección 5: Repetir tareas con bucles for y while (1 minuto 50 segundos)

- **Descripción:** completa rondas, acumula puntos y realiza una cuenta regresiva para abrir una puerta.
- **Objetivo:** repetir instrucciones con los bucles `for` y `while`.
- **Conclusiones clave:** `for` resulta útil para repeticiones contadas; `while` continúa mientras una condición sea verdadera; el contador debe cambiar para evitar bucles infinitos.
- **Código de demostración:** `for (int ronda = 1; ronda <= 5; ronda++)` y cuenta regresiva con `while`.
- **Práctica principal:** cambia las cinco rondas por tres y comprueba los puntos acumulados.
- **Desafío opcional:** aumenta la recompensa por ronda o cambia la cuenta regresiva a cinco.
- **Video:**  https://youtu.be/HYkPB7ZtJPc


### Lección 6: Métodos y parámetros (1 minuto 51 segundos)

- **Descripción:** crea acciones reutilizables para saludar personajes, recuperar energía y comprobar si Dan puede avanzar.
- **Objetivo:** declarar y llamar métodos con parámetros y valores de retorno.
- **Conclusiones clave:** los métodos agrupan acciones; los parámetros reciben información; `void` indica que no se devuelve un valor y `return` entrega un resultado.
- **Código de demostración:** `saludar(String nombre)`, `recuperarEnergia(int actual, int cantidad)` y `puedeAvanzar(int energia)`.
- **Práctica principal:** cambia `recuperarEnergia(30, 20)` para recuperar solo 10 puntos.
- **Desafío opcional:** crea un método `ganarPuntos` o saluda a un personaje adicional.
- **Video:** https://youtu.be/t5A2d8VgaLs

### Lección 7: Entrada y salida con Scanner (2 minuto 14 segundos)

- **Descripción:** permite que el jugador escriba el nombre de su héroe y adivine la clave de un cofre mediante pistas.
- **Objetivo:** recibir texto y números desde la consola.
- **Conclusiones clave:** `Scanner` lee datos del teclado; `nextLine()` lee texto, `nextInt()` lee enteros; `print()` y `println()` muestran mensajes de forma diferente.
- **Código de demostración:** `Scanner sc = new Scanner(System.in);` y cofre con clave `7`, pistas y repetición mediante `while`.
- **Práctica principal:** ejecuta el programa y abre el cofre usando las pistas.
- **Desafío opcional:** modifica la clave o cuenta el número de intentos.
- **Video:** https://youtu.be/lCQGye-Wh6Y


### Lección 8: Clases, objetos y constructores (2 minuto 10 segundos)

- **Descripción:** presenta a Luna y Rocky, mascotas virtuales con nombre, tipo y energía, capaces de jugar y dormir.
- **Objetivo:** comprender clases, atributos, métodos, objetos y constructores.
- **Conclusiones clave:** una clase funciona como plantilla; cada objeto tiene datos propios; `new` crea objetos y el constructor establece su estado inicial.
- **Código de demostración:** clase `Mascota`, constructor `Mascota(String nombre, String tipo)`, métodos `jugar()` y `dormir()`.
- **Práctica principal:** crea `Mascota nube = new Mascota("Nube", "conejo");` y ejecuta `nube.jugar();`.
- **Desafío opcional:** predice la energía de Luna y Rocky o añade `mostrarEstado()`.
- **Video:** https://youtu.be/mWPMn4Sr3Rw

### Lección 9: Encapsulación y arreglos con objetos (2 minutos)

- **Descripción:** protege la energía de las mascotas y organiza a Luna, Rocky y Nube en un equipo.
- **Objetivo:** utilizar `private`, getters, setters y arreglos de objetos.
- **Conclusiones clave:** encapsular permite controlar el acceso a los datos; un setter puede validar valores; un arreglo reúne objetos del mismo tipo y puede recorrerse con `for`.
- **Código de demostración:** `getEnergia()`, `setEnergia(int nuevaEnergia)`, `Mascota[] equipo` y recorrido de `equipo.length`.
- **Práctica principal:** intenta asignar a Luna energía `80` y luego `500`; observa la validación y muestra el equipo.
- **Desafío opcional:** añade una cuarta mascota o muestra los nombres en mayúsculas con `toUpperCase()`.
- **Video:** https://youtu.be/f0CCGCRXiJU


### Lección 10: Proyecto final y buenas prácticas (2 minuto 50 segundos)

- **Descripción:** integra lo aprendido en una aventura de texto con menú interactivo, exploración, puntos, energía y mascotas.
- **Objetivo:** combinar variables, operadores, decisiones, bucles, métodos, entrada/salida, clases, encapsulación y arreglos.
- **Conclusiones clave:** un programa puede construirse a partir de componentes pequeños; los nombres claros, la sangría y las pruebas frecuentes facilitan detectar errores.
- **Código de demostración:** programa inicial precargado con la clase `Mascota`, un arreglo `equipo`, `Scanner`, `while` y un menú con cuatro opciones: **1. Explorar**, **2. Ver equipo**, **3. Descansar** y **4. Salir**.
- **Práctica principal:** abre el proyecto, explora una vez, revisa el equipo y descansa.
- **Desafío opcional:** añade a Nube, cambia la recompensa de 10 a 15 puntos o crea una opción «Ver instrucciones».
- **Nota de producción:** durante el video se completan o modifican únicamente tres fragmentos: una opción del menú, la exploración y la visualización del equipo. El repositorio debe incluir tanto el archivo inicial como la solución completa.
- **Video:**  https://youtu.be/Fsu1AS8tdHM


## Recursos adicionales

- **Repositorio completo de GitHub:** `https://github.com/SmilingFood-7747/java-fundamentals-course-SmilingFood.git`


### Todas las actividades prácticas

| Lección | Tema | Actividad principal | Entorno de práctica |
|---|---|---|---|
| 1 | Introducción a Java | Personalizar la bienvenida de Dan |[ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |
| 2 | Variables y tipos de datos | Cambiar nombre y vidas del héroe | [ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |
| 3 | Operadores y expresiones | Calcular monedas y comprobar el cofre | [ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |
| 4 | Condiciones `if-else` | Probar diferentes niveles de energía | [ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |
| 5 | Bucles `for` y `while` | Completar tres rondas | [ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |
| 6 | Métodos y parámetros | Modificar la recuperación de energía | [ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |
| 7 | Entrada con `Scanner` | Adivinar la clave del cofre | [ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |
| 8 | Clases y objetos | Crear a Nube y hacerla jugar | [ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |
| 9 | Encapsulación y arreglos | Validar energía y recorrer mascotas | [ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |
| 10 | Proyecto final | Explorar, ver equipo y descansar | [ OnlineGDB ](https://www.onlinegdb.com/online_java_compiler#) |

### Organización sugerida del repositorio

```text
java-fundamentals-course-smilingfood/
├── README.md
├── completed-examples/
│   ├── video-01.java
│   ├── video-02.java
│   ├── ...
│   └── video-10.java
└── scripts/
    └── guiones-del-curso.pdf
```

> **Importante:** los enlaces se completarán después de publicar los videos y compartir los ejemplos precargados. Antes de la entrega, comprobar que cada programa se ejecute correctamente en OnlineGDB y que sus enlaces funcionen sin instalación ni registro obligatorio. Los videos se publicarán como **no listados**, de acuerdo con el guion de producción.

**¡Gracias por completar la aventura en Java!** Ahora puedes modificar los personajes, crear nuevas mascotas e inventar tus propios retos.

---

## 👥 Elaboración

**Universidad Peruana de Ciencias Aplicadas (UPC)**  
**Carrera:** Ingeniería de Software  
**Período académico:** 2026-02 (202620)  
**Curso:** 1ASI0729 — Desarrollo de Aplicaciones Open Source  
**NRC:** 7747  
**Nombre del equipo:** SmilingFood  
**Líder del equipo:** Giuliano Angel Peláez Vargas
**Integrantes del equipo:** 

<table style="margin: 0 auto; border-collapse: collapse;" border="1" align="center">
<tr>
<th>Código</th>
<th>Integrantes</th>
</tr>
<tr>
<td>U202326295</td>
<td>Huayra Moreyra José Maria</td>
</tr>
<tr>
<td>U20221e121</td>
<td>Giuliano Angel Peláez Vargas</td>
</tr>
<tr>
<td>U202316246</td>
<td>Martínez Ramos Bryan Felix</td>
</tr>
<tr>
<td>U202213185</td>
<td>Medina Merma, Ingrid Melani</td>
</tr>
</table>

<br>

**Fecha de entrega:** Noviembre 2026
