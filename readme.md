# QA Trabajos de Roman Mysyura

Este es el repositorio con los trabajos que he hecho durante la formación en Logirail.

Hemos hecho un proyecto en TestLink sobre una aplicación de control de asistencia de empleados. Yo me he encargado de hacer la parte de requisitos, casos de uso y casos de prueba del "Subsistema de encargado"

Primero de todo, he hecho el dibujo con un monigote del encargado y sus requisitos.
![Los requisitos que he echo](img/encargado.png)
Luego los he puesto en TestLink
![Los requisitos que he echo](img/Captura001.png)

Después, he hecho las pruebas de aceptación.

![Los pruebas de aceptacion](img/Captura002.png)

Luego de hacer esto, he ejecutado las pruebas de rendimiento, y después de enviar, se ha guardado el estado en MantisDB

![Los pruebas de aceptacion](img/Captura003.png)
![Los pruebas de aceptacion](img/Captura004.png)

La parte más divertida fue hacer las pruebas E2E con Selenium IDE. Aquí tienes el proyecto que he hecho probando la página web para testing:
[Ver archivo](https://github.com/RomanMysyura/GildedRoseQA-JUnit/blob/master/Selenium%20IDE/Pruebas%20E2E.side)

Durante esta formación he aprendido muchas cosas interesantes, como trabajar con SoapUI, Postman, JMeter, ejecutar los tests JUnit con Maven y ver los resultados en SonarQube. La parte más interesante para mí fue Jenkins, que puede analizar el repositorio GitHub, y cuando detecta que el repositorio se ha actualizado, ejecuta los tests.

![Img](img/Captura005.png)
