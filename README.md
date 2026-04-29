Calculadora de Calificaciones - Universidad de Córdoba

Aplicación web standalone para gestionar estudiantes y calcular calificaciones de manera automática. No requiere instalación ni conexión a internet.

Descripción

Esta herramienta permite registrar estudiantes, ingresar sus notas y obtener automáticamente la calificación definitiva según los porcentajes definidos. También incluye funciones de predicción que ayudan a determinar qué nota se necesita para aprobar o alcanzar un rendimiento alto.

Está pensada para uso académico, especialmente en contextos universitarios.

Características
Gestión completa de estudiantes (agregar, editar y eliminar)
Cálculo automático de la nota definitiva
Visualización del progreso por cortes
Predicción de notas necesarias para alcanzar objetivos
Sistema de estados (aprobado, reprobado, en riesgo, pendiente)
Búsqueda y filtrado de estudiantes
Estadísticas generales en tiempo real
Configuración de porcentajes de evaluación
Importación y exportación de datos en formato CSV
Almacenamiento local en el navegador
Diseño adaptable a dispositivos móviles
Tecnologías utilizadas
HTML5
CSS3
JavaScript (sin frameworks)
Uso
Abre el archivo calculadora-standalone.html en tu navegador.
Agrega estudiantes con sus respectivos datos.
Ingresa las notas de cada corte.
Consulta automáticamente los resultados y predicciones.

No se necesita conexión a internet para utilizar la aplicación.

Cálculo de calificaciones

La nota definitiva se calcula con base en los porcentajes definidos para cada corte. Por defecto:

Corte 1: 30%
Corte 2: 30%
Corte 3: 40%

Estos valores pueden modificarse en la sección de configuración, siempre que la suma sea igual a 100%.

Predicción de notas

El sistema calcula:

La nota mínima necesaria para aprobar (2.96)
La nota necesaria para alcanzar la máxima calificación (5.0)

También indica cuando un objetivo es inalcanzable.

Formato de importación CSV

El archivo debe tener la siguiente estructura:

nombre,codigo,corte1,corte2,corte3
Juan Perez,2023001,3.5,4.0,3.8
Maria Garcia,2023002,2.5,3.0,4.5
Atajos de teclado
Ctrl + N: Crear nuevo estudiante
Ctrl + S: Guardar formulario
ESC: Cerrar ventana modal
Validaciones
Las notas deben estar entre 0.0 y 5.0
El código del estudiante debe ser único
Los porcentajes deben sumar 100%
Almacenamiento

Los datos se guardan automáticamente en el navegador mediante localStorage.
Si se borran los datos del navegador, la información se perderá, por lo que se recomienda usar la opción de exportar CSV como respaldo.

Estructura del proyecto
calculadora-standalone.html

Todo el sistema está contenido en un solo archivo que incluye estructura, estilos y lógica.

Posibles mejoras
Sistema de autenticación de usuarios
Almacenamiento en la nube
Generación de reportes en PDF
Aplicación móvil
Integración con plataformas educativas
Licencia

Uso libre para fines educativos y personales.
