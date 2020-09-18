# Reporte de Trabajo Terminal 2: Cansat con sistema de descenso por autorrotación.

Este repositorio continene el código en Latex del reporte técnico realizado para obtener el título de Ingeniero en Mecatrónica.

## Resumen

El presente trabajo muestra una solución al problema de diseñar un CanSat con un sistema de descenso por autorrotación. Esta idea surge del concurso internacional [Annual CanSat Competition](http://www.cansatcompetition.com/index.html) llevada a cabo en Estados Unidos. La solución presentada en este documento está guiada por los requerimientos dados por la competencia en su edición 2019.

Se comenzará abordando los temas relacionados con el diseño preliminar del sistema, haciendo uso de diferentes herramientas de diseño que poseen un enfoque funcional. Posteriormente, se hablará sobre la importancia de definir funciones basadas en requerimientos, para después mostrar la jerarquía y composición de los sistemas y subsistemas del CanSat. Por último, en esta primera sección, se mostrará el concepto final del CanSat.

Seguido de esto, se entrará de lleno en el diseño detallado de todos los sistemas y subsistemas del CanSat, mostrando los criterios, métodos y herramientas usados para la concepción de cada uno de manera individual. Serán abordados los sistemas electrónico y de gestión de información, seguido de los sistemas estructural y de energía, así como los sistemas propios del CanSat.

Posteriormente, se mostrarán las pruebas de integración y verificación de los sistemas y subsistemas, así como los resultados obtenidos en cada prueba. Al reportar las pruebas se menciona en cada una los requerimientos que se pretendían verificar, el procedimiento que se usó, los resultados esperados y los resultados obtenidos.

También se abordará el análisis de los resultados generados durante las pruebas hechas al CanSat en su totalidad. Estas pruebas corresponden a los lanzamientos realizados con un dron y a una altura mucho menor de la especificada en la competencia en su edición 2019. Aquí se podrán observar las gráficas generadas de los datos obtenidos del CanSat durante los lanzamientos. Finalmente, se presentarán las conclusiones.

<p align="center">
  <img width="550" height="550" src="https://github.com/YaoSerrato/TT2_CanSat_Reporte/blob/master/imagenes/imgmeca/EstructuraCansat.png">
</p>

## Sistemas y Subsistemas del CanSat

El diseño del CanSat se realizó bajo un enfoque funcional, es decir, con base en las necesidades y los requerimientos identificados se definieron las funciones que el CanSat debía cumplir, sin entrar en detalles de la implementación para lograr tales funciones. Con base en la lista de funciones, también llamada Arquitectura Funcional, se definió la Arquitectura Física, que es la transición de una perspectiva abstracta (funciones) a algo concreto (sistemas y subsistemas). La siguiente imagen muestra la Arquitectura Física del CanSat donde su puede observar que éste está compuesto de 8 sistemas: 4 sistemas que todo sistema mecatrónico comúnmente tiene (sistema estructural, sistema de energía, sistema central de manejo del comportamiento y sistema de procesamiento de datos); así como 4 sistemas propios del CanSat (sistema de reducción de velocidad de descenso, sistema de liberación del vehículo científico, sistema de estación en Tierra y sistema de registro de descenso).

<p align="center">
  <img height="700" src="https://github.com/YaoSerrato/TT2_CanSat_Reporte/blob/master/imagenes/diseniosist/SistemasSubsistemas.PNG">
</p>
