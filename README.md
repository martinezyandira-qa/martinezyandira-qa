 <div align="center">
<h1>Hola, soy Yandira 👋</h1>
</div>

<div align="center">
  <img src="portada 2.png" width="100%">
</div>

**QA Engineer | Manual & API Testing | Automatización | IA aplicada al Testing**

[LinkedIn](https://www.linkedin.com/in/yandira-mart%C3%ADnez-qa-engineer/) · [CV Profesional](./Yandira_Martinez_CV_QA_Engineer.pdf) · [Contacto](mailto:martinez.yandira28@gmail.com)

---

## 👋 Sobre mí

Soy QA Engineer con experiencia práctica en pruebas manuales, testing de APIs, SQL y automatización con Python y Selenium. Mi trayectoria comenzó en el mundo audiovisual, donde desarrollé una atención especial al detalle, al cumplimiento de requisitos y al control de calidad.

Actualmente combino mis conocimientos de QA con el desarrollo de aplicaciones y la automatización de procesos mediante inteligencia artificial.

He desarrollado proyectos propios que integran APIs, bases de datos, automatizaciones y aplicaciones web. En ellos aplico análisis de requisitos, validaciones funcionales, pruebas de regresión y documentación de defectos.

Mi objetivo es seguir creciendo profesionalmente en Quality Assurance, especialmente en automatización e inteligencia artificial aplicada al software testing.

---

## 🔧 Herramientas y habilidades técnicas

**QA & Testing:** Manual Testing · Functional Testing · API Testing (REST/SOAP) · Test Case Design · Bug Reporting · Regression Testing · Boundary Value Analysis · Equivalence Partitioning · Decision Tables · Mobile Testing

**Automatización:** Python · Pytest · Selenium · Page Object Model · Make

**API & Bases de datos:** Postman · REST APIs · JSON · SQL · PostgreSQL · Google Sheets · Google Apps Script

**Desarrollo e integraciones:** JavaScript · HTML · CSS · Firebase Hosting · Telegram Bot API · OpenAI API

**Herramientas:** Jira · Git/GitHub · Chrome DevTools · Android Studio · SSH · Unix/grep

**Formación actual:** Máster en Inteligencia Artificial (Daxus) · AI-powered QA: Automatización y Agentes en Software Testing (Udemy)

---

## 🚀 Proyectos destacados

### 1. Magnific Control de Créditos — Desarrollo de PWA y Quality Assurance

**Desafío:** Desarrollar una solución para gestionar el consumo y las compras de créditos de inteligencia artificial utilizados en diferentes producciones audiovisuales, manteniendo registros independientes por programa y un saldo global compartido.

**Proceso:** Diseñé y desarrollé una Progressive Web App (PWA) utilizando JavaScript, Google Apps Script, Google Sheets y Firebase Hosting. Implementé autenticación por roles, validaciones de formularios, registro de generaciones, compras y reportes por episodio.

Durante el desarrollo realicé verificaciones funcionales y pruebas de regresión, identificando y corrigiendo problemas relacionados con el inicio de sesión, manejo de fechas y actualización de la PWA.

**QA:** Elaboré un plan de pruebas con 20 casos funcionales y 8 escenarios de API propuestos, incluyendo validaciones positivas, negativas, límites, integridad de datos y control de acceso. El documento distingue verificaciones observadas de pruebas pendientes.

**Resultado:** Aplicación PWA funcional con arquitectura multiprograma, integración frontend–backend y documentación técnica y de QA.

**Tecnologías:** JavaScript · HTML · CSS · Google Apps Script · Google Sheets · Firebase Hosting · REST API · Git/GitHub

🔗 [Ver repositorio](https://github.com/martinezyandira-qa/magnific-ai-credit-manager)

### 2. Automatización Financiera Inteligente — Make, Telegram y OpenAI

**Desafío:** Automatizar el registro de movimientos financieros y los recordatorios de pagos recurrentes, reduciendo la necesidad de introducir información manualmente en hojas de cálculo.

**Proceso:** Diseñé e implementé dos escenarios de automatización en Make:

- **Registro inteligente de movimientos:** recepción de mensajes mediante Telegram, interpretación con OpenAI, transformación a JSON y almacenamiento estructurado en Google Sheets.
- **Recordatorios de pagos:** consulta de obligaciones recurrentes en Google Sheets, evaluación de fechas de vencimiento y días de anticipación, y envío de notificaciones por Telegram.

**QA:** Realicé verificaciones funcionales durante la implementación y documenté escenarios de prueba para validar la clasificación de movimientos, los importes, la estructura JSON, las fechas de vencimiento y las notificaciones. También identifiqué riesgos relacionados con registros y recordatorios duplicados.

**Resultado:** Dos escenarios operativos de automatización para registrar ingresos y gastos y enviar recordatorios. La generación automática de reportes financieros continúa en desarrollo.

**Tecnologías:** Make · Telegram Bot API · OpenAI · JSON · Google Sheets · API Integration · QA Testing

🔗 [Ver repositorio](https://github.com/martinezyandira-qa/make-telegram-finance-automation)

### 3. Urban Routes — Automatización con Selenium

**Desafío:** Asegurar que el flujo completo de solicitud de un viaje (ruta, método de pago y confirmación) funcione de forma consistente ante cambios en la aplicación.

**Proceso:** Automaticé 9 casos de prueba con Python, Selenium y Page Object Model. Implementé la intercepción del código de verificación SMS leyendo los logs de red del navegador mediante Chrome DevTools Protocol (CDP).

**Resultado:** Proyecto aprobado en el primer intento; 9 pruebas automatizadas, código organizado con POM y publicado en GitHub.

🔗 [Ver repositorio](https://github.com/martinezyandira-qa/qa-project-Urban-Routes-es)

### 4. Urban Grocers — Pruebas de API

**Desafío:** Validar que la API de un servicio de entrega de comestibles maneje correctamente los datos entre la aplicación y la base de datos.

**Proceso:** Diseñé un checklist estructurado y ejecuté 60 pruebas en vivo con Postman sobre endpoints REST y SOAP, con validación cruzada en PostgreSQL vía SSH. Analicé logs de servidor con comandos Unix (grep), filtrando por IP, fecha y código de estado HTTP.

**Resultado:** 26 bugs documentados y reportados antes de llegar a producción, relacionados con validación de campos, manejo de errores e integridad de datos.

🔗 [Ver repositorio](https://github.com/martinezyandira-qa/qa-project-Urban-Grocers-app-es)

### 5. Urban Scooter — Proyecto integral de QA (Web, Móvil y API)

**Desafío:** Cubrir de forma integral la calidad de una aplicación de renta de scooters a través de tres plataformas: web, móvil y API.

**Proceso:** Diseñé y ejecuté 222 casos de prueba utilizando partición de equivalencia, valores límite (BVA) y tablas de decisión. Probé la aplicación del repartidor en un emulador Android con Android Studio.

**Resultado:** 30 bugs documentados y reportados en Jira. Proyecto final del bootcamp, integrando análisis de requisitos, diseño de pruebas, ejecución y reporte de defectos.

🔗 [Ver repositorio](https://github.com/martinezyandira-qa/qa-project-Urban-Scooter-es)

### 6. api_stand_tests — Automatización de pruebas de API

**Desafío:** Validar el comportamiento del endpoint de creación de usuarios ante distintos valores del campo `firstName`, incluyendo casos límite y entradas inválidas.

**Proceso:** Automaticé 10 casos de prueba con Python, Pytest y Requests, aplicando partición de equivalencia y valores límite (BVA): longitudes válidas e inválidas, caracteres no latinos, símbolos especiales, dígitos, campos vacíos y tipos de datos incorrectos.

**Resultado:** Pruebas automatizadas de validación de entradas con aserciones sobre códigos de estado, mensajes de error y consistencia de datos.

🔗 [Ver repositorio](https://github.com/martinezyandira-qa/api_stand_tests)

---

## 📚 Formación continua

- **QA Engineering Certificate** — TripleTen (2026)
- **Máster en Inteligencia Artificial** — Daxus (en curso)
- **AI-powered QA: Automatización y Agentes en Software Testing** — Udemy (en curso)

---

## 📫 Contacto

Estoy interesada en oportunidades de **QA Engineer Junior, QA Analyst, Manual Tester y QA Automation Junior**, donde pueda aportar mis conocimientos de testing, análisis de requisitos, automatización e integración de tecnologías.

Puedes escribirme a [martinez.yandira28@gmail.com](mailto:martinez.yandira28@gmail.com) o conectar conmigo en [LinkedIn](https://www.linkedin.com/in/yandira-mart%C3%ADnez-qa-engineer/).
