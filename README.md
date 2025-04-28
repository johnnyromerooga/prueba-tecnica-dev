![Logo OGA](https://github.com/johnnyromerooga/prueba-tecnica-dev/blob/main/imgs/logo-oga.png?raw=true)

# 🚀 Prueba Técnica | Equipo DEV

---

## 📚 Índice

- [1. Introducción](#1-introducción)
  - [1.1 🎯 Objetivo](#11-objetivo)
  - [1.2 📏 Alcance](#12-alcance)
- [2. 🗄️ Base de datos](#2-base-de-datos)
- [3. ⚙️ Web API](#3-web-api)
- [4. 🖥️ Frontal](#4-frontal)
- [5. 🐳 Docker](#5-docker)
- [6. 📦 Entrega](#6-entrega)

---

# 1. Introducción

De cara a incorporar nuevos perfiles al equipo de desarrollo de la compañía, es necesario evaluar todas las capacidades técnicas de los candidatos.

## 1.1 🎯 Objetivo

El objetivo del documento es presentar un ejercicio completo, que sirva como prueba técnica y abarque todos los aspectos relevantes para el equipo de desarrollo.

Se realizará un ejercicio compuesto por varios módulos que, tratados de forma conjunta, darán lugar a una aplicación plenamente funcional.

## 1.2 📏 Alcance

El alcance de este documento incluye:

- 🗄️ Creación de un proyecto **SQL Server Database** con varias tablas relacionadas.
- ⚙️ Desarrollo de un proyecto **.NET Core 8** (mínimo) como backend utilizando Web API.
- 🖥️ Creación de un frontend en **Angular 17** (mínimo) para el mantenimiento de entidades.
- 🐳 Empaquetado de toda la solución en contenedores **Docker**.

---

# 2. 🗄️ Base de datos

Modelo de datos requerido:

![Diagrama BBDD](https://github.com/johnnyromerooga/prueba-tecnica-dev/blob/main/imgs/bbdd-diagram.png?raw=true)

Además, todas las tablas deberán incluir los siguientes **campos de auditoría**:

![Campos base](https://github.com/johnnyromerooga/prueba-tecnica-dev/blob/main/imgs/base-fields.png?raw=true)

---

# 3. ⚙️ Web API

El backend deberá ser un proyecto **.NET Core 8**, basado en el patrón **DDD** según [este artículo oficial](https://learn.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/ddd-oriented-microservice).

🔹 Requisitos:
- Documentación de la API con **Swagger**.
- Cobertura de **pruebas unitarias mínima del 80%**.
- Seguridad en todos los endpoints usando **token JWT**.
- Inclusión de una **colección de Postman** para validación de endpoints.

---

# 4. 🖥️ Frontal

El frontend será un proyecto **Angular 17** (mínimo).

🔸 Funcionalidades:
- Pantalla de **login** obligatorio.
- **Menú lateral** con:
  - 🚗 Vehículos
  - 🛻 Remolques

🔸 Reglas de negocio:
- Las **motos** no pueden tener remolques asignados.
- Los **coches** solo pueden asignar remolques de hasta **1500 kg**.
- Los **camiones** deben asignar remolques de más de **1500 kg**.

> ⚡ Se valorarán positivamente mejoras de **UI/UX** tanto en el diseño como en la experiencia de usuario.

---

# 5. 🐳 Docker

Cada componente de la aplicación:
- 🗄️ Base de datos
- ⚙️ Backend
- 🖥️ Frontend

deberá ser **dockerizado** en contenedores individuales.

---

# 6. 📦 Entrega

La entrega consistirá en:

- Un archivo comprimido `*.zip` con todos los proyectos.
- Alternativamente, un enlace a un repositorio donde se pueda descargar.

✅ **Forma de entrega:** correo electrónico o enlace directo.

---
