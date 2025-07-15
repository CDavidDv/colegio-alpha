# 🏫 Colegio Alpha - Sitio Web Institucional

Sitio web moderno y interactivo para el Colegio Alpha de Pachuca, desarrollado con **Astro** y **Tailwind CSS**. El sitio presenta una experiencia visual atractiva con animaciones dinámicas y efectos interactivos.

## ✨ Características Principales

### 🎨 **Diseño Moderno**
- **Responsive Design**: Adaptable a todos los dispositivos
- **Animaciones CSS**: Efectos suaves y profesionales
- **Colores Institucionales**: Paleta basada en la identidad visual del colegio
- **Tipografía Optimizada**: Legibilidad y jerarquía visual clara

### 🎭 **Componentes Interactivos**

#### **Figuras Geométricas Animadas**
- **Física Realista**: Movimiento, rotación y colisiones entre figuras
- **Interacción con Mouse**: Las figuras se alejan del cursor
- **Límites Inteligentes**: Respetan el contenido y no interfieren con el footer
- **Colores Dinámicos**: Paleta basada en los colores institucionales

#### **Carrusel de Colaboradores**
- **Animación Infinita**: Movimiento continuo y suave
- **Pausa en Hover**: Se detiene al pasar el mouse
- **Logos Institucionales**: Colaboradores y aliados del colegio

#### **Sección STEAM**
- **Letras Coloreadas**: Cada letra de "STEAM" con su color específico
- **Cards Modernas**: Diseño con gradientes y efectos hover
- **Iconos Atractivos**: Representación visual de cada área STEAM

### 📱 **Secciones Principales**

- **Hero Section**: Presentación impactante del colegio
- **Filosofía**: Valores y principios educativos
- **Oferta Educativa**: Kinder, Primaria y Secundaria
- **Metodología STEAM**: Enfoque educativo innovador
- **Colaboradores**: Aliados institucionales
- **Testimonios**: Experiencias de la comunidad
- **Contacto**: Información de ubicación y comunicación

## 🛠️ Tecnologías Utilizadas

### **Frontend**
- **Astro**: Framework moderno para sitios web estáticos
- **Tailwind CSS**: Framework de utilidades CSS
- **TypeScript**: Tipado estático para mejor desarrollo
- **CSS Animations**: Efectos visuales avanzados

### **Características Técnicas**
- **SSR (Server-Side Rendering)**: Rendimiento optimizado
- **Componentes Reutilizables**: Arquitectura modular
- **SEO Optimizado**: Meta tags y estructura semántica
- **Accesibilidad**: Cumple estándares WCAG

## 🚀 Instalación y Desarrollo

### **Prerrequisitos**
- Node.js (versión 16 o superior)
- npm o yarn

### **Instalación**

1. **Clonar el repositorio**
```bash
git clone [URL_DEL_REPOSITORIO]
cd instituto-alpha
```

2. **Instalar dependencias**
```bash
npm install
```

3. **Ejecutar en modo desarrollo**
```bash
npm run dev
```

4. **Abrir en el navegador**
```
http://localhost:4321
```

### **Comandos Disponibles**

```bash
# Desarrollo
npm run dev          # Servidor de desarrollo
npm run build        # Construir para producción
npm run preview      # Vista previa de producción

# Linting y formateo
npm run lint         # Verificar código
npm run format       # Formatear código
```

## 📁 Estructura del Proyecto

```
instituto-alpha/
├── public/                 # Archivos estáticos
│   ├── favicon.svg
│   ├── Hero.jpg
│   └── logos/
├── src/
│   ├── components/         # Componentes Astro
│   │   ├── Hero.astro
│   │   ├── Filosofia.astro
│   │   ├── Steam.astro
│   │   ├── Colaboradores.astro
│   │   └── ...
│   ├── layouts/           # Layouts de página
│   │   └── Layout.astro
│   ├── pages/             # Páginas del sitio
│   │   └── index.astro
│   └── styles/            # Estilos globales
│       └── global.css
├── astro.config.mjs       # Configuración de Astro
├── package.json
└── README.md
```

## 🎯 Componentes Destacados

### **Layout.astro**
- **Figuras Geométricas**: Sistema de física con colisiones
- **Interacción Mouse**: Repulsión de figuras al cursor
- **Límites Inteligentes**: Respeto por el contenido
- **Optimización de Rendimiento**: 20 FPS para movimiento suave

### **Steam.astro**
- **Letras Dinámicas**: Colores individuales para "STEAM"
- **Cards Modernas**: Gradientes y efectos hover
- **Grid Responsive**: Adaptable a diferentes pantallas

### **Colaboradores.astro**
- **Carrusel Infinito**: Animación CSS pura
- **Pausa Interactiva**: Detiene al hacer hover
- **Z-index Optimizado**: Sin conflictos con elementos de fondo

## 🎨 Paleta de Colores

```css
/* Colores Institucionales */
--verde-logo: #67BC29
--azul-logo: #01A8B7
--verde-steam: #97BE12
--amarillo-steam: #E4E41A
--naranja-steam: #FF7300
--azul-claro-steam: #01A8B7
```

## 📱 Responsive Design

El sitio está optimizado para:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🚀 Despliegue

### **Netlify (Recomendado)**
1. Conectar repositorio a Netlify
2. Configurar build command: `npm run build`
3. Configurar publish directory: `dist`

### **Vercel**
1. Importar proyecto desde GitHub
2. Framework preset: Astro
3. Deploy automático

## 🤝 Contribución

1. Fork el proyecto
2. Crear rama feature (`git checkout -b feature/AmazingFeature`)
3. Commit cambios (`git commit -m 'Add AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abrir Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver `LICENSE` para más detalles.

## 📞 Contacto

**Colegio Alpha** - Pachuca, Hidalgo
- **Email**: [email@colegioalpha.com]
- **Teléfono**: [número de contacto]
- **Dirección**: [dirección del colegio]

---

Desarrollado con ❤️ para el Colegio Alpha
