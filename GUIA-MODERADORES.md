# 📋 Guía para moderadores — Un café por la democracia

¡Parceros! Acá les explico cómo funciona la herramienta del conversatorio. Es súper sencilla, no se asusten.

---

## 🔑 Entrar

1. Abran la página: **https://lfresco.github.io/cafe-democracia/**
2. La contraseña se las comparto por WhatsApp. Es la misma para todos.
3. Después de entrar, van a ver el **panel de admin** donde se configura todo.

---

## ✏️ Preparar el debate (antes del evento)

### Temas
- Cada tema tiene: **título**, **contexto** (info clave para ustedes), **preguntas guía** y **datos/cifras**.
- Pueden agregar, editar o eliminar temas cuando quieran durante la semana.
- Los cambios se guardan solos (esperan 2 segundos y se sube a la nube).
- Si quieren guardar inmediato, le dan al botón **Guardar**.

### Panelistas
- Pongan un nombre por línea en la caja de "Panelistas".

### Reglas
- Una regla por línea. Estas se pueden mostrar al público si las necesitan.

### Timer
- El número de segundos es lo que dura el timer por defecto (180 = 3 minutos).

### Preguntas random 🎲
- Esta es una lista aparte de los temas. Son preguntas "comodín" para cuando el debate se ponga aburrido o se necesite un cambio de tema.
- Una pregunta por línea.
- En vivo, cuando le dan al botón **🎲 Random**, sale una pregunta al azar **sin repetir**. Cuando se acaban todas, se reinician.

### Diseño
- Pueden subir una imagen de fondo (ej: el diseño que hicieron en Canva).
- O cambiar los colores del gradiente con los selectores.
- El slider de "Oscurecer imagen" le pone una capa negra encima para que el texto se lea bien.

---

## 🔴 En vivo (el día del evento)

1. Cuando esté todo listo, le dan al botón **▶ Iniciar LIVE**.
2. La pantalla cambia al **modo proyección**: timer grande + tema + QR para preguntas.
3. Los botones de control aparecen al pasar el mouse por encima.

### Controles en vivo
| Acción | Botón | Tecla |
|--------|-------|-------|
| Play/Pausa timer | Iniciar/Pausa | `Espacio` |
| Reset timer | Reset | — |
| Tema anterior | ← | `Flecha izquierda` |
| Tema siguiente | → | `Flecha derecha` |
| Pregunta random | 🎲 Random | `R` |
| Salir de live | ✕ Salir | `Escape` |

### Preguntas del público
- El QR lleva a una página donde la gente manda preguntas anónimas desde el celular.
- Las preguntas aparecen al lado derecho en tiempo real.
- Solo se muestran las que llegaron **después** de que se activó el LIVE (las viejas no salen).
- Si necesitan ocultar alguna, vayan a Supabase → tabla `questions` → pongan `visible = false`.

---

## 💡 Tips

- **Prueben todo el día anterior**: entren, pongan live, prueben el QR con el celular.
- **El timer no para solo**: si se acabó el tiempo, queda en 00:00 parpadeando. Ustedes deciden cuándo resetear.
- **Pueden editar temas DURANTE el evento**: si necesitan ajustar algo, salen del live (Escape), editan, y vuelven a entrar.
- **Varios moderadores a la vez**: todos pueden entrar con la misma contraseña desde diferentes dispositivos. Los cambios se sincronizan.

---

## 🆘 Si algo falla

- Recarguen la página (F5).
- Si no carga datos, puede ser un problema de internet.
- Si el QR no funciona, compartan el link directo: `https://lfresco.github.io/cafe-democracia/preguntas.html`

---

¡Eso es todo! Cualquier duda me escriben. Éxitos con el conversatorio 🇨🇴☕
