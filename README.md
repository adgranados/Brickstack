# 🧠 [Brickstack](https://github.com/adgranados/Brickstack) ModularAI Platform

Este monorepo contiene la plataforma base para **construcción dinámica de sistemas empresariales inteligentes**, incluyendo ERP, CRM, flujos de trabajo y otras aplicaciones centradas en procesos y tareas. Utiliza un **asistente de IA generativa** para crear automáticamente:

- Componentes de negocio
- Formularios de captura de datos
- Estructuras relacionales y no relacionales
- Módulos ajustables según dominio y contexto

## 📦 Estructura del monorepo

- `/front`: Aplicación frontend en Angular, interfaz dinámica generada a partir de modelos y flujos definidos por el usuario.
- `/back`: Backend en NestJS, responsable de orquestar la generación de componentes, gestionar la lógica de negocio y exponer APIs.
- `/orchestrator`: Servicio encargado de interpretar instrucciones del usuario, activar agentes inteligentes, generar código y configurar dependencias.
- `/infra`: Definición de infraestructura como código (Terraform, CDKTF, Docker) para entornos de desarrollo, pruebas y producción.
- `/tests/n2n`: Breve descripción de las pruebas de extremo a extremo.

## 🧩 Características clave

- 🧠 **Asistente AI** que interpreta instrucciones y crea lógica de negocio.
- ⚙️ **Módulos y formularios autogenerados** a partir de modelos definidos en lenguaje natural.
- 🔄 **Persistencia híbrida**: base de datos relacional (PostgreSQL) para datos estructurados y base no relacional (MongoDB, Redis u otra) para eventos y almacenamiento dinámico.
- 🔐 **Multitenencia**, control de acceso granular y auditoría por módulo y campo.

## 🚀 Casos de uso

- Automatización de procesos internos (RRHH, ventas, soporte)
- Creación rápida de CRMs personalizados por área
- ERP modulares sin necesidad de programar desde cero

## 📝 Licencia

Distribuido bajo licencia [GNU GPL v3.0](./LICENSE) — El código puede ser modificado y reutilizado, siempre que se mantenga la misma licencia para obras derivadas.
