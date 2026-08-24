# Yandira Martínez Jaimes



<img src="portada 2.png" width="320" alt="Yandira Martínez Jaimes">



**QA Engineer Junior | Testing Manual y de API | Background en edición de video**

[LinkedIn](https://www.linkedin.com/in/yandira-martínez-qa-engineer/) · [CV Profesional](./Yandira_Martinez_CV_QA_En.pdf) · [Contacto](mailto:martinez.yandira28@gmail.com)

---

## 👋 Sobre mí

Vengo del mundo de la edición de video, donde aprendí que los detalles importan, que un pequeño error puede arruinar el resultado final y que la calidad no es opcional. Cuando descubrí el área de QA, me di cuenta de que esas mismas habilidades —ojo crítico, análisis meticuloso y resolución de problemas— son exactamente lo que se necesita para garantizar que el software funcione como debe.

Lo que me apasiona del QA es pensar como usuario: anticipar dónde puede fallar algo antes de que llegue a quien lo va a usar. Para mí, un buen tester no solo encuentra errores, protege la experiencia del usuario. Estoy en constante aprendizaje y siempre abierta a nuevas oportunidades, proyectos y conexiones en el mundo tech. ¡No dudes en escribirme!

---

## 🔧 Herramientas y habilidades técnicas

**Testing manual y de API:** Manual Testing · Test Case Design · Bug Reporting · API Testing (REST y SOAP) · Postman · Mobile Testing

**Automatización:** Python · Selenium · Page Object Model · Pytest

**Bases de datos:** SQL (JOIN, GROUP BY, HAVING, CASE WHEN) · PostgreSQL · Conexión SSH

**Otros:** Jira · Chrome DevTools (CDP) · Android Studio (emulador) · Análisis de logs con Unix (grep) · OAuth 2.0 / tokens / headers Authorization · Git/GitHub

---

## 🚀 Proyectos destacados

Cada carpeta enlazada abajo tiene su propio README explicando el objetivo, el proceso y los resultados con más detalle.

### 1. Urban Routes — Automatización con Selenium
**Desafío:** Asegurar que el flujo completo de solicitud de un viaje (ruta, método de pago, confirmación) funcione de forma consistente ante cambios en la aplicación.
**Proceso:** Automatización de 9 casos de prueba con Python, Selenium y Page Object Model. Implementé la intercepción del código de verificación SMS leyendo los logs de red del navegador vía Chrome DevTools Protocol (CDP).
**Resultado:** Proyecto aprobado en el primer intento; 9 pruebas automatizadas, código organizado con POM y publicado en GitHub.
🔗 [Ver repositorio](https://github.com/martinezyandira-qa/qa-project-Urban-Routes-es)

### 2. Urban Grocers — Pruebas de API
**Desafío:** Validar que la API de un servicio de entrega de comestibles maneje correctamente los datos entre la aplicación y la base de datos.
**Proceso:** Diseñé un checklist estructurado y ejecuté 60 pruebas en vivo con Postman sobre los endpoints REST y SOAP, con validación cruzada en PostgreSQL vía SSH. Analicé logs de servidor con comandos Unix (grep) filtrando por IP, fecha y código de estado HTTP.
**Resultado:** 26 bugs documentados y reportados antes de llegar a producción (validación de campos, manejo de errores e integridad de datos).
🔗 [Ver repositorio](https://github.com/martinezyandira-qa/qa-project-Urban-Grocers-app-es)

### 3. Urban Scooter — Proyecto integral de QA (Web, Móvil y API)
**Desafío:** Cubrir de forma integral la calidad de una aplicación de renta de scooters a través de tres plataformas distintas: web, móvil y API.
**Proceso:** Diseñé y ejecuté 222 casos de prueba usando partición de equivalencia, valores límite (BVA) y tablas de decisión. Probé la app del repartidor en un emulador Android con Android Studio.
**Resultado:** 30 bugs documentados y reportados en Jira. Proyecto final del bootcamp: integra teoría, diseño de casos, ejecución y reporte de bugs en 3 plataformas distintas.
🔗 [Ver repositorio](https://github.com/martinezyandira-qa/qa-project-Urban-Scooter-es)

### 4. api_stand_tests — Automatización de pruebas de API
**Desafío:** Validar el comportamiento del endpoint de creación de usuarios ante distintos valores del campo `firstName`, incluyendo casos límite y entradas inválidas.
**Proceso:** Automaticé 10 casos de prueba con Python, pytest y requests, aplicando partición de equivalencia y valores límite (BVA): longitud del campo (1, 2, 15, 16 caracteres), caracteres no latinos, símbolos especiales, dígitos, campo vacío, campo faltante y tipo de dato incorrecto.
**Resultado:** Cobertura automatizada de las validaciones de entrada del endpoint, con aserciones sobre código de estado, mensaje de error y consistencia de los datos creados.
🔗 [Ver repositorio](https://github.com/martinezyandira-qa/api_stand_tests)

---

## 📫 Contacto

¿Buscas a alguien con ojo crítico para el detalle y ganas de seguir creciendo en QA? Escríbeme a [martinez.yandira28@gmail.com](mailto:martinez.yandira28@gmail.com) o conéctate conmigo en [LinkedIn](https://www.linkedin.com/in/yandira-martínez-qa-engineer/).
