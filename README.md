# Portafolio 2.0 - Daniel Hincapié

**Docente:** Juliana Gómez Osorio  
**Asignatura:** Desarrollo Web / Frontend  
**Entrega:** Tercer Corte Evaluativo  
**Estudiante:** Daniel Hincapié  
**Repositorio:** [https://github.com/Damahibe/portafolio-2.0-programa-web](https://github.com/Damahibe/portafolio-2.0-programa-web)  

---

## 📌 Modernización del Portafolio con Bulma CSS

Este proyecto corresponde a la modernización del portafolio personal desarrollado en el primer corte con HTML y CSS, integrando el framework de estilos **Bulma CSS** según las instrucciones vistas en clase:

### Requisitos Implementados:

1. **Código base conservado:** Se mantuvo la estructura original del HTML y los contenidos del primer corte (disponibles también en la carpeta `/version-original-corte1` como respaldo).
2. **Framework de estilos:** Se integró **Bulma CSS** mediante enlace en el `<head>`, aprovechando sus componentes y clases estándar.
3. **Componentes modernizados:**
   * **Proyectos:** Mostrados en tarjetas limpias (`card`, `card-content`) con sombras, títulos y etiquetas de tecnologías.
   * **Habilidades / Stack:** Presentadas mediante etiquetas visuales con colores (`tags`, `tag is-info`, `tag is-warning`, `tag is-success`, etc.).
   * **Sección Hero:** Maquetada con `hero is-medium` y rejilla de columnas (`columns`, `column`), organizando el título, la presentación, los botones de acción y la imagen.
   * **Botones y Formulario:** Botones estilizados con `button is-primary` y `button is-light`. Formulario de contacto organizado con `field`, `label`, `control`, `input` y `textarea`.
   * **Tipografía y colores:** Paleta armónica basada en tonos oscuros con acentos cian/naranja y tipografía clara y legible.
4. **Código organizado y funcional:** Estructura limpia y sin dependencias complejas, listo para abrir directamente en cualquier navegador.

---

## 📂 Estructura del Proyecto

```text
Portfolio/
├── index.html                  # Portafolio modernizado con clases de Bulma
├── styles.css                  # Estilos complementarios y colores personalizados
├── script.js                   # Script sencillo para el menú móvil de Bulma
├── css/
│   └── bulma.min.css           # Archivo local de Bulma CSS
├── assets/
│   └── hero-visual.svg.png     # Imagen original del portafolio
└── version-original-corte1/    # Respaldo intacto de la entrega del primer corte
    ├── index.html
    └── styles.css
```

---

## 🚀 Cómo Visualizarlo

Simplemente abre el archivo `index.html` en tu navegador:

```bash
open index.html
```
