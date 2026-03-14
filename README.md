# Blas Cuagliarella
Software Architect & Tech Lead

Especializado en el diseño, desarrollo y escalabilidad de plataformas B2B transaccionales. Mi enfoque técnico se basa en arquitecturas server-first, tipado estricto y despliegues robustos en la nube.

## Proyecto Actual: Redlic
Actualmente liderando la arquitectura y desarrollo de **[Redlic](https://project-222vz.vercel.app/)**, una plataforma B2B a nivel nacional para la industria de autopartes, conectando desarmaderos, repuesteras y talleres mecánicos.

## Arsenal Tecnológico
* **Ecosistema Core:** Next.js 16 (App Router), React, Node.js
* **Lenguajes:** TypeScript (Tipado estricto al 100%)
* **Datos & Autenticación:** PostgreSQL, Supabase (Auth + Row Level Security), Prisma ORM
* **Arquitectura Frontend:** Tailwind CSS, Zustand (Estado Global Modular), React Hook Form + Zod
* **Infraestructura & Telemetría:** Vercel, Sentry, Playwright (E2E automatizado), Husky/Lint-Staged

## Principios de Arquitectura
* **Modularidad Estricta:** Separación absoluta entre ensambladores (Server Components) y nodos interactivos de UI. Cero código monolítico.
* **Seguridad de Tipos:** Zod como escudo innegociable en validaciones y mutaciones. Tolerancia cero al uso de tipados dinámicos en producción.
* **Optimización de Estado:** Prohibido el *prop drilling*. El estado efímero del cliente se maneja exclusivamente mediante stores microscópicos.
* **Despliegues Resilientes:** CI/CD automatizado, integraciones validadas por pre-commits y observabilidad en tiempo real.
