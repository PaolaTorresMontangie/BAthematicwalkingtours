# BA Thematic Walking Tours

Sitio web bilingüe (EN / ES) desarrollado para **BA Thematic Walking Tours**, una propuesta de visitas guiadas temáticas en Buenos Aires orientada a viajeros internacionales.

El proyecto prioriza **arquitectura clara, buenas prácticas de frontend, SEO, accesibilidad y diseño responsive**, utilizando HTML semántico, Sass y Bootstrap.

---

## 🌍 Descripción general

BA Thematic Walking Tours ofrece recorridos a pie en inglés y español, enfocados en historia, arquitectura, simbolismo y cultura local.

El sitio presenta:
- Página principal con tours destacados
- Páginas de detalle de cada tour
- Sección About / Nosotros
- Página de Contacto
- FAQ
- Versión bilingüe con estructura paralela EN / ES

---

## 🛠 Tecnologías utilizadas

- **HTML5** – estructura semántica y accesible  
- **CSS3 / Sass (SCSS)** – estilos modulares y escalables  
- **Bootstrap 5** – layout responsive y componentes base  
- **JavaScript (vanilla)** – pequeños comportamientos UI  
- **SEO técnico** – meta tags, Open Graph, Twitter Cards, hreflang  

---

## 📁 Estructura del proyecto

```text
/
├── index.html                # Home (EN)
├── pages/                    # Páginas internas (EN)
│   ├── nosotros.html
│   ├── contacto.html
│   ├── faq.html
│   ├── tourCementerioRecoleta.html
│   ├── tourMasonesEnBA.html
│   └── tourPalacioBarolo.html
│
├── es/                       # Versión en español
│   ├── index.html            # Home (ES)
│   └── pages/
│       ├── nosotros.html
│       ├── contacto.html
│       ├── faq.html
│       ├── tourCementerioRecoleta.html
│       ├── tourMasonesEnBA.html
│       └── tourPalacioBarolo.html
│
├── css/
│   └── styles.css            # CSS compilado
│
├── scss/
│   ├── utilities/
│   │   ├── _variables.scss   # Paleta, tipografías, breakpoints
│   │   ├── _mixins.scss      # Mixins reutilizables
│   │   └── _extends.scss    # Placeholders (%)
│   │
│   ├── layouts/
│   │   ├── _header.scss
│   │   ├── _main.scss
│   │   └── _footer.scss
│   │
│   └── styles.scss           # Archivo principal de Sass
│
├── img/                      # Imágenes, iconos, og-image, favicon
└── README.md
