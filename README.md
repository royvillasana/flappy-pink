# 🎮 Flappy Pink - Barbie Edition

Un juego web estilo Flappy Bird con temática de Barbie, completamente responsivo y optimizado para dispositivos móviles.

## 🌟 Características

### 📱 **Totalmente Responsivo**
- ✅ Optimizado para móviles y tablets
- ✅ Controles táctiles naturales 
- ✅ Escala perfectamente en cualquier pantalla
- ✅ Interfaz adaptable automáticamente

### 🎯 **Mecánicas de Juego**
- ❤️ **Sistema de vida**: 5 corazones, pierdes 0.5 por colisión
- 🏆 **Victoria**: Alcanza 50 puntos pasando tubos
- ⭐ **Bonificaciones**: Recolecta estrellas para puntos extra
- 🎵 **Audio**: Sonidos diferenciados para acciones
- 🌈 **Efectos visuales**: Partículas y animaciones

### 🎨 **Estilo Barbie**
- 💖 Paleta de colores rosa completa
- 🏰 Fondo animado del castillo de ensueño
- ✨ Efectos de brillos y partículas
- 🎀 Interfaz amigable y adorable

## 🎮 Cómo Jugar

### Controles:
- **Móvil**: Toca la pantalla para volar
- **Desktop**: Espacio, flecha arriba, o clic

### Objetivo:
1. 🚀 Vuela entre los tubos rosas
2. ⭐ Recolecta estrellas para puntos bonus  
3. ❤️ Cuida tus 5 corazones de vida
4. 🏆 ¡Llega a 50 puntos para ganar!

## 🚀 Instalación y Uso

```bash
# Clona el repositorio
git clone https://github.com/TU_USUARIO/flappy-pink-barbie.git

# Abre el juego
open index.html
# O arrastra index.html a tu navegador
```

## 📁 Estructura del Proyecto

```
flappy-pink-barbie/
├── index.html          # Juego completo (HTML + CSS + JS)
├── assets/             # Recursos multimedia
│   ├── background.png  # Fondo del castillo
│   ├── hero.png       # Personaje principal
│   ├── heart.png      # Corazones de vida
│   ├── star.png       # Estrellas recolectables
│   ├── sparkle.png    # Efectos de partículas
│   ├── logo.png       # Logo del juego
│   ├── favicon.png    # Icono del navegador
│   ├── star.wav       # Sonido de estrella
│   └── victory.wav    # Sonido de victoria
├── README.md          # Este archivo
├── CLAUDE.md          # Guía para Claude Code
└── .gitignore         # Archivos a ignorar en Git
```

## 🎨 Personalización

### Colores:
Modifica las variables CSS en `:root`:
```css
:root {
  --rose: #e60073;
  --pink1: #ffb6e9;
  --pink2: #ffc1f3;
  /* ... más colores */
}
```

### Dificultad:
Ajusta parámetros en el JavaScript:
- `gap`: Espacio entre tubos
- Velocidad de movimiento
- Gravedad del héroe
- Fuerza del salto

## 🌐 Hosting

### GitHub Pages:
1. Sube el proyecto a GitHub
2. Ve a Settings > Pages
3. Selecciona "Deploy from branch: main"
4. ¡Listo! Tu juego estará en: `https://tu-usuario.github.io/flappy-pink-barbie`

### Netlify/Vercel:
- Conecta tu repositorio de GitHub
- Deploy automático en cada cambio

## 🛠️ Tecnologías

- **HTML5 Canvas** - Renderizado del juego
- **CSS3** - Responsive design y animaciones
- **Vanilla JavaScript** - Lógica del juego
- **Web Audio API** - Efectos de sonido
- **Touch Events** - Controles móviles

## 📱 Compatibilidad

- ✅ Chrome/Safari/Firefox/Edge (móvil y desktop)
- ✅ iOS Safari
- ✅ Android Chrome
- ✅ Pantallas desde 320px hasta 4K

## 🤝 Contribuir

¡Las contribuciones son bienvenidas!

1. Fork el proyecto
2. Crea una branch (`git checkout -b feature/nueva-caracteristica`)
3. Commit tus cambios (`git commit -m 'Agrega nueva característica'`)
4. Push a la branch (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto es de código abierto. Siéntete libre de usar, modificar y distribuir.

---

💖 **¡Disfruta jugando Flappy Pink!** ✨
