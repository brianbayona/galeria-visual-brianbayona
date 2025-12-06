# galeria-visual-brianbayona
Este proyecto es una galería web estática desarrollada como parte de la Actividad de Transferencia del Conocimiento del curso **Diseño Web – SENA**.  
El objetivo fue aplicar propiedades visuales en CSS para organizar y presentar recursos gráficos de manera estética, accesible y responsiva.

---

## ✨ Características principales

Presentación visual organizada de imágenes  
Uso de gradientes y fondos decorativos  
Aplicación de transparencias para mejorar legibilidad  
Paleta de colores coherente en todo el proyecto  
Interacciones visuales al pasar el cursor (hover)  
Código HTML y CSS debidamente comentado  

---

## 🚀 Cómo visualizar el proyecto

### 🔹 En local
1. Descargar o clonar el repositorio
2. Abrir el archivo `index.html` en cualquier navegador moderno

### 🔹 En GitHub Pages
🔗 URL del proyecto publicado:  
👉 *(Aquí colocarás tu enlace)*

---

## 🎨 Decisiones de diseño

**Paleta de colores**  
La paleta fue elegida con inspiración temática del contenido de las imágenes, destacando tonos **oscuros y vibrantes** para generar contraste y mantener una apariencia moderna.  
Se definió directamente en CSS como variables, facilitando mantenimiento y consistencia visual.

**Gradientes aplicados**  
Se utilizaron gradientes en:
- Encabezado: para resaltar el título y dar sensación de profundidad
- Sección de banner/intro: como elemento atractivo que divide visualmente la página

Su propósito es guiar la atención del usuario hacia el contenido principal.

**Imágenes como background**  
Una sección utiliza imágenes de fondo con:
- `background-size: cover;`
- `background-position: center;`
- `background-repeat: no-repeat;`

Esto mejora el diseño sin afectar la claridad del contenido.

**Transparencias (rgba)**  
Se aplicaron en elementos de texto sobre imágenes para asegurar legibilidad, evitando que los fondos saturados entorpezcan la lectura.

---

## 🧪 Control de calidad

- Pruebas visuales en navegador de escritorio
- Revisión de contraste para accesibilidad
- Verificación de rutas correctas en todas las imágenes

---

## 👨‍💻 Autor

Aprendiz: Brian Mauricio Bayona Ravelo  
Curso: Técnico en programación de Software  
Instructor: *John Freddy Becerra Castellanos*

HTML

<!-- Sección principal donde se muestran todas las imágenes de la galería -->
<section class="galeria">

CSS

/* Gradiente para dar profundidad visual al encabezado */
header {
    background: linear-gradient(...);
}
