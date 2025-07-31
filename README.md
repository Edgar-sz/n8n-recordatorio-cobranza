# n8n-recordatorio-cobranza
📌 Flujo de Recordatorio de Cobranza Automatizado (n8n)

Este flujo automatiza el envío diario de recordatorios de cobranza por correo electrónico y WhatsApp, utilizando como base una hoja de Google Sheets con datos de clientes, montos y fechas de vencimiento. Evalúa cada factura según su estado (vencida, por vencer, vigente), genera mensajes personalizados (manuales o con IA), y registra si fueron enviados correctamente. También gestiona errores como correos mal escritos o números inválidos, e informa automáticamente al responsable si ocurre algún fallo. Se han incluido pausas entre mensajes para evitar bloqueos por parte de WhatsApp y ajustes de zona horaria para sincronizar con la ubicación del servidor.

RECURSO: https://www.youtube.com/watch?v=SgXXUHRamCQ&t=771s
