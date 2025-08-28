# Informe War Room - Grupo 3
### Área: Desarrollo de Software Interno

---

## Contexto del Caso
La empresa acaba de liberar en producción una **aplicación web de facturación** desarrollada por su equipo interno de 6 programadores.  
En menos de 24 horas los clientes reportan **fallas críticas**:

- Algunos clientes visualizan **facturas de otras empresas**.  
- No existen ambientes separados (desarrollo, pruebas y producción comparten la misma base de datos).  
- El equipo no cuenta con procesos de revisión de código (code review) ni pruebas automatizadas.  
- Existe una alta dependencia de un único programador senior, quien actualmente está de vacaciones.  

### Situación crítica:
El Gerente Financiero exige un informe urgente porque las fallas podrían significar **pérdida de clientes, sanciones legales y riesgos reputacionales**.  

---

## Tareas a Realizar (Trabajo de Auditoría)

### 1. Análisis de Riesgos
- Identificar **mínimo 3 riesgos operativos** (ej.: fuga de información de clientes, indisponibilidad de la aplicación, errores en cálculos de facturación).  
- Identificar **mínimo 2 riesgos de gestión** (ej.: dependencia de una persona clave, ausencia de procesos de QA).  
- Evaluar probabilidad e impacto aplicando **ISO 27005** y **NIST RMF (Risk Assessment)**.  
- Elaborar un mapa de riesgos con niveles (Bajo / Medio / Alto / Crítico).  

---

### 2. Matriz RACI
Construir una matriz RACI con los siguientes roles:  
- **Jefe de Desarrollo**  
- **Programadores**  
- **Administrador de Base de Datos**  
- **Gerente de TI**  
- **Auditor de Seguridad**  

Actividades mínimas a considerar:  
- Revisión y aprobación de código.  
- Gestión de ambientes (dev, test, prod).  
- Pruebas de calidad y seguridad.  
- Implementación de parches y hotfixes.  
- Comunicación de incidentes a gerencia y clientes.  

---

### 3. Checklist de Control
Elaborar un checklist de auditoría basado en **ISO/IEC 27002:2022** y **ISO/IEC 27001:2022**:

---

### 4. Cuestionario de Auditoría
Preparar un cuestionario de 5–7 preguntas para entrevistar a:  
- Jefe de Desarrollo  
- Programadores  
- Administrador de BD  

---

### 5. Presentación Final
El grupo deberá preparar una **presentación de 5 minutos** que incluya:  
1. Resumen del caso y principales hallazgos.  
2. Mapa de riesgos (ISO 27005 + NIST RMF).  
3. Matriz RACI propuesta.  
4. Checklist y cuestionario de auditoría.  
5. Recomendaciones y plan de mejora (alineado a estándares internacionales).  

---

## Recursos de Referencia
- **NIST RMF**: https://csrc.nist.gov/projects/risk-management  
- **ISO/IEC 27005:2022** – Gestión de riesgos de seguridad de la información  
- **ISO/IEC 27002:2022** – Controles de seguridad de la información  
- **ISO/IEC 27001:2022** – SGSI y requisitos de certificación   

---

