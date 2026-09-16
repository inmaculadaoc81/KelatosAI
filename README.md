# KelatosAi — web para Vercel

Marca y logotipo propuestos; comprueba disponibilidad comercial y de dominio antes de utilizarlos.

## Despliegue
Importa este proyecto en Vercel (raíz del proyecto: carpeta que contiene index.html). Framework preset: Other.

## Variables de entorno
SMTP_HOST, SMTP_PORT, SMTP_SECURE, SMTP_USER, SMTP_PASS y CONTACT_EMAIL (por ejemplo soporte@kelatos.com). Configura sus valores en Vercel; nunca guardes contraseñas en el repositorio.

## Referencias reutilizadas
El formulario POST /api/contacto, los enlaces de WhatsApp, teléfono, Cal.com, política de privacidad, YouTube y el webhook de n8n provienen de la plantilla aportada. No se ha reutilizado su diseño.

## Antes de publicar
Confirma nombre y dominio, que el webhook de n8n está autorizado para esta nueva web y que el destino SMTP es el deseado. No se ha añadido Google Analytics porque no se proporcionó ID. La barra de cookies guarda la preferencia, pero no instala analítica. Verifica políticas de privacidad y condiciones comerciales.
