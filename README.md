# Implementación de Arquitectura Frontend en Plataforma de Gestión de Inversiones

La empresa necesita una plataforma de gestión de inversiones que combine una arquitectura monolítica con microfrontends. El objetivo es proporcionar una estructura React lista para usar, con package.json en cada carpeta y una configuración de webpack/typescript correcta.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Diseño y Aplicación de Arquitecturas Frontend |
| **Nivel** | junior-l3 |
| **Tipo** | practical |
| **Tiempo estimado** | 5-6 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Node.js 18+, npm, VS Code o similar.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Ejecuta `npm install && npm run build` (o `npm start`). Si no hay errores, estás listo.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Configuración Inicial

**Objetivo:** Preparar el entorno de desarrollo con la estructura básica de la plataforma.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Crear la estructura de carpetas para la plataforma.
- Configurar package.json en cada carpeta.
- Asegurar que la configuración de webpack y typescript esté correcta.

**Entregable:** Estructura de carpetas y archivos básicos configurados.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda que cada microfrontend debe tener su propio package.json.
- La configuración de webpack debe permitir la compilación de los microfrontends.

</details>

### Fase 2: Implementación del Módulo de Inversiones

**Objetivo:** Desarrollar el módulo de inversiones utilizando la estructura React.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Crear los componentes necesarios para el módulo de inversiones.
- Asegurar que los componentes sigan las buenas prácticas de React.
- Integrar los componentes en la plataforma.

**Entregable:** Módulo de inversiones funcional integrado en la plataforma.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda seguir las buenas prácticas de React al crear los componentes.
- Asegúrate de que los componentes se integren correctamente en la plataforma.

</details>

### Fase 3: Configuración de Webpack y Typescript

**Objetivo:** Asegurar que la configuración de webpack y typescript permita la compilación y ejecución de la plataforma.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Revisar y ajustar la configuración de webpack para que compile los microfrontends.
- Asegurar que la configuración de typescript permita la compilación sin errores.
- Comprobar que la plataforma se ejecuta correctamente.

**Entregable:** Plataforma compilada y ejecutada correctamente.

<details>
<summary>Pistas de conocimiento</summary>

- Revisa la configuración de webpack para asegurarte de que compile todos los microfrontends.
- Asegúrate de que la configuración de typescript no genere errores al compilar.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un microfrontend y cómo se relaciona con la arquitectura de la plataforma?
- **paraQueSirve**: ¿Para qué sirve la configuración de webpack en este proyecto?
- **comoSeUsa**: ¿Cómo se usa la estructura de carpetas para organizar los microfrontends?
- **erroresComunes**: ¿Cuáles son los errores comunes al configurar webpack y typescript?
- **queDecisionesImplica**: ¿Qué decisiones implica la elección de una arquitectura monolítica con microfrontends?

## Criterios de Evaluacion

- Configuración correcta de package.json en cada carpeta.
- Configuración correcta de webpack y typescript.
- Implementación funcional del módulo de inversiones.
- Plataforma compilada y ejecutada correctamente.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
