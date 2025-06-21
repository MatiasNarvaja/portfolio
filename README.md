# Mi Portafolio Personal

## 📋 Descripción del Proyecto

Este es un portafolio personal desarrollado con **Angular** que demuestra habilidades en desarrollo web frontend, utilizando elementos semánticos de HTML5 y estilos CSS modernos. El portafolio utiliza placeholders con emojis y gradientes en lugar de imágenes para un diseño limpio y moderno.

## ✨ Características Implementadas

### 🎯 Elementos Semánticos HTML5
- **`<main>`**: Contenedor principal de la aplicación
- **`<header>`**: Encabezado con navegación
- **`<nav>`**: Menú de navegación principal
- **`<section>`**: Secciones organizadas del portafolio
- **`<article>`**: Tarjetas de proyectos y contenido principal
- **`<footer>`**: Pie de página con información de contacto

### 🎨 CSS Externo Completo
- **Variables CSS**: Sistema de colores y espaciado consistente
- **Fuente personalizada**: Poppins (Google Fonts) + fuentes web-safe
- **Paleta de colores**: Azul, púrpura y naranja con gradientes
- **Diseño responsive**: Adaptable a diferentes tamaños de pantalla
- **Animaciones**: Efectos hover y transiciones suaves
- **Placeholders**: Diseños con emojis y gradientes en lugar de imágenes

### 📱 Elementos en Bloque y Línea
- **Elementos en bloque**: `.portfolio-main`, `.container`, `.project-card`
- **Elementos en línea**: `.nav-link`, `.tech-tag`, `.social-link`

### 🎯 Uso de IDs y Clases
- **IDs**: `#inicio`, `#sobre-mi`, `#proyectos`, `#habilidades`, `#contacto`
- **Clases**: Sistema de clases semánticas y reutilizables

### 📐 Dimensiones y Espaciado
- **Height y Width**: Placeholders con dimensiones específicas (300x300px para perfil)
- **Espaciado consistente**: Sistema de variables CSS para márgenes y padding

### 🎨 Personalización de Elementos
- **Botones**: Estilos personalizados con hover effects
- **Formularios**: Inputs y textareas con focus states
- **Barras de progreso**: Para mostrar habilidades técnicas
- **Tarjetas**: Sombras y efectos de elevación
- **Placeholders**: Gradientes y emojis para representar contenido visual

## 🚀 Secciones del Portafolio

### 1. **Header/Navegación**
- Logo del portafolio
- Menú de navegación con enlaces internos
- Diseño sticky para mejor UX

### 2. **Sección Hero**
- Título principal y descripción
- Placeholder de perfil con emoji de desarrollador
- Botón call-to-action

### 3. **Sobre Mí**
- Información personal y profesional
- Estadísticas destacadas (experiencia, proyectos, clientes)

### 4. **Proyectos**
- Grid de tarjetas de proyectos
- Placeholders con emojis representativos (🛒, 📋, 📊)
- Descripciones y tecnologías utilizadas
- Enlaces a demo y código

### 5. **Habilidades Técnicas**
- Categorías Frontend y Backend
- Barras de progreso animadas
- Porcentajes de dominio

### 6. **Contacto**
- Información de contacto
- Formulario funcional
- Iconos descriptivos

### 7. **Footer**
- Copyright y enlaces sociales
- Diseño minimalista

## 🛠️ Tecnologías Utilizadas

- **Angular 17**: Framework principal
- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos y responsive
- **TypeScript**: Tipado estático
- **Google Fonts**: Fuente Poppins
- **Emojis**: Para representación visual sin imágenes

## 📁 Estructura del Proyecto

```
portfolio/
├── src/
│   ├── app/
│   │   ├── app.component.html    # Estructura HTML semántica
│   │   ├── app.component.css     # Estilos CSS externos
│   │   └── app.component.ts      # Lógica del componente
│   ├── assets/                   # Recursos estáticos
│   ├── styles.css               # Estilos globales
│   └── index.html               # Página principal
└── README.md                    # Documentación
```

## 🎯 Comentarios del Código

El código incluye comentarios explicativos que documentan:

1. **Estructura de secciones**: Organización del HTML semántico
2. **Sistema de variables CSS**: Explicación de colores y espaciado
3. **Elementos en bloque vs línea**: Diferenciación clara
4. **Mejoras futuras**: TODO items para funcionalidades adicionales

## 🚀 Cómo Ejecutar

1. **Instalar dependencias**:
   ```bash
   npm install
   ```

2. **Ejecutar en modo desarrollo**:
   ```bash
   npm start
   ```

3. **Abrir en navegador**:
   ```
   http://localhost:4200
   ```

## 📱 Responsive Design

El portafolio es completamente responsive con breakpoints para:
- **Desktop**: > 768px
- **Tablet**: 768px - 480px
- **Mobile**: < 480px

## 🎨 Paleta de Colores

- **Primario**: #2563eb (Azul)
- **Secundario**: #7c3aed (Púrpura)
- **Acento**: #f59e0b (Naranja)
- **Texto oscuro**: #1f2937
- **Texto claro**: #6b7280
- **Fondo claro**: #f8fafc
- **Fondo oscuro**: #1e293b

## 🎨 Placeholders y Diseño Visual

En lugar de imágenes, el portafolio utiliza:
- **Placeholder de perfil**: Círculo con emoji de desarrollador (👨‍💻)
- **Placeholders de proyectos**: Rectángulos con emojis representativos
  - 🛒 para E-commerce
  - 📋 para Task Management
  - 📊 para Analytics Dashboard
- **Gradientes**: Fondos con colores de la paleta personalizada
- **Efectos hover**: Animaciones y cambios de color

## 🔮 Mejoras Futuras

- [ ] Modo oscuro/claro con toggle
- [ ] Animaciones más complejas con CSS animations
- [ ] Filtros para proyectos por tecnología
- [ ] Integración con backend para formulario de contacto
- [ ] Blog integrado
- [ ] Portfolio de testimonios
- [ ] Opción para agregar imágenes reales

## 📄 Licencia

Este proyecto es de uso educativo y personal.

---

**Desarrollado con ❤️ usando Angular y CSS moderno**
