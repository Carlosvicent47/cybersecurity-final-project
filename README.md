# Auditoría y Bastionado de Infraestructura Crítica (Debian + WordPress)

### Proyecto Final de Ciberseguridad - 4Geeks Academy
**Autor:** Carlos Vicent Arnau Chuquispuma
**Curso:** Spain-CS-PT-11

---

## 📋 Descripción del Proyecto

Este repositorio contiene la documentación, evidencias y entregables técnicos del Proyecto Final de Ciberseguridad. El objetivo principal ha sido asegurar un servidor **Debian 12** que aloja un aplicativo **WordPress**, el cual había sido comprometido previamente.

El proyecto abarca el ciclo de vida completo de la ciberseguridad:
1.  **Fase Forense:** Análisis *post-mortem* para identificar el vector de entrada y el alcance de la intrusión.
2.  **Red Team (Auditoría):** Simulación de ataques para descubrir vulnerabilidades persistentes (Fuerza bruta, Enumeración, Misconfiguration).
3.  **Blue Team (Hardening):** Implementación de contramedidas defensivas (SSH, Fail2Ban, HTTPS/SFTP, Permisos).
4.  **Gobernanza (GRC):** Diseño de un Plan de Respuesta a Incidentes (NIST) y un SGSI alineado con ISO 27001.

---

## 📂 Estructura del Repositorio

El contenido se organiza de la siguiente manera para facilitar su revisión:

```text
📁 PROYECTO-FINAL-CARLOS-VICENT/
│
├── 📄 README.md                            # Este archivo (Resumen y Guía de inicio)
├── 📄 Proyecto Final - Carlos Vicent.pdf   #MEMORIA TÉCNICA COMPLETA (Informe principal)
├── 📄 Proyecto Final - Carlos Vicent.pptx  #Presentación Comercial
│
├── 📁 01_Evidencias_Graficas/          # Capturas de pantalla del proceso
│   └── 01_old/                         # Imagenes de la primera versión
│
├── 📁 02_Logs_Auditoria/               # Registros originales para cadena de custodia
│   ├── Evidencias                      
│   └── syslog/                         # Log del sistema
│
├── 📁 04_Forense --> https://drive.google.com/drive/folders/1qB_P0qcRgyn2aTRwgHQ40GvqC6e5halx?usp=sharing 
│
└── 📁 05_Maquina_Virtual/ --> https://drive.google.com/drive/folders/1v2xrGEPA5qz4A87dHX6U0_ercjLK3ofC?usp=sharing
