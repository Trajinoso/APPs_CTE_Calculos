[README.md](https://github.com/user-attachments/files/29297028/README.md)
# Sistema de Cálculo de Protección contra el Rayo (CTE DB-SUA 8)
**ID_PROYECTO:** PROY_SUA8_2026 | **ÚLTIMA VERSIÓN DE INFORME VINCULADO:** ITR.SUA8_260624-01 v1.0

Este repositorio contiene la herramienta técnica autocontenida para la justificación normativa de la necesidad de instalación de pararrayos y la determinación de su nivel de protección exigido, cumpliendo estrictamente con el Código Técnico de la Edificación (CTE) de España, Documento Básico SUA 8.

## Historial de Requerimientos Acumulados
* **Módulo de Configuración de Proyecto [Implementado]**: Registro persistente de metadatos (Nombre del proyecto, Ubicación, Expediente).
* **Módulo de Entradas Geométricas y Locales [Implementado]**: Introducción de dimensiones rectangulares ($L, W, H$) y de la densidad de impactos sobre el terreno ($N_g$) con control estricto de rangos.
* **Matriz de Selección No Ambigua de Coeficientes [Implementado]**: Configuración asistida mediante selectores descriptivos para los coeficientes normativos ($C_1, C_2, C_3, C_4, C_5$).
* **Motor Analítico de Frecuencias y Eficiencia [Implementado]**: Cálculo en tiempo real de la superficie de captura ($A_e$), de la frecuencia esperada ($N_e$), de la frecuencia admisible ($N_a$) y de la eficiencia del sistema ($E$).
* **Persistencia Local [Implementado]**: Integración nativa con `window.localStorage` para evitar la pérdida de datos de diseño al recargar la pestaña.
* **Módulo de Documentación Integrado [Implementado]**: Sección nativa dentro de la interfaz que permite consultar y copiar el Informe Técnico de Requisitos (ITR) en formato Markdown para garantizar la auditoría del software.
* **Motor de Impresión Corporativa e Informe Ampliado [Implementado]**: Generador de informes en formato DIN A4 con la identidad visual corporativa provista (azul/naranja) optimizado para la exportación a PDF nativo del sistema operativo.

## Bitácora de Cambios (Changelog)
* **v1.0 (24/06/2026)**: Versión inicial del ecosistema. Consolidación de fórmulas del CTE DB-SUA 8, definición de interfaz adaptativa, almacenamiento local automatizado y estructuración del layout de impresión.
