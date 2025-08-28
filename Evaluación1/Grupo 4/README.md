# Informe War Room - Grupo 4
### Área: Administración de Bases de Datos

---

## Contexto del Caso
El servidor **PostgreSQL** que almacena información crítica de clientes y transacciones ha presentado una falla inesperada.  
Durante la revisión, se identifican los siguientes problemas:

- El último **backup completo** fue realizado hace 20 días.  
- No existe un **plan de recuperación documentado** (procedimientos de restore).  
- La base de datos almacena datos sensibles (RUT, direcciones, correos) **sin cifrado**.  
- El servidor físico es antiguo, sin redundancia de discos ni alta disponibilidad.  
- No se aplican parches de seguridad desde hace más de un año.  

### Situación crítica:
El Gerente Comercial advierte que si la información no se recupera, la empresa podría enfrentar **demandas por incumplimiento contractual** y sanciones legales por violar normativas de protección de datos.  

---

## Tareas a Realizar (Trabajo de Auditoría)

### 1. Análisis de Riesgos
- Identificar **mínimo 3 riesgos operativos** (ej.: pérdida total de datos, corrupción de la BD, accesos no autorizados a datos sensibles).  
- Identificar **mínimo 2 riesgos de gestión** (ej.: incumplimiento normativo, falta de continuidad de negocio).  
- Clasificar riesgos en Probabilidad × Impacto siguiendo **ISO/IEC 27005** y **NIST RMF (Risk Assessment)**.  
- Representar los hallazgos en un **mapa de riesgos**.  

---

### 2. Matriz RACI
Definir roles y responsabilidades para la gestión de bases de datos:  
- **Administrador de BD**  
- **Gerente de TI**  
- **Equipo de Seguridad Informática**  
- **Auditor Interno**  
- **Usuarios de negocio**  

Actividades mínimas:  
- Gestión de respaldos.  
- Aplicación de parches de seguridad.  
- Cifrado y protección de datos sensibles.  
- Recuperación ante desastres.  
- Reporte a la gerencia y cumplimiento regulatorio.  

---

### 3. Checklist de Control
Basado en **ISO/IEC 27002:2022** y **ISO/IEC 27001:2022**: 


---

### 4. Cuestionario de Auditoría
Preguntas de ejemplo para entrevistar a:  
- Administrador de BD  
- Gerente de TI  
- Responsable de Seguridad  

---

### 5. Presentación Final
El grupo debe preparar una **presentación de 5 minutos**, con:  
1. Resumen del incidente y contexto.  
2. Riesgos operativos y de gestión identificados.  
3. Matriz RACI propuesta.  
4. Checklist y cuestionario de auditoría.  
5. Recomendaciones y controles alineados a estándares (ISO 27001, 27002, NIST RMF).  

---

## Recursos de Referencia
- **NIST RMF**: https://csrc.nist.gov/projects/risk-management  
- **ISO/IEC 27005:2022** – Gestión de riesgos de seguridad de la información  
- **ISO/IEC 27002:2022** – Controles de seguridad de la información  
- **ISO/IEC 27001:2022** – SGSI y requisitos de certificación  

---
