# Sistema de Horarios

Este sistema permite generar automáticamente los horarios semanales de cada salón a partir de un archivo Excel que contiene la información de cursos, docentes, horarios y salones. El objetivo es simplificar la creación de horarios impresos para colocarlos en las portamicas de los salones de clase.

En el repositorio estoy dejando un archivo Excel con el formato para que puedan adecuarlo a la necesidad, colocando los datos necesarios, les dejo estas recomendaciones:

1. En las columnas de Horas inicio y Final, deben pegarse las horas como texto.

2. Recomendacion para limpiar data: Pueden transformar la data con TEXTO(HORA_INICIO; "HH:MM:SS")
3. En la columna dia solo debe estar el nombre del dia.
4. Recomendacion para limpiar data: Pueden transformar la data con EXTRAE(DIA; 7; 20)

Se mejoró la interfaz de usuario con un diseño más atractivo y profesional, optimizando la experiencia visual sin alterar la lógica original.

OBS: Por el momento solo se puede descargar uno por uno, salon por salon. Se estara revisando la opcion de descargar todos de un solo click.

✨ Características

Lectura de datos desde un archivo Excel (curso, salón, docente, días, horas).

Generación automática de horarios por salón.

Exportación a PDF listo para impresión.

Interfaz mejorada con CSS puro.

🛠 Tecnologías

HTML

CSS

JavaScript

<img width="1920" height="1556" alt="ScreenCapture" src="https://github.com/user-attachments/assets/56ac8985-ef9f-43a9-bdd9-ac66efb66dfe" />


