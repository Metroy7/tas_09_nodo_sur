# tas_09_nodo_sur
Plataforma Digital Resiliente Nodo Sur - Taller de Administración de Sistemas 2026
# Proyecto Integrador · Nodo Sur (2026)
**Asignatura:** Taller de Administración de Sistemas (EIN-090B)  
**Institución:** Universidad Técnica Federico Santa María · Sede Concepción  
**Profesor:** José Antonio Arellano V.  
**Grupo:** 09  

---

## 📌 Descripción del Proyecto
Este repositorio contiene la documentación, arquitectura de servicios y configuraciones para la modernización de la plataforma digital de la empresa **Nodo Sur**. El proyecto busca desplegar una infraestructura resiliente, escalable y segura, optimizada para soportar su portal corporativo y sistema de gestión de contenidos (CMS).

---

## 👥 Integrantes del Equipo
* **Alonso Jara Guevara**
* **Joaquín Sepúlveda Morales**
* **Francisca Di Genova**

---

## 🛠️ Resumen de la Solución Técnica
La infraestructura propuesta se despliega en un entorno virtualizado sobre **Proxmox VE (Nodo Alpha)** utilizando **Ubuntu Server 24.04 LTS** como sistema operativo base. La solución se compone de una arquitectura desacoplada en capas:

* **Acceso y Cifrado:** Punto de entrada único gestionado por **HAProxy**, encargado de la terminación TLS (HTTPS/443) y el balanceo de carga.
* **Capa Web / CMS:** Dos nodos backend redundantes (**WEB01** y **WEB02**) ejecutando **WordPress + WooCommerce** sobre pila LAMP/LNMP.
* **Capa de Datos:** Base de datos relacional independiente (**BD01** - MariaDB) aislada en red privada y accesible únicamente por los nodos web.
* **Operación y Gestión:** Nodos dedicados para monitoreo y alertas (**MON01**), respaldos periódicos (**BKP01**) y gestión SSH segura restringida mediante llaves públicas nominativas.

---

## 📂 Estructura del Repositorio

```text
├── docs/
│   ├── arquitectura_nodo_sur.png    # Diagrama de topología y flujos
│   └── informe_entrega1.pdf         # Informe técnico Entrega 1
├── scripts/                         # Scripts de aprovisionamiento y configuración
├── BITACORA.md                      # Registro de contribuciones por integrante
├── USO_IA.md                        # Trazabilidad y validación de uso de IA
└── README.md                        # Descripción general del proyecto
