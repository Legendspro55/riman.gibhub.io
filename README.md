{
  "title": "Landing Page de RIMAN - Belleza Coreana Exclusiva",
  "description": "Este proyecto es una landing page interactiva y de una sola página, diseñada para promocionar y vender productos de belleza de la marca RIMAN. El diseño se inspira en una estética coreana moderna y exclusiva, enfocada en el cuidado de la piel.",
  "features": [
    "**Diseño Responsivo:** La página se adapta a diferentes tamaños de pantalla, desde computadoras de escritorio hasta dispositivos móviles.",
    "**Estética Sofisticada:** Utiliza una paleta de colores neutros, tipografía elegante y un diseño minimalista para transmitir una sensación de lujo y exclusividad.",
    "**Interactividad Ligera:** Incluye animaciones sutiles con CSS para mejorar la experiencia del usuario, como efectos de desvanecimiento, desplazamiento y un carrusel de testimonios.",
    "**Llamada a la Acción (CTA) Clara:** Múltiples botones de acción invitan al usuario a explorar los productos o a contactar a la asesora de ventas, Hana Choi.",
    "**Sección de Testimonios:** Un carrusel animado de testimonios agrega prueba social y confianza en la marca."
  ],
  "project_structure": {
    "root": "/tu_proyecto/",
    "files": [
      {
        "name": "index.html",
        "description": "Página principal y única"
      },
      {
        "name": "styles.css",
        "description": "Hojas de estilo CSS para el diseño"
      }
    ],
    "directories": [
      {
        "name": "/assets/",
        "description": "Carpeta que contiene todos los recursos multimedia.",
        "subdirectories": [
          {
            "name": "/images/",
            "description": "Almacena las imágenes de los productos, logos de certificaciones y cualquier otro gráfico.",
            "files": [
              "producto1.jpg",
              "producto2.jpg",
              "producto3.jpg",
              "cert.png",
              "cruelty_free.png"
            ]
          },
          {
            "name": "/videos/",
            "description": "Almacena el video de fondo de la cabecera.",
            "files": [
              "fondo.mp4"
            ]
          }
        ]
      }
    ]
  },
  "content_files": {
    "index.html": "Contiene la estructura HTML de toda la landing page.",
    "styles.css": "Contiene todos los estilos de CSS para dar vida al diseño, incluyendo animaciones y la lógica de responsividad."
  },
  "usage_instructions": {
    "title": "Instrucciones de Uso",
    "steps": [
      "Asegúrate de tener todos los archivos y carpetas con la estructura correcta.",
      "Coloca tus propias imágenes y el video de fondo en las carpetas correspondientes dentro de `assets/`.",
      "Abre el archivo `index.html` con tu navegador web preferido (Chrome, Firefox, Safari, etc.)."
    ],
    "personalization": {
      "title": "Personalización",
      "items": [
        "**Imágenes y Video:** Reemplaza los archivos de ejemplo en `assets/` con tus propios recursos. Asegúrate de que los nombres de los archivos en el código HTML coincidan.",
        "**Textos:** Edita el contenido de los títulos, descripciones y testimonios directamente en el archivo `index.html` para adaptarlos a tu campaña.",
        "**Colores:** Puedes cambiar la paleta de colores editando las variables CSS en la parte superior del archivo `styles.css` (`--color-primary`, `--color-accent`, etc.)."
      ]
    },
    "ending_message": "Esperamos que esta landing page te ayude a alcanzar tus objetivos de venta. ¡Éxito!"
  }
}
