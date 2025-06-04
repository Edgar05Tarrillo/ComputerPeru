# Informe Técnico - Sitio Web Computer Perú
**Fecha de entrega:** 05/05/2024 11:59 PM

## Carátula
- **Proyecto:** Sitio Web Estático Computer Perú
- **Curso:** Desarrollo Web
- **Institución:** Universidad Tecnológica del Perú
- **Docente:** [Nombre del Docente]
- **Estudiante:** [Nombre del Estudiante]

## Presentación
El presente informe técnico documenta el desarrollo de un sitio web estático para la empresa Computer Perú, especializada en la venta de productos tecnológicos. El proyecto se ha desarrollado siguiendo estrictamente los requerimientos establecidos, utilizando exclusivamente HTML sin estilos CSS ni JavaScript, con el objetivo de crear una estructura semántica sólida y accesible.

## Desarrollo

### 1. Estructura del Proyecto
```
ComputerPeru/
├── index.html
├── informe_tecnico.md
├── README.md
└── imagenes/
    ├── imagen1.jpg
    ├── imagen2.webp
    ├── imagen3.webp
    ├── imagen4.webp
    ├── imagen5.webp
    ├── imagen6.jfif
    ├── imagen7.jpg
    ├── imagen8.webp
    ├── imagen9.jfif
    ├── sillagamer1.png
    ├── sillagamer2.png
    └── logo.png
```

### 2. Análisis de Requerimientos
- Sitio web estático sin estilos CSS
- Entrega mediante enlace
- Plazo de entrega: 29/05 - 05/05 11:59 PM
- Sin extensiones de plazo
- Documentación técnica completa

### 3. Implementación Técnica

#### 3.1 Estructura HTML
El sitio web se desarrolló utilizando HTML5, aprovechando elementos semánticos para mejorar la accesibilidad y SEO:

- `<!DOCTYPE html>`: Declaración del tipo de documento HTML5
- `<html lang="es">`: Especificación del idioma español
- `<head>`: Metadatos y título del sitio
- `<body>`: Contenido principal
- `<main>`: Contenedor principal
- `<header>`: Encabezado con navegación
- `<section>`: Secciones principales del contenido
- `<footer>`: Pie de página con información de contacto

#### 3.2 Componentes Principales

##### Navegación
```html
<nav>
    <table align="center">
        <tr align="center">
            <td><a href="#inicio">Inicio</a></td>
            <td><a href="#productos">Productos</a></td>
            <td><a href="#nosotros">Nosotros</a></td>
            <td><a href="#contacto">Contacto</a></td>
        </tr>
    </table>
</nav>
```

##### Catálogo de Productos
- Smartphones
- Laptops Gaming
- Accesorios Gaming
- Smartwatches
- Sillas Gamer

Cada producto incluye:
- Imagen del producto
- Nombre
- Precio original y con descuento
- Opciones de pago
- Botón de "Añadir al carrito"

##### Formulario de Contacto
```html
<form action="#" method="post">
    <input type="text" id="nombre" name="nombre" required>
    <input type="email" id="email" name="email" required>
    <input type="tel" id="telefono" name="telefono">
    <input type="text" id="asunto" name="asunto" required>
    <textarea id="mensaje" name="mensaje" required></textarea>
</form>
```

### 4. Consideraciones Técnicas

#### 4.1 Accesibilidad
- Uso de atributos `alt` en imágenes
- Estructura jerárquica de encabezados (h1-h4)
- Formularios con etiquetas `<label>` asociadas
- Navegación mediante anclas

#### 4.2 Optimización
- Imágenes en formatos optimizados (webp, jpg, png)
- Estructura de código limpia y organizada
- URLs semánticas para enlaces internos
- Meta tags para SEO básico

#### 4.3 Compatibilidad
- Markup HTML5 estándar
- Sin dependencias externas
- Compatible con todos los navegadores modernos

### 5. Desafíos y Soluciones
1. **Desafío**: Crear un diseño atractivo sin CSS
   **Solución**: Uso estratégico de tablas HTML y atributos de alineación

2. **Desafío**: Organización de productos
   **Solución**: Estructura tabular anidada para mantener consistencia

3. **Desafío**: Navegación responsiva
   **Solución**: Enlaces de ancla y estructura de navegación simple

## Conclusiones

1. **Objetivos Cumplidos**
   - Desarrollo exitoso del sitio web estático
   - Implementación de todas las secciones requeridas
   - Documentación técnica completa
   - Cumplimiento de plazos establecidos

2. **Aspectos Técnicos**
   - La estructura HTML demuestra ser robusta y semántica
   - El sitio es completamente funcional sin necesidad de estilos
   - La accesibilidad se mantiene en un nivel óptimo

3. **Recomendaciones Futuras**
   - Implementación de CSS para mejorar la experiencia visual
   - Adición de JavaScript para funcionalidades interactivas
   - Integración con backend para procesar formularios
   - Implementación de sistema de carrito de compras funcional

4. **Lecciones Aprendidas**
   - Importancia de la estructura HTML semántica
   - Valor de la simplicidad en el diseño web
   - Relevancia de la accesibilidad web
   - Eficacia de la documentación técnica detallada 