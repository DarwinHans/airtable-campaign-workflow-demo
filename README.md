# 📊 Airtable Campaign Workflow Demo

Este proyecto es una demostración de un flujo de trabajo completo para equipos de marketing que gestionan campañas de contenido. Fue diseñado como parte de un proceso de postulación para el cargo de **Creative Operations Specialist** en Storm Ideas, y tiene como objetivo mostrar la capacidad de estructurar información, automatizar tareas y ofrecer interfaces visuales fáciles de usar con herramientas no-code.
<img width="1438" height="284" alt="Captura de Pantalla 2025-07-23 a la(s) 10 16 45" src="https://github.com/user-attachments/assets/48ccf8e7-7ed3-432c-8cde-402f15e1cd4f" />

---

## 📌 Descripción

Esta base de Airtable permite a equipos de marketing:

- Crear y monitorear campañas activas.
- Planificar y registrar contenido para distintas plataformas (Instagram, TikTok, YouTube, etc).
- Asignar tareas a miembros del equipo con fechas límite y estados.
- Visualizar todo el flujo mediante una **interfaz tipo dashboard**.
- Preparar la automatización de notificaciones y seguimiento.

---

## 🛠️ Tecnologías y servicios utilizados

- [Airtable](https://airtable.com/) – Base de datos no-code y diseño de interfaces
- Automatizaciones internas de Airtable
- 📄 Archivos CSV estructurados (adjuntos)
- GitHub para documentación y versionado del proyecto

---

## 📁 Estructura del proyecto

### 1. `Campanas.csv`
Contiene la información principal de las campañas (fechas, objetivos, responsables, estado).

### 2. `Contenido.csv`
Registra las publicaciones específicas por plataforma y tipo, asociadas a cada campaña.

### 3. `Tareas.csv`
Define las tareas del equipo vinculadas a cada pieza de contenido.

---

## 🧠 Lógica del flujo

- Las tablas están **relacionadas** entre sí (Campañas → Contenido → Tareas).
- Cada publicación está ligada a una campaña y tiene una fecha de publicación estimada.
- Las tareas se asignan a miembros y se relacionan con una pieza de contenido específica.
- La interfaz permite **visualizar por estado**, responsables y tipo de plataforma.
- El diseño está pensado para facilitar la colaboración y la trazabilidad de proyectos.

---

## 🔗 Demo en vivo

👉 [Ver demo Airtable (solo lectura)](https://airtable.com/apppVdIVMjcbjnBzJ/shrkvCL4dmCkqM8Fn)

Puedes duplicar la base y personalizarla para tus propios flujos de trabajo.

---

## 🚀 Posibles mejoras futuras

- Automatizaciones por estado (ej: enviar email cuando un contenido se publica)
- Integración con calendarios o Slack mediante Webhooks
- Formularios para que los equipos soliciten campañas nuevas
- Reportes automáticos de progreso

---

## 👨‍💻 Autor

**Darwin Nahuelpán**  
Ingeniero Civil Industrial 
🌍 [LinkedIn](https://www.linkedin.com/in/darwin-nahuelpan-habert-00a86aa8/) | 📫 darwinhans10@gmail.com

---
