# 🤖 Clasificador Inteligente de Leads – n8n

## 📋 Descripción del proyecto

Este workflow automatiza la captura, clasificación y gestión de leads desde un formulario web.</br>
</br>Integra IA, notificaciones por Slack, correos por Gmail y almacenamiento en Google Sheets.

## 👀 Vista del proyecto

![Clasificador Inteligente de Leads](https://github.com/romyluna/N8N-clasificador-inteligente-leads/blob/master/Screenshots/N8N%20PROYECTO.PNG?raw=true)

## 🗂️ google sheets ejemplo de como registra:
![Registro en Google Sheets](https://github.com/romyluna/N8N-clasificador-inteligente-leads/blob/master/Screenshots/sheetmuestra.png)


## 🛠 Tecnologías
- **n8n** para automatización de workflows
- **Docker** para levantar n8n fácilmente
- **Gmail API** para enviar emails automáticos
- **Slack API** para notificaciones
- **Google Sheets** para almacenar la información de los leads
- **LangChain + Google Gemini (PaLM)** para IA de clasificación y análisis de sentimientos

## 📝 Flujo principal

1. 📝 Captura del lead: nombre, email y mensaje del cliente.
2. 🧹 Normalización de datos: limpieza y estandarización.
3. ❌ Exclusión de emails no deseados, por ejemplo `@platzi.com`.
4. 🤖 Clasificación del mensaje con IA: info, demo, compra o soporte.
5. 🚦 Ruteo según intención:
   - 💼 Demo → notificación a ventas por Slack
   - 📧 Info → envío de información al cliente por Gmail
   - 🛒 Compra → notificación a ventas + email de bienvenida
   - 🆘 Soporte → análisis de sentimiento y notificación al equipo de soporte
6. 🗂️ Registro en Google Sheets de toda la información del lead
7. ⏰ Seguimiento automatizado: recordatorios en Slack para el equipo de ventas

## 🎯 Beneficios
- ⚡ Automatización total del flujo de leads
- 🧠 Clasificación rápida y precisa con IA
- 🔔 Integración con Slack, Gmail y Google Sheets
- 📈 Mejor seguimiento de clientes y eficiencia de ventas

---

### 👩‍💻 Contacto
<a name="contacto"></a>

👩‍💻 Romina Olivera Luna
</br>
💌 rominalunaolivera@gmail.com
</br>
🔗 [LinkedIn
](https://www.linkedin.com/in/romina-bluna/)

[⬆️ Volver arriba](#readme)
