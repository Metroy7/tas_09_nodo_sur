# Declaración y Trazabilidad del Uso de Inteligencia Artificial

**Asignatura:** Taller de Administración de Sistemas (EIN-090B)  
**Proyecto:** Nodo Sur (2026)  
**Grupo:** 09  
**Integrantes:** Alonso Jara Guevara, Joaquín Sepúlveda Morales, Francisca Di Genova  

---

## 📌 Declaración de Uso Responsable
En cumplimiento con las normas oficiales del proyecto integrador, el equipo declara que se utilizó la herramienta de IA Generativa **Gemini (Google)** como apoyo exclusivamente para:
1. La estructuración, ordenamiento y formato Markdown/Word del informe técnico de la Entrega 1.
2. La elaboración de matrices comparativas (criterios de selección de CMS, matrices de riesgo y dimensionamiento).
3. El refinamiento del lenguaje técnico y revisión de redacción.

---

## 📝 Registro de Prompts y Validaciones Técnicas

| Fecha | Herramienta | Propósito / Petición (Prompt) | Resultado / Sugerencia Obtenida | Validación y Cambios Aplicados por el Equipo |
| :--- | :--- | :--- | :--- | :--- |
| **08/2026** | Gemini | "Ayuda a comparar 4 CMS (WordPress, Ghost, Drupal, Joomla) en una tabla para un proyecto de alta disponibilidad." | Tabla comparativa de características, nivel de operación y facilidad de backup. | **Validado y modificado:** Se seleccionó WordPress + WooCommerce por compatibilidad con la infraestructura LAMP del laboratorio. |
| **08/2026** | Gemini | "Estructurar la matriz de recursos de cómputo (CPU, RAM, Disco) para balanceador, 2 nodos web, BD y monitoreo." | Propuesta de asignación de vCPU, RAM y almacenamiento por nodo. | **Validado:** Se ajustaron los valores de memoria y almacenamiento para adaptarse a la capacidad real del clúster Proxmox (Nodo Alpha). |
| **09/2026** | Gemini | "Revisar informe de Entrega 1 para detectar inconsistencias y generar plantilla de README.md para GitHub." | Observaciones sobre secciones vacías y estructura estándar de README.md. | **Aplicado:** Se completaron los criterios de aceptación vacíos y se subió la estructura oficial al repositorio. |

---

## 🛡️ Compromiso de Capacidad Técnica
El equipo garantiza que **ningún código, script o configuración fue aplicado sin previa revisión**:
* Toda la arquitectura y asignación de red fue analizada y aprobada por los integrantes.
* El grupo comprende en su totalidad las decisiones de diseño reflejadas en el informe y está preparado para defenderlas oralmente ante el docente sin apoyo de la herramienta.
