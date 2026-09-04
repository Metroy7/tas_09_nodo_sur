# Bitácora de Contribuciones del Equipo

**Asignatura:** Taller de Administración de Sistemas (EIN-090B)  
**Proyecto:** Nodo Sur (2026)  
**Grupo:** 09  
**Integrantes:** Alonso Jara Guevara, Joaquín Sepúlveda Morales, Francisca Di Genova  

---

## 📌 Resumen de Responsabilidades Principales

* **Alonso Jara Guevara:** Diseño conceptual de la arquitectura de red, definición de flujos de balanceo/HAProxy y estructuración de la matriz de recursos de cómputo.
* **Joaquín Sepúlveda Morales:** Gestión y saneamiento del repositorio GitHub, elaboración del informe técnico (Entrega 1) y definición de políticas de seguridad/SSH.
* **Francisca Di Genova:** Evaluación y comparativa del CMS (WordPress vs alternativas), análisis de riesgos/monitoreo y diseño de la estrategia de respaldos.

---

## 🗓️ Registro de Actividades por Hito

### Hito 1: Análisis de Requisitos y Elección de CMS
* **Fecha:** Última semana de Agosto 2026
* **Participantes:** Alonso Jara, Joaquín Sepúlveda, Francisca Di Genova
* **Actividades realizadas:**
  * **Francisca Di Genova:** Investigó y redactó la comparativa de los 4 CMS (WordPress, Ghost, Drupal, Joomla) evaluando seguridad, operación y compatibilidad.
  * **Alonso Jara:** Definió los requisitos verificables del negocio (REQ-01 al REQ-06) y sus criterios de aceptación.
  * **Joaquín Sepúlveda:** Recopiló y consolidó la primera versión de la plantilla del informe.

### Hito 2: Diseño de Arquitectura y Dimensionamiento
* **Fecha:** Primera semana de Septiembre 2026
* **Participantes:** Alonso Jara, Joaquín Sepúlveda, Francisca Di Genova
* **Actividades realizadas:**
  * **Alonso Jara:** Diseñó el diagrama de la topología de red (Frontend, DMZ, Backend, BD) y calculó la asignación de vCPU/RAM/Disco para Proxmox (Nodo Alpha).
  * **Francisca Di Genova:** Definición de la matriz de riesgos, controles recomendados y métricas de monitoreo (MON01 y BKP01).
  * **Joaquín Sepúlveda:** Elaboró la sección de usabilidad, accesos SSH nominativos y políticas de mínimo privilegio.

### Hito 3: Consolidación, Repositorio y Preparación de Defensa
* **Fecha:** Septiembre 2026
* **Participantes:** Alonso Jara, Joaquín Sepúlveda, Francisca Di Genova
* **Actividades realizadas:**
  * **Joaquín Sepúlveda:** Creó el repositorio de GitHub, configuró el `README.md`, los archivos de trazabilidad (`USO_IA.md`, `BITACORA.md`) y generó la versión `v1.0`.
  * **Alonso Jara:** Revisión final del informe técnico, validación del diagrama de arquitectura e integración de la declaración de IA.
  * **Francisca Di Genova:** Preparación de la pauta de exposición oral de 10 minutos y argumentos para la defensa de puntos únicos de falla (SPOF).
