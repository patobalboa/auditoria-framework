# Informe War Room - Grupo 5
### Área: Cloud Computing (AWS)

---

## Contexto del Caso
La empresa ha migrado parte de sus aplicaciones a **Amazon Web Services (AWS)**.  
En la última factura mensual se detecta un gasto **10 veces mayor al presupuesto estimado**.  
Al revisar la infraestructura, se descubren las siguientes situaciones:

- Una instancia **EC2 está siendo utilizada para minado de criptomonedas** sin autorización.  
- Varias cuentas de usuario de AWS IAM tienen permisos de **administrador global** sin aplicar el principio de mínimo privilegio.  
- No existen alarmas de costos ni alertas de uso configuradas en la consola de AWS.  
- No se cuenta con un **plan de recuperación ante desastres (DRP)** documentado en la nube.  
- Las claves de acceso a S3 están expuestas en repositorios de código (GitHub interno).  

### Situación crítica:
El Director Financiero y el Gerente de TI exigen respuestas inmediatas, ya que la brecha podría implicar **pérdida económica, compromiso de datos sensibles y exposición a sanciones legales**.  

---

## Tareas a Realizar (Trabajo de Auditoría)

### 1. Análisis de Riesgos
- Identificar **mínimo 3 riesgos operativos** (ej.: uso no autorizado de instancias, fuga de datos de S3, indisponibilidad por falta de DRP).  
- Identificar **mínimo 2 riesgos de gestión** (ej.: sobrecostos por mala gobernanza, incumplimiento regulatorio en servicios cloud).  
- Evaluar probabilidad e impacto según **ISO 27005** y **NIST RMF (Risk Assessment)**.  
- Elaborar un **mapa de riesgos cloud** con niveles (Bajo / Medio / Alto / Crítico).  

---

### 2. Matriz RACI
Definir roles para la gestión de seguridad en cloud:  
- **Administrador Cloud (AWS SysAdmin)**  
- **Gerente de TI**  
- **Equipo de Seguridad Informática**  
- **Proveedor AWS (Soporte Enterprise)**  
- **Auditor Externo**  

Actividades mínimas a cubrir:  
- Gestión de identidades y accesos (IAM).  
- Monitoreo de uso y costos (CloudWatch / Budgets).  
- Configuración de seguridad en servicios (S3, EC2, RDS).  
- Respuesta ante incidentes en la nube.  
- Planificación de continuidad y recuperación.  

---

### 3. Checklist de Control
Diseñar un checklist basado en **ISO/IEC 27017 (controles cloud)**, **ISO 27002** y **ISO 27001**. Ejemplos:  


---

### 4. Cuestionario de Auditoría
Elaborar 5–7 preguntas para entrevistar a:  
- Administrador Cloud  
- Gerente de TI  
- Equipo de Seguridad  



---

### 5. Presentación Final
El grupo debe preparar una **presentación de 5 minutos** que incluya:  
1. Resumen del incidente cloud.  
2. Riesgos identificados y clasificados (operativos y de gestión).  
3. Matriz RACI.  
4. Checklist y cuestionario.  
5. Recomendaciones alineadas a estándares (ISO 27001, ISO 27017, NIST RMF, CIS Controls).  

---

## Recursos de Referencia
- **NIST RMF**: https://csrc.nist.gov/projects/risk-management  
- **ISO/IEC 27005:2022** – Gestión de riesgos de seguridad de la información  
- **ISO/IEC 27001:2022** – SGSI
- **ISO/IEC 27002:2022** – Controles de seguridad de la información

---

