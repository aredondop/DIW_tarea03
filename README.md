# Tarea 03 para DIW - Desarrollo de Sitio Web con Multimedia

## Descripción
Esta tarea consiste en desarrollar un sitio web que contenga imágenes, vídeo y audio con licencia para su uso, y optimizado para su reproducción en la web.

### Objetivo:
Diseñar una página web para un restaurante basada en el siguiente wireframe:

> **Wireframe**: Aparece un logo en la cabecera (forma de muslo de pollo), una imagen en la sección principal arriba a la derecha, un vídeo en el centro y un audio al final de la sección. 

La página muestra una receta de pollo al chilindrón con:
1. Una **imagen** del plato ya cocinado.
2. Un **vídeo** que muestra la elaboración.
3. Un **audio** que narra la receta.

---

## Requisitos

### 1. **Sección Multimedia**
- Logo en la cabecera con forma de muslo de pollo.
- Imagen del plato cocinado en la sección principal.
- Vídeo mostrando la elaboración de la receta.
- Audio que narra los ingredientes y pasos de la receta.

### 2. **Optimización de Archivos**
- Imágenes: Peso no superior a **100 KB**.
- Vídeo: Peso no superior a **10 MB**.
- Audio: Peso no superior a **5 MB**.

### 3. **Receta del Pollo al Chilindrón**
#### **Ingredientes**
- 1 pollo entero troceado.
- 1 pimiento rojo.
- 1 pimiento verde grande.
- 4 dientes de ajo.
- 1 cebolla grande.
- 50 g de jamón serrano.
- 150 ml de vino blanco.
- 400 g de tomate picado.
- Aceite de oliva virgen extra.
- Pimienta negra.
- Sal.

#### **Elaboración**
1. Calienta el aceite en una sartén grande.
2. Añade el pollo troceado y sofríelo hasta que esté dorado.
3. Cocina los pimientos y la cebolla en el mismo aceite.
4. Agrega los tomates y deja que se cocinen hasta formar una salsa.
5. Añade el pollo y cocina todo junto unos minutos más.
6. Sirve caliente.

### 4. **Extras**
- Añadir una **animación GIF** culinaria en la sección principal.
- Estilo adicional para un diseño atractivo.
- Pie de página con nombre completo y DNI.

---

## Herramientas Utilizadas
- **Bootstrap**: Para la estructura y estilo.
- **CSS Personalizado**: Archivo `estilo.css` para añadir estilos propios.
- **Editor de Imágenes**: Para optimizar las imágenes y capturar su tamaño.
- **Herramientas de Audio y Vídeo**: Para grabar, editar y comprimir los archivos multimedia.

---

## Requisitos Técnicos
1. La página debe ser **responsive** y adaptarse a diferentes tamaños de pantalla.
2. Los elementos multimedia deben ser accesibles en la mayoría de navegadores.
3. Incluye una descripción en el código HTML de los elementos multimedia utilizados (atribución de licencias si corresponde).

---

## Estructura del Proyecto
```plaintext
.
├── /css
│   └── estilo.css       # Estilos personalizados
├── /img
│   ├── logo.png         # Logo del restaurante
│   ├── pollo_chilindron.jpg  # Imagen del plato
│   └── robin-food.gif   # Animación GIF culinaria
├── /media
│   ├── pollo_al_chilindron.mp4  # Vídeo de la receta
│   ├── pollo_al_chilindron.mp3  # Audio de la receta
│   └── pollo_al_chilindron.ogg  # Alternativa de audio
├── index.html           # Página principal
└── README.md            # Documentación del proyecto

