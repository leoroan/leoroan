# Hola 👋 Soy Leandro

**Backend Developer · Node.js · Arquitectura de software**

Desarrollo aplicaciones backend poniendo el foco no solo en que funcionen, sino en que tengan una **arquitectura clara, mantenible y preparada para crecer**.

Trabajo principalmente con **Node.js, Express, Sequelize y MySQL**, y me interesa especialmente el diseño de APIs, la separación de responsabilidades, seguridad, testing y sistemas modulares.

---

## 🧑‍💻 Sobre mí

Soy un desarrollador backend con una fuerte orientación hacia la **arquitectura y el diseño de sistemas**.

Me interesa entender el problema completo antes de empezar a agregar código: cómo se relacionan los componentes, dónde debe vivir cada responsabilidad, cómo evolucionará una funcionalidad y qué decisiones evitarán problemas más adelante.

Algunas cosas que considero importantes:

* **Código limpio antes que código innecesariamente complejo.**
* **Responsabilidades bien separadas.**
* **Interfaces y contratos claros entre capas.**
* **Seguridad desde el diseño**, no como agregado posterior.
* **Testing como parte de la arquitectura.**
* **Configuración y ambientes correctamente aislados.**
* **Abstracciones cuando realmente aportan valor.**
* Evitar el clásico *"funciona, no lo toques"* cuando en realidad estamos acumulando deuda técnica.

No busco aplicar patrones porque sí. Prefiero una solución simple y bien diseñada antes que una arquitectura sofisticada que no resuelve ningún problema real.

---

## ⚙️ Stack principal

### Backend

* Node.js
* Express
* JavaScript / ECMAScript Modules
* Sequelize
* MySQL
* REST APIs
* Socket.IO

### Seguridad y arquitectura

* JWT
* Passport
* RBAC
* Roles y permisos
* Middleware / Policies
* Validación de datos
* Manejo centralizado de errores
* Logging estructurado
* Request tracing

### Testing

* Jest
* Supertest
* Unit testing
* Integration testing
* Tests de integridad
* Tests de flujos completos

### Herramientas y ecosistema

* Git / GitHub
* Docker
* Portainer
* Swagger / OpenAPI
* Supabase
* Resend
* Webhooks
* APIs de terceros
* Cline / herramientas de asistencia con IA

---

## 🏗️ Cómo pienso el backend

Me gusta trabajar con capas y responsabilidades explícitas:

Pero la arquitectura no termina ahí.

También me interesa cómo se resuelven problemas transversales

La idea es que cada componente tenga un propósito claro y que cambiar una parte del sistema no obligue a modificar todo lo demás.

---

## 🔐 Seguridad y autorización

Uno de mis intereses principales es construir sistemas donde la autorización no dependa de simples `if` dispersos por el código.

Trabajo con conceptos como:

* Roles
* Permisos granulares
* Wildcards
* Herencia de permisos
* Policies
* JWT
* Separación entre autenticación y autorización
* Protección de endpoints
* Validación de contexto

Esto permite que las reglas de acceso formen parte de la arquitectura y no sean simplemente lógica duplicada dentro de cada controller.

---

## 🧪 Testing como contrato

No considero los tests únicamente como una herramienta para comprobar que una función devuelve el resultado esperado.

También los utilizo para **definir y proteger el comportamiento del sistema**.

Una estructura que me resulta útil:

```text
tests/
├── unit/
├── integration/
├── integrity/
└── flows/
```

La intención es poder comprobar diferentes niveles del sistema:

* comportamiento aislado;
* interacción entre componentes;
* integridad de datos;
* flujos completos desde HTTP hasta persistencia.

Para mí, un test también puede funcionar como documentación ejecutable del contrato de una funcionalidad.

---

## 🔌 Sistemas desacoplados

También trabajo con integraciones donde el proveedor externo no debería contaminar el dominio interno.
Esto permite que el sistema pueda evolucionar sin quedar atado a una implementación específica del proveedor.

Es especialmente útil para:

* Webhooks
* WhatsApp
* APIs externas
* Servicios de email
* Integraciones con terceros

---

## 🧠 Actualmente explorando

Además del backend tradicional, estoy experimentando con:

* Arquitecturas orientadas a eventos.
* Webhooks y adapters.
* Integraciones con WhatsApp Business.
* Supabase y PostgreSQL.
* Edge Functions.
* Servicios de email mediante Resend y otros.
* Integración de IA en herramientas de desarrollo.
* Computer Vision con Python y OpenCV.
* Automatización y sistemas basados en datos.

Me interesa especialmente encontrar el punto donde estas tecnologías aportan **valor real al sistema**, en lugar de incorporarlas simplemente porque están de moda.

---

## 🚀 Filosofía de desarrollo

> **Primero entender el problema. Después diseñar la solución. Finalmente escribir el código.**

No me interesa acumular código.

Me interesa construir sistemas donde:

* cada pieza tenga una razón para existir;
* las dependencias sean explícitas;
* los errores sean controlables;
* los tests protejan los contratos;
* la seguridad sea parte del diseño;
* y el sistema pueda evolucionar sin convertirse en un *Frankenstein*.

Porque eventualmente todo código se vuelve legado.

La diferencia está en **qué tan difícil hacemos mantenerlo**.

---

## 📌 En resumen

**Backend Developer con mentalidad de arquitecto.**

Me gusta construir APIs y sistemas backend con **Node.js**, pero mi interés va más allá del framework: diseño de arquitectura, seguridad, persistencia, testing, integraciones y evolución del sistema.

No busco escribir más código.

Busco escribir **mejor código para resolver problemas reales**.
