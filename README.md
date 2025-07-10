# Energías Limpias en Colombia 🌱

Una página web moderna e interactiva sobre las energías limpias en Colombia, desarrollada con HTML, CSS, JavaScript y Python (Flask).

![Energías Limpias Colombia](https://img.shields.io/badge/Energía-Limpia-green)
![Flask](https://img.shields.io/badge/Flask-2.3.3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![CSS3](https://img.shields.io/badge/CSS3-Modern-blue)

## 🎯 Características

### 📊 Visualización de Datos
- **Gráficos interactivos** con Chart.js mostrando la matriz energética colombiana
- **Estadísticas en tiempo real** sobre hidroeléctrica, solar, eólica y térmica
- **Animaciones suaves** y transiciones modernas

### 🏗️ Proyectos Destacados
- Información detallada sobre proyectos de energía renovable
- Estado actual de construcción y operación
- Ubicaciones geográficas y capacidades instaladas

### 🗺️ Análisis Regional
- Potencial energético por regiones de Colombia
- Número de proyectos activos por zona
- Destacados climáticos y geográficos

### 📱 Diseño Responsivo
- **Mobile-first design** optimizado para todos los dispositivos
- **Navegación intuitiva** con menú hamburguesa en móviles
- **Animaciones de scroll** y efectos visuales modernos

### 🚀 Tecnologías Backend
- **Flask API** con endpoints RESTful
- **Datos estructurados** sobre energías renovables
- **CORS habilitado** para desarrollo

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5** - Estructura semántica moderna
- **CSS3** - Variables CSS, Grid, Flexbox, animaciones
- **JavaScript ES6+** - Async/await, modules, DOM manipulation
- **Chart.js** - Gráficos interactivos
- **Font Awesome** - Iconografía moderna
- **Google Fonts** - Tipografía Poppins

### Backend
- **Python 3.8+** - Lenguaje de programación
- **Flask 2.3.3** - Framework web minimalista
- **JSON** - Formato de datos para API

### Librerías y Frameworks
- **Chart.js** - Visualización de datos
- **Intersection Observer API** - Animaciones de scroll
- **Fetch API** - Comunicación con backend

## 📦 Instalación y Configuración

### Prerrequisitos
- Python 3.8 o superior
- pip (gestor de paquetes de Python)
- Navegador web moderno

### 1. Clonar o descargar el proyecto
```bash
git clone <repository-url>
cd energia-limpia-colombia
```

### 2. Crear entorno virtual (recomendado)
```bash
python -m venv venv

# En Windows
venv\Scripts\activate

# En macOS/Linux
source venv/bin/activate
```

### 3. Instalar dependencias
```bash
pip install -r requirements.txt
```

### 4. Ejecutar la aplicación
```bash
python app.py
```

### 5. Abrir en el navegador
Visita: `http://localhost:5000`

## 🌐 Estructura del Proyecto

```
energia-limpia-colombia/
│
├── app.py                 # Aplicación Flask principal
├── requirements.txt       # Dependencias de Python
├── README.md             # Documentación del proyecto
│
├── templates/
│   └── index.html        # Plantilla HTML principal
│
├── static/
│   ├── css/
│   │   └── style.css     # Estilos CSS principales
│   ├── js/
│   │   └── script.js     # JavaScript principal
│   └── images/           # Imágenes (vacío por ahora)
│
└── venv/                 # Entorno virtual (no incluido en git)
```

## 🔌 API Endpoints

### GET `/`
- **Descripción**: Página principal de la aplicación
- **Retorna**: Template HTML renderizado

### GET `/api/statistics`
- **Descripción**: Estadísticas de la matriz energética
- **Retorna**: JSON con datos de hidroeléctrica, térmica, solar y eólica

### GET `/api/projects`
- **Descripción**: Lista de proyectos de energías limpias
- **Retorna**: JSON con proyectos destacados

### GET `/api/regions`
- **Descripción**: Información sobre regiones colombianas
- **Retorna**: JSON con potencial energético por región

### GET `/api/all-data`
- **Descripción**: Todos los datos combinados
- **Retorna**: JSON con estadísticas, proyectos y regiones

## 📊 Datos Incluidos

### Matriz Energética
- **Hidroeléctrica**: 68% (17,500 MW)
- **Térmica**: 29% (7,400 MW)
- **Solar**: 1.5% (400 MW)
- **Eólica**: 1.5% (380 MW)

### Proyectos Destacados
- Parque Eólico Guajira I (La Guajira)
- Granja Solar El Paso (Cesar)
- Central Hidroeléctrica Ituango (Antioquia)
- Parque Solar Bayunca (Bolívar)

### Regiones Analizadas
- Costa Caribe
- Región Andina
- Región Pacífica
- Orinoquia

## 🎨 Características de Diseño

### Paleta de Colores
- **Primario**: Verde (`#10b981`) - Energía renovable
- **Secundario**: Amarillo (`#f59e0b`) - Energía solar
- **Azul**: (`#2563eb`) - Energía hidroeléctrica
- **Rojo**: (`#dc2626`) - Energía térmica

### Tipografía
- **Fuente principal**: Poppins (Google Fonts)
- **Pesos**: 300, 400, 500, 600, 700

### Animaciones
- Flotación para elementos de energía
- Rotación para turbinas eólicas
- Fade-in en scroll
- Hover effects suaves

## 🔧 Funcionalidades JavaScript

### Gestión de Estado
- Carga de datos desde API Flask
- Fallback a datos estáticos si falla la API
- Manejo de errores robusto

### Interactividad
- Navegación suave entre secciones
- Menú hamburguesa responsivo
- Formulario de contacto con validación
- Notificaciones toast

### Visualización
- Gráfico de dona interactivo
- Tarjetas de proyectos dinámicas
- Tarjetas de regiones generadas automáticamente
- Animaciones de entrada en scroll

## 🚀 Características Avanzadas

### Performance
- Lazy loading de contenido
- Optimización de imágenes
- Minificación de CSS (en producción)
- Caching de datos API

### Accesibilidad
- Semántica HTML apropiada
- Contraste de colores WCAG
- Navegación por teclado
- Screen reader friendly

### SEO
- Meta tags optimizados
- Estructura de headings correcta
- URLs amigables
- Schema markup (futuro)

## 🔮 Futuras Mejoras

### Funcionalidades
- [ ] Mapa interactivo de proyectos
- [ ] Sistema de usuarios y autenticación
- [ ] Dashboard administrativo
- [ ] Blog de noticias sobre energía
- [ ] Calculadora de huella de carbono

### Técnicas
- [ ] Progressive Web App (PWA)
- [ ] Server-Side Rendering (SSR)
- [ ] Base de datos real (PostgreSQL/MongoDB)
- [ ] API REST más robusta
- [ ] Tests automatizados

### UI/UX
- [ ] Modo oscuro
- [ ] Internacionalización (i18n)
- [ ] Más animaciones y micro-interacciones
- [ ] Diseño aún más moderno

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

Desarrollado como proyecto de demostración de tecnologías web modernas aplicadas al sector de energías renovables en Colombia.

## 📞 Contacto

- Email: info@ecoenergia.co
- Teléfono: +57 1 234 5678
- Ubicación: Bogotá, Colombia

---

⚡ **¡Impulsando el futuro sostenible de Colombia!** 🇨🇴