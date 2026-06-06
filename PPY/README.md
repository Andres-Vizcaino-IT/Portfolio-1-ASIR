# 🐍 Portfolio de Programación en Python - 1º ASIR

¡Bienvenido al repositorio de prácticas del módulo de **Programación**! 

Este espacio reúne todos los scripts, laboratorios y proyectos que he desarrollado para dominar las bases del lenguaje Python. El portfolio está diseñado para demostrar mi evolución conceptual: partiendo de la sintaxis básica y manipulación de datos, pasando por el control de flujos algorítmicos complejos, hasta llegar a la gestión de errores y la interacción con el sistema de archivos de manera interactiva.

A continuación, se detalla el contenido técnico del repositorio dividido por bloques de aprendizaje:


## 📝 Fundamentos, Variables y Strings
En este bloque inicial me familiaricé con la sintaxis limpia de Python y las mejores prácticas de codificación.
* **Salida por Terminal y Comentarios:** Uso de la función nativa `print()` para la depuración de datos, la modificación de cadenas para repetición rápida de texto y la documentación del código mediante comentarios de línea (`#`) y multilínea (`'''`).
* **Buenas Prácticas de Estilo:** Comprensión de los diferentes estilos de escritura de variables (como `camelCase`, `PascalCase`, `snake_case` y `screaming SNAKE_CASE` para constantes), manteniendo el código legible y limpio.
* **Tipos de Datos Primitivos:** Declaración de variables de tipo entero (`int`), decimal (`float`) y booleano (`True`/`False`).
* **Manipulación de Strings:** Extracción de la longitud de cadenas mediante `len()`, troceado avanzado (*slicing*) de texto usar índices positivos y configuración dinámica utilizando interpolación con cadenas *f-strings*.
* **Métodos Integrados de String:** Limpieza de espacios en blanco (`strip()`, `lstrip()`, `rstrip()`), alteración de mayúsculas/minúsculas (`upper()`, `lower()`, `capitalize()`, `title()`), reemplazo de caracteres (`replace()`), búsquedas con `.find()` y operadores de pertenencia lógica (`in` / `not in`).
* **Secuencias de Escape:** Uso de caracteres especiales dentro de cadenas de texto (como comillas dobles escapadas `\"`, barras invertidas `\\` para definir rutas de sistema, y saltos de línea `\n`).

## 🔢 Operaciones Matemáticas y Conversión de Tipos
Aprendizaje enfocado en el procesamiento numérico y la mutabilidad de los tipos de datos.
* **Operadores Aritméticos:** Implementación de operaciones estándar de suma, resta, producto y división, junto con operadores especiales como la división entera (`//`), el resto o módulo (`%`) y la potenciación (`**`).
* **Asignaciones Compactas:** Optimización de contadores y acumuladores mediante atajos aritméticos (`+=`, `-=`, `*=`, `/=`, `**=`, `//=`, `%=`).
* **Conversión Explicita de Tipos (Casting):** Mutación manual entre tipos compatibles (`int()`, `float()`, `str()`) para posibilitar operaciones de cadenas numéricas obtenidas por pantalla.
* **Evaluación Booleana (Truthy & Falsy):** Comprensión profunda de cómo Python evalúa nativamente la veracidad de los tipos de datos a través de la función `bool()`, identificando valores inherentemente falsos (cadenas vacías `""`, el número `0` o el objeto `None`) y valores verdaderos.

##  Módulos Nativos (`math` y `random`)
Uso y explotación de las librerías integradas estándar de Python para potenciar las capacidades del código.
* **Ajustes de Precisión:** Uso de la función nativa `round()` analizando el comportamiento del redondeo bancario (al número par más cercano ante un decimal exacto de `.5`) y cálculo del valor absoluto con `abs()`.
* **Módulo `math`:** Importación y aplicación de métodos avanzados para redondeo superior (`math.ceil()`), redondeo inferior (`math.floor()`), raíces cuadradas (`math.sqrt()`), potencias (`math.pow()`) y validación numérica (`math.isnan()`).
* **Módulo `random`:** Generación de números pseudoaleatorios utilizando `random.randint()` enfocado en mecánicas de juegos de azar.

## 🚦 Estructuras de Control Condicional (Toma de Decisiones)
Desarrollo de algoritmos capaces de bifurcar sus procesos e interactuar fluidamente con el usuario mediante flujos lógicos.
* **Comparadores Lógicos:** Evaluaciones booleanas complejas empleando operadores relacionales (`>`, `<`, `>=`, `<=`, `==`, `!=`).
* **Estructura Clásica `if-elif-else`:** Diseño de árboles de decisión anidados y secuenciales aplicados a la clasificación precisa de rangos de edad o calificaciones escolares dinámicas.
* **Operador Ternario:** Implementación de condicionales compactos en una sola línea de código para optimizar la asignación rápida de variables de salida según la evaluación de una premisa.
* **Estructura Estructurada `match case`:** Aplicación de la sintaxis moderna de emparejamiento de patrones (introducida en Python 3.10) utilizando guardas condicionales (`case n if ...`) para reemplazar cadenas extensas de `elif`.

## 🔄 Bucles, Iterables y Persistencia en Archivos
Dominio de la repetición controlada de procesos y el almacenamiento permanente de información de forma externa.
* **Bucle `for` y Colecciones:** Iteración definida sobre secuencias numéricas mediante la función generadora `range()` y recorrido carácter por carácter de objetos iterables como cadenas de texto.
* **Cláusula `for-else`:** Uso avanzado de la estructura `else` al final de un ciclo `for`, diseñada para ejecutarse únicamente si el bucle termina de forma natural sin haber sido interrumpido de forma abrupta por la instrucción `break` (aplicado en sistemas con límite de intentos para credenciales).
* **Bucle `while` y Gestión de Terminal:** Creación de ciclos de ejecución indeterminada supeditados al cambio dinámico de una variable o basados en la lectura de entradas del usuario simulando una terminal interactiva (rompiendo el bucle ante palabras clave como "FIN").
* **Bucles Infinitos Seguros:** Diseño de estructuras `while True` controladas estrictamente desde el interior mediante evaluaciones internas y salidas explícitas con `break`.
* **Bucles Anidados:** Construcción de bucles dentro de otros bucles para modelar estructuras complejas bidimensionales, tales como matrices de coordenadas personalizadas o tablas de multiplicar completas.
* **Manejo de Ficheros (I/O):** Uso de gestores de contexto automáticos (`with open()`) para interactuar con archivos de texto plano. Implementación de escrituras en modo destructivo/sobrescritura (`"w"`) y escrituras en modo adición al final del archivo (`"a"`) sin comprometer los datos existentes.

##  Proyecto Destacado: Calculadora Interactiva de Consola (`calculadora.py`)
Como culminación de estas prácticas, desarrollé un entorno interactivo completo que consolida todo lo aprendido. Se trata de una calculadora de consola que incluye:
1. **Realimentación Continua:** El resultado de una operación se convierte automáticamente en el operando inicial para la siguiente instrucción.
2. **Control Robusto de Excepciones:** Uso de bloques de seguridad `try-except ValueError` para capturar e interceptar entradas alfanuméricas inválidas sin que el programa aborte o colapse.
3. **Validación de Errores Matemáticos:** Control explícito para evitar fallos de división por cero (`ZeroDivisionError`).
4. **Salida Universal:** Flexibilidad total del flujo que permite al programa interpretar el comando `"FIN"` de forma unificada (independientemente de mayúsculas o minúsculas) en cualquier fase de la ejecución (pidiendo el primer operando, el segundo operando o el operador lógico) mediante banderas de control y la interrupción `exit()`.


