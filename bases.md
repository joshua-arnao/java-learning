# JAVA

## ¿Qué es Java?

Java es un lenguaje de programación de **alto nivel** que utiliza el paradigma **"orientado a objetos"** para modelar procesos de negocio complejos. Se caraceriza por ser **fuertemente tipado y verbozo** lo que garantiza integridad de los datos mediante una validación estrica en tiempo de compilación, fue diseñado orginalmente **Multhilos** para ejecutar varias partes de manera simultanea y opera sobre una **Máquina virtual(JVM)**, lo que proporciona seguridad, gestión automática de memoria y total dependeica del hardware.

Su lema histórico:

> _Write once, run anywhere_

- ¿Porqué es **"Fuertemente Tipado" y "verbozo"**:
  Significa que cada variable debe de tener un nombre y un tipo definido, es decir "aquí hay un **Número Entero** llamado **saldo**. Y es **verbozo** porque en Java, para decir "Hola Mundo", necesitas una Clase un Método y tipo de datos definidos. No te preocupes ya entraremos a profundidad sobre todo esto..

- ¿Porqué es **"Orientado a Objetos"** y de **"alto nivel"**:
  "Alto nivel" significa que el lenguje se parece más al idioma humano que al lenguaje de las maquinas. Y es "Orientado a Objetos" porque Java organiza el código imitando conceptos del mundo real, esto lo hace **abstracto**.

- ¿Porqué es **"Mulithilos"**?: Java tiene la capacidad de realizar tareas en paralelo. Es la base de los sistemas modernos y servidores web, permitiendo que miles de usuarios interactúen con la misma aplicación al mismo tiempo sin bloquearse entre si.

## ¿Cómo funciona Java??
Java no es solo un lenguaje para escribir comandos; es una **plataforma de ejecución segura**.

- El lenguaje es lo que escribes (Alto nivel, Tipado).
- La plataforma es donde corre (JVM).


| Código Fuente | Compilador | Bytecode | JVM |
|---------------|------------|----------|-----|
| ```.java``` | ```javac``` | ```.class``` | Java Virtual Machine|
|El Manuscrito | El traductor estricto | Idioma Universal | El intérprete y Motor |
| Es lo que tu esribes | El compilador toma tu archivo ```.java``` y lo revisa de arriba a abajo para validar que toda la sintaxis sea correcta. Si todo está bien, crea un archivo ```.class``` que contiene **Bytecode**.|Es el lenguaje intermedio. No es código máquina, sino un conjunto de instrucciones optimizadas que solo la JVM entiende. | El "simulador" que traduce el Bytecode a lenguaje real de tu procesador (Windows, Mac, Linux). |


## 4. Programación Orientada a Objetos (POO)

Java nos obliga a pensar en Moldes y Productos.

### 4.1 El concepto de Clase (`Class`) - El Molde

Una `Clase` es la unidad básica en Java. Como vimos en la definición, Java es **Verboso** y **Abstracto**; por lo tanto, no puedes simplemente escribir código "al aire". Todo debe pertencer a una clase que define los **atributos** (datos) y **comportamientos** (métodos) que tendrá un objeto.

### 4.2 El concepto de Objeto - La Instancia
El **Objeto** es el producto real creado a partir del modelo. Aquí es donde entra la JVM 
