# 🍇 Landing page · Barrio Privado Cepas de Junín

Landing page de un solo archivo para el **Barrio Privado Cepas de Junín** (Junín, Mendoza), un desarrollo inmobiliario con casas, dúplex y lotes. Está pensada para presentar el proyecto con un estilo elegante y llevar al visitante a una **consulta directa por WhatsApp**.

🔗 **Sitio en vivo:** (https://mutualmebna0.github.io/landingCepas/)

<img width="1351" height="659" alt="image" src="https://github.com/user-attachments/assets/da5b9a10-3b83-49ee-bf93-5cff37fd1249" />


## 🎯 Objetivo

Generar consultas de compradores e inversores. La página transmite el entorno (viñedos, naturaleza, privacidad), muestra los tipos de vivienda y el plano del barrio, indica la ubicación y ofrece un único llamado a la acción claro: escribir por WhatsApp.



## ✨ Características

- **Hero a pantalla completa** con imagen de viñedos y superposición en tonos lila.
- **Barra de navegación adaptable:** transparente sobre el hero y con fondo claro al hacer scroll.
- **Secciones:** Inicio, El Proyecto, Residencias (casas y dúplex), Masterplan, Ubicación y Contacto.
- **Animaciones de aparición al hacer scroll**, con `IntersectionObserver`, que se ejecutan una sola vez.
- **Mapa de Google Maps** embebido con carga diferida (`loading="lazy"`).
- **Botón de WhatsApp** con mensaje prellenado y efecto de pulso al pasar el cursor.
- **Diseño responsive** con las utilidades de Tailwind.

## 🎨 Diseño

| Elemento | Detalle |
|----------|---------|
| **Paleta** | Beige `#F4EFE6`, beige claro `#FBF9F6`, lila `#75619A` y berenjena `#3B3050` |
| **Tipografías** | *Playfair Display* (títulos) y *Montserrat* (texto) |
| **Estilo** | Minimalista y elegante, con mucho espacio en blanco y detalles en líneas finas |

## 🛠️ Tecnologías

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) con configuración personalizada de colores y fuentes
- JavaScript (vanilla)
- Google Fonts y Google Maps Embed

## 📁 Estructura

```
├── index.html        # (cepaslanding.html) página completa: estructura, estilos y scripts
└── imagenes/         # logo, hero, fotos de casas y dúplex, plano 3D
```

## 🚀 Cómo verla

No requiere instalación ni compilación. Alcanza con abrir el archivo en el navegador:

```bash
git clone https://github.com/[tu-usuario]/[nombre-del-repo].git
cd [nombre-del-repo]
# Abrí index.html en tu navegador
```

También se puede publicar gratis con **GitHub Pages**: *Settings → Pages → Deploy from a branch → main / root*.

## ⚙️ Personalización

- **Número de WhatsApp y mensaje:** en el enlace `wa.me` de la sección *Contacto*.
- **Colores y fuentes:** en el bloque `tailwind.config` del `<head>`.
- **Imágenes:** en la carpeta `imagenes/`; las rutas están en las etiquetas `<img>`.
- **Mapa:** reemplazá el `src` del `<iframe>` por el enlace de *Compartir → Insertar un mapa* de Google Maps.

## Aclaración
- Etiquetas SEO utilizadas, mas no presentadas en el .html presentado, por seguridad.

## 🔮 Próximas mejoras

- Menú desplegable para celulares.
- Compilar Tailwind (en lugar de usar el CDN) para producción.
- Galería de fotos y formulario de contacto como alternativa al WhatsApp.


## 👩‍💻 Autora

**Ludmila Micaela Reyes Martínez**
Estudiante de Ingeniería en Sistemas de Información (UTN FRM)
 📧 [ludmilareyes208@gmail.com]
