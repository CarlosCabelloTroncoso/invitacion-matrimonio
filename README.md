# 💍 Invitación Digital de Matrimonio · Sofía & Mateo

Maqueta interactiva, limpia y profesional para invitación web de matrimonio / boda. Desarrollada en HTML5, CSS3 moderno y JavaScript vanilla, optimizada para dispositivos móviles (responsive first) y lista para compartir por WhatsApp o redes sociales.

---

## ✨ Características Principales

- **Portada Elegante:** Monograma floral con iniciales, tipografías refinadas (*Cormorant Garamond*, *Great Vibes*, *Montserrat*) y diseño limpio con paleta crema, oro champagne y sage.
- **Cuenta Regresiva en Vivo (Countdown):** Temporizador animado con cálculo dinámico en tiempo real (días, horas, minutos y segundos).
- **Detalles del Evento:** Tarjetas con fecha, hora y ubicación para la Ceremonia y la Fiesta, con accesos directos a Google Maps y botón interactivo para agendar en Google Calendar.
- **Cronograma / Itinerario:** Línea de tiempo visual del gran día (Ceremonia, Cóctel, Cena, Apertura de pista, etc.).
- **Código de Vestimenta (Dress Code):** Muestra de paleta sugerida de colores y recomendaciones de etiqueta.
- **Mesa de Regalos & Transferencia Bancaria:** Datos de transferencia con botón interactivo de **"Copiar Datos"** y feedback visual instantáneo (Toast notification).
- **Confirmación de Asistencia (RSVP):** Formulario dinámico (asistencia, número de personas, restricciones alimentarias, sugerencia de canción y dedicatoria) que genera un mensaje pre-formateado y abre WhatsApp automáticamente.
- **Música de Fondo Integrada:** Botón flotante para activar música ambiental romántica generada con la Web Audio API (funciona inmediatamente sin necesidad de alojar archivos de audio pesados externos).

---

## 🚀 Despliegue en GitHub Pages

Para publicar este demo de manera gratuita y que tu cliente pueda abrirlo desde cualquier teléfono o computador:

1. Ve a la pestaña **Settings** de este repositorio en GitHub.
2. Entra a **Pages** (en el menú lateral izquierdo).
3. En **Branch**, selecciona `main` y la carpeta `/ (root)`.
4. Haz clic en **Save**. En un par de minutos estará disponible públicamente en la URL de GitHub Pages.

---

## 🛠️ Personalización

Para adaptar los datos a un cliente específico, simplemente edita [`index.html`](index.html):
- **Nombres y fecha:** Cambia el texto en el encabezado y ajusta la variable `targetDate` en el script (`"2026-11-14T17:00:00"`).
- **Lugares y mapas:** Actualiza los enlaces de Google Maps y las direcciones.
- **Teléfono de WhatsApp:** En la función de RSVP, reemplaza `const phone = "56912345678";` por el número de WhatsApp de los novios o del organizador.
- **Datos bancarios:** Modifica los valores dentro de `textToCopy` y en el bloque HTML `#bankInfo`.
