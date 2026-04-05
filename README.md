# 🎉 Invitación a los 15 de Mora

Una página web elegante e interactiva para la invitación a los 15 años de Mora.

## 📋 Características

- 📱 Diseño totalmente responsivo (mobile, tablet, desktop)
- 🎵 Playlist integrada de Spotify
- ⏱️ Contador interactivo en tiempo real (Días, Horas, Minutos, Segundos)
- ✨ Efectos visuales con destellos de brillo
- 🌐 Scroll suave entre secciones
- 📸 Foto de Mora destacada
- 🗺️ Integración con Google Maps
- 💬 Confirmación directa por WhatsApp

## 🚀 Inicio Rápido

### 1. Instalar Node.js (si no lo tienes)
Descarga Node.js desde: https://nodejs.org/

### 2. Instalar dependencias
```bash
cd c:\Users\carob\OneDrive\Escritorio\Proyectos\invitacion-mora
npm install
```

### 3. Ejecutar el servidor
```bash
npm start
```

### 4. Abrir en el navegador
```
http://localhost:3000
```

## 📁 Estructura de Carpetas

```
invitacion-mora/
├── public/
│   ├── index.html          # HTML principal
│   ├── styles.css          # Estilos
│   ├── script.js           # JavaScript
│   ├── mora-photo.jpg      # Foto de Mora
│   └── favicon.ico         # (opcional)
├── package.json            # Dependencias
├── server.js               # Servidor Express
├── .gitignore              # Archivos ignorados
└── README.md               # Este archivo
```

## ⚙️ Configuración

### Cambiar puerto
En `server.js`, modifica:
```javascript
const PORT = process.env.PORT || 5000;  // Cambiar de 3000 a 5000
```

### Fecha del evento
En `public/script.js`, actualiza:
```javascript
const eventDate = new Date('2026-05-23T21:30:00').getTime();
```

### Información del evento
En `public/index.html`, actualiza los detalles.

## 🌐 Despliegue

### Opción 1: Vercel (Gratis)
```bash
npm install -g vercel
vercel
```

### Opción 2: Heroku
```bash
npm install -g heroku-cli
heroku login
heroku create tu-app-name
git push heroku main
```

### Opción 3: Netlify
Sube la carpeta `public/` directamente a Netlify (modo estático)

## 🎨 Personalización

### Colores
En `public/styles.css`, modifica las variables CSS:
```css
:root {
  --bg-main: #E8CFC3;    /* Fondo beige */
  --gold: #D4AF37;       /* Oro */
  --text-dark: #341E14;  /* Texto oscuro */
  --white: #FFFFFF;      /* Blanco */
}
```

### Fuentes
Se usan fuentes de Google Fonts, edibible en `public/index.html`:
- Cormorant Garamond (serif)
- Cinzel Decorative (display)
- Dancing Script (cursiva)

## 📱 Responsividad

La página está optimizada para:
- 📱 Móviles (480px y menores)
- 📱 Tablets (768px - 1024px)
- 💻 Desktops (1024px y mayores)

## 🔗 Enlaces Útiles

- **Playlist Spotify**: https://open.spotify.com/playlist/23H2zC2Snq8hGKEWyxKGzJ
- **Ubicación Google Maps**: https://maps.app.goo.gl/ThZLt4gzLWMYykS49
- **WhatsApp API**: https://wa.me/

## 📝 Notas

- La foto debe estar en `public/mora-photo.jpg`
- Se recomienda optimizar la imagen a menos de 500KB
- El alias de pago es: `mora.baiud.13`
- Fecha del evento: **23 de mayo de 2026 a las 21:30**

## ❓ Problemas Comunes

**La foto no carga:**
- Verifica que `mora-photo.jpg` esté en la carpeta `public/`
- Recarga la página con Ctrl+Shift+R

**El contador no actualiza:**
- Asegúrate de que JavaScript esté habilitado
- Verifica la consola del navegador (F12)

**El puerto 3000 está en uso:**
- Cambia el puerto en `server.js`
- O ejecuta: `lsof -i :3000` para ver qué lo usa

## 📞 Contacto & Soporte

Para más información o cambios, contacta al desarrollador.

---

**¡Que disfrutes de los 15 de Mora! 🎊**
