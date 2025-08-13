# 🌐 TalentSphere 
## Talent Management Platform

![Estado](https://img.shields.io/badge/🚀_En_Desarrollo-yellow) 
![Licencia](https://img.shields.io/badge/Licencia-🔒_Privada-red)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

## 📋 Descripción del Sistema
Es una solución tecnológica integral diseñada para optimizar la **gestión del ciclo de selección** y administración de candidatos en las áreas de Recursos Humanos.  
Facilita la **carga de hojas de vida**, la **extracción automática de datos**, la **asignación de cargos**, el seguimiento de evaluaciones y la trazabilidad de procesos de selección.

Entre sus funcionalidades principales se incluyen:
- Autenticación por roles: acceso diferenciado para Director RRHH, Analista, Psicólogo Organizacional, Especialista en Capacitación, Compensaciones, Bienestar, Asistente de RRHH y Superusuario.
- Carga inteligente de hojas de vida (PDF/DOCX/Imagen) con extracción automática de datos al formulario.
- Gestión completa de candidatos: alta, modificación, historial y seguimiento.
- Asignación de cargo con comparación de perfil vs requisitos.
- Checklist de validación configurable, con adjuntos y observaciones.
- Reportes y estadísticas del pipeline de selección.
- Interfaz web responsive para acceso desde PC o móvil.
- Almacenamiento seguro en base de datos con respaldo programado y buenas prácticas de seguridad.

Esta solución está diseñada para **reducir tiempos de selección**, **mejorar la precisión de los procesos** y **facilitar decisiones de contratación**.

## 🛠 Stack Tecnológico
**Backend Avanzado:**
- Python FastAPI con arquitectura RESTful
- PostgreSQL para producción (SQLite en desarrollo)
- JWT para autenticación segura
- SQLAlchemy + Alembic para ORM y migraciones

**Frontend:**
- React + Vite para SPA moderna
- TailwindCSS para estilos
- Chart.js para visualización de datos

## 🖥️ Infraestructura

**Entorno de Producción:**
- Servidor optimizado para cargas empresariales
- Backup automático diario
- Monitorización 24/7
- Despliegue seguro con validación

**Próximas Implementaciones Planeadas:**
- Integración con ATS externos
- OCR avanzado para documentos escaneados
- Motor de recomendación de candidatos por IA

**Gestión de Versiones:**
- Control con Git
- Estrategia Git Flow
- Deployment validado

## 🖥️ Estructura del Proyecto
📁 talentsphere  
├── 📂 backend/ # API y lógica de negocio  
│ ├── auth.py # Autenticación y roles  
│ ├── candidates.py # Gestión de candidatos  
│ ├── positions.py # Gestión de cargos  
│ └── checklist.py # Validación y seguimiento  
├── 📂 models/ # Entidades y ORM  
│ └── user.py # Usuarios y roles  
├── 📂 frontend/ # Interfaz de usuario  
│ ├── pages/ # Pantallas y formularios  
│ └── components/ # Componentes reutilizables  
└── 📂 migrations/ # Control de versiones DB    

## 🔍 Características Clave
Sistema especializado para procesos de selección y gestión de talento:
- Carga y parsing automático de hojas de vida
- Comparación de perfiles vs cargos
- Checklist de validación con trazabilidad
- Reportes y métricas en tiempo real
- Seguridad multirol y auditoría

## 🛡️ Derechos de Autor
© 2025 WoMo Soluciónˢ. Todos los derechos reservados.

**Condiciones de uso:**
- Estrictamente confidencial
- Prohibida la reproducción no autorizada
- Licencia por instalación

## 📬 Contacto Corporativo
**Julián Alberto Ramírez**  
💻 Socio Fundador & Visionario Tecnológico
⚙️ Automatización | 🧩 Soluciones software |💡 Innovador Tecnológico | 🔍 Apasionado por IA  
<img width="222" height="29" alt="Image" src="https://github.com/user-attachments/assets/24519130-f605-4762-a4f2-374c450f2b64" />  
🏢 **Soluciones Tecnológicas Avanzadas**  
<img width="150" height="150" alt="Image" src="https://github.com/user-attachments/assets/09c23a95-e483-452e-880f-e7c90c222014" />  


💡 **Notas Técnicas:**  
Este sistema demuestra capacidades avanzadas en:  
✅ Procesamiento inteligente de CV  
✅ Integración con flujos de selección  
✅ Seguridad y trazabilidad de datos  
✅ Visualización profesional de métricas  

"Del CV a la decisión, sin fricción"

📅 **Control de Versiones**  
![Versión](https://img.shields.io/badge/Versión-1.0.0-blue) ![Última Actualización](https://img.shields.io/badge/Actualizado-Ago_2025-green)
