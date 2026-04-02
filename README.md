=================================
Proyecto de pruebas automatizadas
=================================
DESCRIPCIÓN:
Este repositorio contiene la evidencia de pruebas de automatización 
y rendimiento realizadas sobre APIs públicas y entornos de práctica.

ESTRUCTURA DEL REPOSITORIO:
- /jmeter: Contiene los Planes de Prueba (.jmx) y el archivo de datos (.csv).
- /prueba-qa: Contiene los proyectos de automatización:
    * Selenium (E2E) para validación de formularios.
    * Karate (API) para validación de contratos y flujos REST.

INSTRUCCIONES DE EJECUCIÓN:

1. Pruebas de Rendimiento (JMeter):
   - Abrir Apache JMeter y cargar los archivos .jmx.
   - En el ejercicio de Login, validar que el componente 'CSV Data Set Config' 
     tenga la ruta relativa correcta al archivo 'usuarios.csv'.
   - Ejecutar los grupos de hilos y observar los resultados en el 
     'Informe de Resumen' y 'Gráfico de Resultados'.

2. Automatización Web (Selenium):
   - Importar la carpeta como proyecto Maven en su IDE (IntelliJ/Visual Studio Code).
   - Ejecutar los tests mediante TestNG para validar las pruebas.

3. Automatización de API (Karate):
   - Ejecutar los archivos .feature para validar los códigos de estado 
     y esquemas JSON de las respuestas.
