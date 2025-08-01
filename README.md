# 📌 n8n-recordatorio-cobranza  
## Flujo de Recordatorio de Cobranza Automatizado (n8n)

Este flujo automatiza el envío diario de recordatorios de cobranza por **correo electrónico** y **WhatsApp**, utilizando como base una **hoja de Google Sheets** con datos de clientes, montos y fechas de vencimiento.  

Evalúa cada factura según su estado (**vencida**, **por vencer**, **vigente**), genera mensajes personalizados (manuales o con IA), y registra si fueron enviados correctamente.  

También gestiona errores como **correos mal escritos** o **números inválidos**, e informa automáticamente al responsable si ocurre algún fallo.  

Se han incluido **pausas entre mensajes** para evitar bloqueos por parte de WhatsApp y **ajustes de zona horaria** para sincronizar con la ubicación del servidor.

---

## 🔐 Credenciales necesarias

Para que este flujo funcione correctamente, deberás configurar las siguientes credenciales dentro de **n8n**:

- **Google Sheets**: Para acceder a la base de datos de clientes.  
- **Gmail (OAuth2 o SMTP)**: Para el envío de correos electrónicos automáticos.  
- **Evolution API**: Para ejecutar mensajes por WhatsApp mediante endpoints personalizados.  
- **OpenAI (opcional)**: Si deseas generar mensajes automatizados con inteligencia artificial.  

Asegúrate de que cada una esté correctamente autorizada y activa en tu entorno de producción o pruebas.

---

## 📎 Recurso

- [🎥 YouTube - Flujo de Recordatorio de Cobranza](https://www.youtube.com/watch?v=SgXXUHRamCQ&t=771s)

