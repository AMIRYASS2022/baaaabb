# Mezquita Alhuda - Sitio Web Oficial

## 🕌 Descripción

Sitio web oficial de la Mezquita Alhuda ubicada en Playa Blanca, Lanzarote, Islas Canarias. Una aplicación web moderna y responsive que proporciona información esencial para la comunidad musulmana local.

## ✨ Características

### 🕐 Horarios de Oración
- **Horarios diarios** con zona horaria de Islas Canarias (Atlantic/Canary)
- **Calendario mensual** que se actualiza automáticamente
- **Próxima oración** con cuenta regresiva en tiempo real
- Coordenadas precisas para Playa Blanca, Lanzarote

### 🌍 Multiidioma
- **Español** (idioma principal)
- **Inglés** para turistas y residentes internacionales
- **Árabe** con soporte RTL completo
- Cambio de idioma dinámico

### 📱 Diseño Responsive
- Optimizado para móviles, tablets y escritorio
- Navegación móvil con menú hamburguesa
- Diseño adaptativo para todas las pantallas

### 🎥 Transmisión en Vivo
- Stream en vivo de la Jutba del viernes
- Horarios de transmisión claramente indicados
- Enlace directo al canal de YouTube

### 💰 Donaciones
- Sistema de donaciones integrado
- Múltiples métodos de pago
- Información transparente sobre el uso de fondos

## 🚀 Instalación

### Prerrequisitos
- Node.js (versión 16 o superior)
- npm o yarn

### Pasos de Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/mezquita-alhuda.git
cd mezquita-alhuda
```

2. **Instalar dependencias**
```bash
npm install
```

3. **Ejecutar en modo desarrollo**
```bash
npm start
```

4. **Abrir en el navegador**
```
http://localhost:3000
```

## 🛠️ Scripts Disponibles

- `npm start` - Ejecuta la aplicación en modo desarrollo
- `npm run build` - Construye la aplicación para producción
- `npm run dev` - Ejecuta con Vite (alternativo)
- `npm test` - Ejecuta las pruebas

## 📁 Estructura del Proyecto

```
mezquita-alhuda/
├── src/
│   ├── locales/          # Archivos de traducción
│   │   ├── es.json       # Español
│   │   ├── en.json       # Inglés
│   │   └── ar.json       # Árabe
│   ├── App.jsx           # Componente principal
│   ├── App.css           # Estilos principales
│   ├── i18n.js           # Configuración de internacionalización
│   └── main.jsx          # Punto de entrada
├── public/               # Archivos públicos
├── package.json          # Dependencias del proyecto
└── README.md             # Este archivo
```

## 🔧 Configuración

### Zona Horaria
La aplicación está configurada para usar la zona horaria `Atlantic/Canary` con las coordenadas exactas de Playa Blanca:
- **Latitud**: 28.8627
- **Longitud**: -13.8372

### API de Horarios de Oración
Utiliza la API de Aladhan para obtener horarios precisos:
- Método de cálculo: 3 (Muslim World League)
- Actualización automática mensual

## 🌐 Despliegue

### Vercel (Recomendado)
1. Conecta tu repositorio de GitHub con Vercel
2. Configura las variables de entorno si es necesario
3. Despliega automáticamente

### Netlify
1. Conecta tu repositorio
2. Comando de build: `npm run build`
3. Directorio de publicación: `dist`

### GitHub Pages
1. Instala gh-pages: `npm install --save-dev gh-pages`
2. Agrega script en package.json: `"deploy": "gh-pages -d dist"`
3. Ejecuta: `npm run build && npm run deploy`

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 📞 Contacto

**Mezquita Alhuda**
- 📍 Dirección: Playa Blanca, Lanzarote 35580, Islas Canarias
- 📧 Email: info@mezquitaalhuda.org
- 📱 Teléfono: +34 928 XXX XXX

## 🙏 Agradecimientos

- [Aladhan API](https://aladhan.com/) por proporcionar horarios de oración precisos
- [React](https://reactjs.org/) por el framework
- [i18next](https://www.i18next.com/) por la internacionalización
- La comunidad musulmana de Lanzarote por su apoyo

---

**جزاك الله خيراً** - Que Allah te recompense con el bien

*Desarrollado con ❤️ para la comunidad musulmana de Lanzarote*