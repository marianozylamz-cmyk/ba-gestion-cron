# ba-gestion-cron

Programa los avisos de BÁ Gestión: cada 15 minutos llama al endpoint de avisos de la app.

No contiene código de la app ni datos. La dirección (`AVISOS_URL`) y la clave (`CRON_SECRET`) están guardadas como secretos del repo.
Si la clave cambia en Vercel, actualizarla en *Settings → Secrets and variables → Actions*.
