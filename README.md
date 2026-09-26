# Ortesis&Protesis

Sitio web para **Ortesis&Protesis**, un centro biomédico especializado en ortesis y prótesis biomecánicas personalizadas.

Proyecto desarrollado como parte del **Desafío Práctico I — Desarrollo Web I**, Ingeniería de Software y Negocios Digitales, ESEN.

---

## Descripción

El sitio presenta los servicios, catálogo de dispositivos y proceso clínico de OrtoVida, permitiendo a los usuarios conocer la organización, explorar productos y agendar una evaluación clínica mediante un formulario de contacto.

Desarrollado con **HTML5** y **CSS3** puro (sin frameworks, sin JavaScript), utilizando **Flexbox** y **Grid** para la maquetación, con un diseño completamente **adaptable** (responsive) a escritorio y móvil.

---

## Equipo

| Integrante | Página a cargo |
|---|---|
| Luis Rivera | Página de inicio (`index.html`) |
| Rogelio | Productos / Catálogo (`productos.html`) |
| Davo | Nosotros (`nosotros.html`) |
| Los tres | Contacto (`contacto.html`) |

---

## Páginas del sitio

- **Inicio** — presenta la organización, su actividad principal y una llamada a la acción hacia el catálogo y la agenda de citas.
- **Productos** — catálogo de dispositivos (ortesis y prótesis) organizado por categoría, con información técnica de cada uno.
- **Nosotros** — misión, visión, trayectoria, equipo especialista y metodología clínica de OrtoVida.
- **Contacto** — formulario de solicitud de valoración clínica con validaciones nativas de HTML, información de la sede y preguntas frecuentes.

---

##Tecnologías utilizadas

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS3 (Flexbox y CSS Grid para la maquetación)
- Diseño responsive con media queries
- Validaciones de formulario nativas de HTML (`required`, `type`, `pattern`, etc.)

> No se utilizan frameworks CSS, plantillas prediseñadas ni JavaScript, conforme a los requisitos del desafío.

---

## Cómo ejecutar el proyecto localmente

1. Clona el repositorio:
   ```bash
   git clone https://github.com/lrivera-dev/ortesis-protesis-web.git
   cd ortesis-protesis-web
   ```
2. Abre `index.html` en tu navegador, o usa una extensión como **Live Server** en VS Code para recarga automática.

No requiere instalación de dependencias ni servidor backend.

---

## Publicación

El sitio está publicado mediante **GitHub Pages**

---

## Flujo de trabajo con Git

- `main` contiene siempre una versión funcional del sitio y no se edita directamente.
- Cada funcionalidad o página se desarrolla en su propia rama (`feature/...`) y se integra mediante **Pull Request** revisado por otro integrante del equipo.
- Convención de ramas:
  - `feature/nombre-de-la-página-o-funcionalidad`
  - `style/ajuste-de-maquetación`
  - `fix/corrección`
