# Control de Asistencia

## Descripción

Control de Asistencia es una aplicación de escritorio desarrollada en Java que permite gestionar empleados y registrar sus entradas y salidas del trabajo mediante una interfaz gráfica. La aplicación almacena el historial de fichajes de cada empleado y calcula la duración de los registros realizados.

El proyecto forma parte de mi aprendizaje en el ciclo de Desarrollo de Aplicaciones Multiplataforma (DAM) y me permite poner en práctica conocimientos de programación orientada a objetos, interfaces gráficas, gestión de fechas y persistencia de datos.

## Tecnologías utilizadas

- **Java:** desarrollo de la lógica de la aplicación.
- **Java Swing:** creación de la interfaz gráfica.
- **Java Time API:** gestión de fechas, horas y duración de los fichajes.
- **Serialización de objetos:** almacenamiento de empleados y registros en archivos.
- **Git y GitHub:** control de versiones y alojamiento del código.

## Estructura del proyecto

```text
asistencia/
├── src/
│   ├── AppAsistencia.java
│   ├── Empleado.java
│   ├── Fichaje.java
│   ├── GestorAsistencia.java
│   └── InterfazAsistencia.java
├── lib/
├── .vscode/
├── asistencia.dat
└── README.md
```

### Descripción de las clases

- **AppAsistencia.java:** punto de entrada de la aplicación.
- **Empleado.java:** representa a los empleados registrados.
- **Fichaje.java:** representa los registros de entrada y salida.
- **GestorAsistencia.java:** gestiona los empleados, los fichajes y los datos asociados.
- **InterfazAsistencia.java:** contiene la interfaz gráfica desarrollada con Java Swing.
- **asistencia.dat:** archivo utilizado para almacenar los datos de la aplicación.

## Funcionalidades

- Registro de nuevos empleados con identificador, nombre y departamento.
- Registro de entradas y salidas de los empleados.
- Validación de fichajes para evitar registrar una nueva entrada cuando existe una salida pendiente.
- Consulta del historial de fichajes de cada empleado.
- Cálculo de la duración de los fichajes completados.
- Cálculo del total de horas trabajadas durante el día actual.
- Persistencia de los datos mediante el archivo `asistencia.dat`.

## Instalación y ejecución

### Requisitos

- Java JDK instalado.
- Un IDE compatible con Java, como Visual Studio Code, Eclipse o IntelliJ IDEA.

### Pasos

1. Clona el repositorio:

   ```bash
   git clone https://github.com/brando046/Asistencias.git
   ```

2. Abre la carpeta del proyecto en tu IDE.
3. Comprueba que los archivos Java de la carpeta `src` estén incluidos en el proyecto.
4. Ejecuta la clase principal `AppAsistencia.java`.
5. La aplicación se abrirá y permitirá registrar empleados y gestionar sus fichajes. Los datos se almacenan en `asistencia.dat`, según la configuración del proyecto.

## Autor

**Brandon Castrillón**

Estudiante de Desarrollo de Aplicaciones Multiplataforma (DAM).

- **Portfolio:** [Portfolio personal](https://brando046.github.io/Portfolio-Brandon/)

