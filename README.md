# Blas Cuagliarella
Software Architect & Tech Lead

Especializado en el diseño, desarrollo y escalabilidad de plataformas B2B transaccionales y sistemas de gestión integrales. Mi enfoque técnico se basa en arquitecturas robustas, tipado estricto, integraciones complejas de Web Services y despliegues seguros tanto en la nube como en entornos de escritorio.

## Proyectos Destacados

* **[Gridlic](gridlic.com) (Ex Redlic):** Liderando la arquitectura y desarrollo de una plataforma web B2B a nivel nacional para la industria de autopartes, diseñada para conectar de forma eficiente desarmaderos, repuesteras y talleres mecánicos.
* **MARMARY:** Desarrollo y arquitectura de un sistema de gestión local para el sector retail, incluyendo la migración de bases de datos legacy y la integración criptográfica directa con los Web Services gubernamentales (AFIP) para la facturación electrónica.

## Arsenal Tecnológico

* **Ecosistema Web Core:** Next.js (App Router), React, Node.js
* **Ecosistema Desktop & Scripting:** Python 3, Tkinter, PyInstaller
* **Lenguajes:** TypeScript (Tipado estricto al 100%), Python
* **Datos & Autenticación:** PostgreSQL, Supabase (Auth + Row Level Security), Prisma ORM, SQLite
* **Arquitectura Frontend:** Tailwind CSS, Zustand (Estado Global Modular), React Hook Form + Zod
* **Integraciones & Protocolos:** Web Services (SOAP/XML), Criptografía de claves públicas (OpenSSL, X.509)
* **Infraestructura, Telemetría & Testing:** Vercel, Sentry, Playwright (E2E automatizado), Husky/Lint-Staged

## Principios de Arquitectura

* **Modularidad Estricta:** Separación absoluta entre la capa de presentación y la lógica de negocio. Uso riguroso de Server Components y aislamiento de los nodos interactivos de UI. 
* **Seguridad de Tipos y Validación:** Implementación de Zod como escudo innegociable para la validación de esquemas y mutaciones. Tolerancia cero al uso de tipados dinámicos en entornos de producción.
* **Optimización de Estado:** Eliminación del *prop drilling*. El estado efímero del cliente se maneja exclusivamente mediante stores microscópicos y focalizados.
* **Despliegues Resilientes:** Integraciones validadas por pre-commits obligatorios, cobertura de pruebas automatizadas y observabilidad proactiva de errores en tiempo real.
