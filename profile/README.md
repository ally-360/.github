<p align="center">
  <img src="https://ally360.netlify.app/logo/logoFondoTransparentesvg.svg" width="200" alt="Logo de Ally360">
</p>

<h1 align="center">Ally360 - Tu empresa a la mano</h1>

<p align="center">
  ERP multi-tenant diseñado para emprendedores, pequeñas y medianas empresas en Colombia. Centraliza tu gestión operativa, facilita el cumplimiento normativo y digitaliza tu negocio de manera simple, segura y escalable.
</p>

---

## 📌 ¿Qué es Ally360?

**Ally360** es un sistema ERP en la nube enfocado en la digitalización y automatización de operaciones para negocios colombianos. Nuestra solución permite controlar facturación electrónica, inventarios, finanzas, ventas y más, todo desde una sola plataforma.

> 🎯 Nuestra misión: ayudar a las PyMEs a enfocarse en su crecimiento sin preocuparse por la complejidad tecnológica.

---

## 🧱 Arquitectura Modular

Ally360 se compone de microservicios independientes y aplicaciones frontend escalables. Esta organización permite extender funcionalidades fácilmente y mantener un sistema ágil y robusto.

### 🔧 Repositorios Backend

| Repositorio         | Descripción                                          |
|---------------------|------------------------------------------------------|
| `core-service`      | API central multi-tenant que orquesta los servicios  |
| `auth-service`      | Servicio de autenticación y autorización             |
| `mailer-service`    | Servicio para envío de correos electrónicos          |
| `storage-service`   | Manejo de almacenamiento en la nube (MinIO/S3)       |
| `manager-service`   | Servicio de gestión de tenants y accesos internos    |
| `common-service`    | Código compartido y utilidades entre microservicios  |

### 💻 Aplicaciones Frontend

| Repositorio             | Descripción                                          |
|-------------------------|------------------------------------------------------|
| `webapp-platform`       | App web para los clientes (tenants)                  |
| `webapp-admin`          | Panel administrativo para gestión de la plataforma   |

---

## 👥 Nuestros Clientes

Ally360 está diseñado especialmente para:

- **Emprendedores y Microempresas**: hasta 5 empleados y operaciones básicas.
- **Pequeñas Empresas**: entre 5 y 20 empleados que necesitan control de inventario, ventas y finanzas.
- **Medianas Empresas**: entre 20 y 100 empleados con operaciones más complejas y necesidad de reportes avanzados.

---

## 📦 ¿Qué incluye Ally360?

- Facturación electrónica conforme a la DIAN
- Gestión de inventario multibodega
- Punto de venta (POS)
- Control financiero y presupuestal
- Reportes y dashboards en tiempo real
- Escalabilidad modular
- Soporte para múltiples usuarios y roles
- Seguridad y cumplimiento legal colombiano

---

## 📈 Planes

- **Esencial**
- **Avanzado**
- **Elite**
- **Enterprise**

➡️ Más información en [Ally360]([https://ally360.co](https://ally360.netlify.app/)) *(en desarrollo)*

---

## 🧠 Tecnologías utilizadas

- **Frontend**: React, Material UI
- **Backend**: NestJS
- **Auth**: Keycloak (OpenID Connect)
- **Database**: PostgreSQL
- **Infraestructura**: Docker, CI/CD, Arquitectura de Microservicios

---

## 🚀 Misión

Facilitar la transformación digital de miles de empresas en Colombia con una solución intuitiva, económica y potente, que cumpla con las exigencias normativas y operativas de forma sencilla.

---

## 🤝 Contacto

Si eres desarrollador, contador, aliado estratégico o emprendedor interesado en digitalizar su negocio, contáctanos:


📧 danielestupinan0802@gmail.com
📍 Pereira, Risaralda, Colombia

---

> **Construido con 💙 por emprendedores para emprendedores**
