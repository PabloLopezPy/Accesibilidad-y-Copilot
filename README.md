# Proyecto de Accesibilidad Web WCAG 2.2

Este repositorio contiene un proyecto para desarrollar y validar un prompt efectivo que permita a asistentes de IA como GitHub Copilot mejorar la accesibilidad web de códigos HTML según los estándares WCAG 2.2.

## Índice
1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [El Prompt](#el-prompt)
3. [Proceso de Desarrollo del Prompt](#proceso-de-desarrollo-del-prompt)
4. [Pasos para Validar](#pasos-para-validar)
5. [Herramientas de Validación](#herramientas-de-validación)

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un prompt efectivo para que asistentes de IA como GitHub Copilot puedan modificar código HTML existente para cumplir con los estándares de accesibilidad web WCAG 2.2. El proyecto incluye la creación del prompt, la validación de su efectividad y la documentación del proceso.


## El Prompt

A continuación se presenta el prompt desarrollado para mejorar la accesibilidad web:

```
Necesito desarrollar un prompt efectivo para que asistentes de IA como GitHub Copilot mejoren la accesibilidad web en código HTML según WCAG 2.2. Por favor, ayúdame con:

Un prompt detallado que cubra todos los criterios de accesibilidad WCAG 2.2 y etiquetas ARIA (nivel AA y AAA opcional).
Un ejemplo de código HTML original sin accesibilidad que incluya elementos diversos como formularios, tablas, imágenes y navegación.
El mismo código transformado para ser completamente accesible.
Una estructura para el repositorio GitHub donde documentar el proceso.
Un README.md bilingüe (español e inglés) detallando el desarrollo del prompt y los pasos para validación.
Recomendaciones sobre herramientas de validación como WAVE, Axe, Lighthouse, etc., y cómo usarlas para verificar la accesibilidad.
Consejos para iterar y perfeccionar el prompt hasta lograr que el código sea completamente accesible.

Necesito que el prompt final sea eficaz para transformar código HTML en versiones accesibles que cumplan con los estándares WCAG 2.2
```

## Proceso de Desarrollo del Prompt

El desarrollo del prompt siguió estos pasos:

1. **Investigación inicial**: Se estudiaron las pautas WCAG 2.2 para identificar los requisitos clave de accesibilidad.

2. **Categorización**: Los requisitos se agruparon en categorías lógicas para facilitar la implementación.

3. **Priorización**: Se dio prioridad a los aspectos más críticos de la accesibilidad como la estructura semántica, las alternativas textuales y la navegación por teclado.

4. **Iteración**: El prompt se refinó mediante pruebas con diferentes ejemplos de código HTML.

5. **Validación**: Se utilizaron herramientas de validación para verificar que los cambios sugeridos por el prompt mejoraban efectivamente la accesibilidad.

## Pasos para Validar

1. **Preparación del Código HTML Original**
   - Se crearon varios archivos HTML con diferentes estructuras (formularios, tablas, etc.)
   - Se guardaron estos archivos en la carpeta `ejemplos/*/original.html`
   - Se realizaron validaciones iniciales con herramientas como WAVE, Lighthouse, etc.
   - Se tomaron capturas de pantalla de los resultados iniciales

2. **Aplicación del Prompt**
   - Se utilizó el prompt desarrollado con GitHub Copilot y otros asistentes de IA
   - Se aplicó el prompt a cada uno de los archivos HTML originales
   - Se guardaron los resultados en `ejemplos/*/accesible.html`

3. **Validación de Resultados**
   - Se utilizaron múltiples herramientas de validación para evaluar la accesibilidad
   - Se tomaron capturas de pantalla de los resultados post-transformación
   - Se verificó el cumplimiento de los criterios WCAG 2.2 nivel AA y AAA

4. **Iteración y Mejora**
   - Se identificaron áreas donde el prompt no era efectivo
   - Se refinó el prompt para abordar estas deficiencias
   - Se repitió el proceso de validación con el prompt mejorado

## Herramientas de Validación

Para asegurar la calidad de los resultados, se utilizaró:

1. **WAVE (Web Accessibility Evaluation Tool)**
   - URL: https://wave.webaim.org/
   - Proporciona una evaluación visual de la accesibilidad
   - Identifica errores, alertas y características de accesibilidad
   - Permite validar páginas locales mediante extensiones de navegador

El prompt desarrollado se ha demostrado efectivo para mejorar la accesibilidad web en diversos tipos de páginas HTML, cumpliendo con los estándares WCAG 2.2 y proporcionando una experiencia más inclusiva para todos los usuarios.
