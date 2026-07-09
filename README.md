# 🏳️‍🌈 Círculo de Hombres — Gestión de Temas

Sistema web dinámico para la gestión participativa de temas semanales del **Círculo de Hombres**. Los usuarios proponen, votan y deciden los temas de las próximas sesiones, todo sincronizado en tiempo real.

## ✨ Funcionalidades

- **Votación en vivo** — Los temas propuestos se muestran con su conteo de votos actualizado en tiempo real
- **Proponer temas** — Cualquier persona puede sugerir un tema para la comunidad
- **Agenda confirmada** — Las próximas 4 sesiones semanales con fecha y tema asignado
- **Panel de administración** — El coordinador puede aprobar propuestas, editar la agenda y limpiar duplicados
- **Voto único por sesión** — Cada navegador puede votar una sola vez por tema
- **Diseño arcoíris elegante** — Responsivo, mobile-first, con la paleta LGBT+ como identidad visual

## 🛠️ Stack técnico

| Herramienta | Propósito |
|-------------|-----------|
| HTML + CSS + JS | Frontend vanilla, sin frameworks |
| Firebase Realtime Database | Sincronización en tiempo real |
| GitHub Pages | Hosting estático gratuito |
| LocalStorage | Control de voto único por sesión |

## 🔗 URLs

| Vista | URL |
|-------|-----|
| **Página pública** | `https://jesusherll.github.io/Temas-de-circulo-de-hombres/` |
| **Panel admin** | `https://jesusherll.github.io/Temas-de-circulo-de-hombres/admin-control.html` |

## 🔐 Acceso administrador

- **Contraseña:** `Circulo2026`
- El panel admin no tiene enlace público — se accede directamente por la URL
- La contraseña está en el código del lado del cliente (JS); para entornos productivos se recomienda agregar autenticación real

## 📁 Estructura del proyecto

```
├── index.html              # Vista pública (agenda, votación, proponer)
├── admin-control.html      # Panel de administración protegido
├── firebase-config.js      # Configuración de Firebase
├── circulo de hombres diversos.jpeg  # Logo del círculo
└── README.md               # Este archivo
```

## 🧑‍💻 Desarrollo local

Abrí los archivos HTML directamente en tu navegador — Firebase se encarga de la sincronización. No necesitas servidor local.

## 📝 Notas

- Los datos de ejemplo iniciales son: *Desahogo*, *Sexualidad* y *Orgullo*
- Las fechas de agenda se calculan automáticamente como los próximos 4 viernes
- El coordinador puede editar fechas y temas desde el panel de administración

---

Hecho con ❤️ para el Círculo de Hombres
