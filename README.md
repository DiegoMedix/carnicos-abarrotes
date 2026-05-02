# 🥩 Cárnicos & Abarrotes Don Luis

Sitio web desarrollado como proyecto práctico del **Taller de GitHub** — Desarrollo web con Git, GitHub y GitHub Pages.

---

## 🌐 Sitio publicado

🔗 **https://diegomedix.github.io/carnicos-abarrotes/**

---

## 📋 Descripción del proyecto

Sitio web para una empresa local de cárnicos y abarrotes ubicada en el barrio Kennedy, Bogotá. El proyecto fue desarrollado aplicando el flujo profesional de trabajo con Git y GitHub: creación de repositorio, trabajo en ramas, pull requests y publicación con GitHub Pages.

El sitio cuenta con tres páginas principales:

- **Inicio** — Presentación de la empresa, beneficios y llamados a la acción
- **Catálogo de productos** — Listado de cárnicos y abarrotes con precios
- **Contacto** — Información de contacto, horarios y formulario de mensaje

---

## 📁 Estructura del repositorio

```
carnicos-abarrotes/
├── index.html          → Página principal (inicio)
├── productos.html      → Catálogo de productos
├── contacto.html       → Información y formulario de contacto
├── css/
│   └── estilos.css     → Hoja de estilos global del sitio
├── img/
│   ├── La-carne-de-cerdo-y-la-salud-mental-ASPE-2.jpg
│   ├── diferentes-productos-carnicos-sobre-fondo-bl... (x2)
│   └── R.jpg
└── README.md           → Documentación del proyecto
```

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de las páginas |
| CSS3 | Estilos, animaciones y diseño responsive |
| Google Fonts | Tipografías Playfair Display y DM Sans |
| Git | Control de versiones |
| GitHub | Repositorio remoto y colaboración |
| GitHub Pages | Publicación y despliegue del sitio |

---

## 🔀 Flujo de trabajo Git aplicado

### 1. Configuración inicial
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

### 2. Creación del repositorio
- Repositorio creado directamente en **github.com**
- Inicializado con `README.md`
- Visibilidad: **Público**

### 3. Creación de archivos base
Los archivos fueron creados directamente desde la interfaz web de GitHub:
- `index.html` — Página de inicio
- `productos.html` — Catálogo
- `contacto.html` — Contacto
- `css/estilos.css` — Estilos

### 4. Trabajo en rama
Se creó la rama `feature/catalogo` para desarrollar el catálogo de productos sin afectar la rama principal:

```
main
 └── feature/catalogo  ← desarrollo del catálogo
```

Los commits realizados en esta rama fueron:
- `Add product catalog for meats and groceries`
- `Add initial HTML structure for the website`
- `Add contacto.html for contact information and form`
- `Add CSS styles for layout and components`

### 5. Pull Request
- PR creado desde `feature/catalogo` → `main`
- Título: *"Add product catalog for meats and groceries"*
- 4 commits · 4 archivos cambiados · 371 líneas añadidas
- Estado: **Merged** ✅

### 6. Publicación con GitHub Pages
- Activado desde **Settings → Pages → Branch: main → Save**
- El sitio se actualiza automáticamente con cada `git push`

---

## 🎨 Diseño del sitio

El sitio fue diseñado con una estética cálida y profesional que refleja la tradición y confianza de la empresa:

- **Paleta de colores** — Rojo oscuro `#8B1A1A`, crema `#fdf6ee` y blanco
- **Tipografía** — Playfair Display (títulos) + DM Sans (cuerpo)
- **Animaciones** — Tarjetas flotantes en el hero, hover en productos
- **Responsive** — Adaptado para dispositivos móviles y escritorio
- **Componentes** — Header sticky, barra de estadísticas, cards de productos, panel de contacto

---

## 📄 Páginas del sitio

### `index.html` — Inicio
- Hero con titular principal y llamados a la acción
- Badge de "20+ años de experiencia"
- Barra de estadísticas (500+ clientes, 80+ productos)
- Sección de categorías (Cárnicos, Abarrotes, Domicilios)
- Banner CTA de contacto

### `productos.html` — Catálogo
**Cárnicos:**
- Pechuga de pollo — $6.500/lb
- Lomo de res — $14.000/lb
- Costilla de cerdo — $9.000/lb
- Carne molida — $8.500/lb
- Chuleta de res — $12.000/lb
- Chorizo casero — $7.000/lb

**Abarrotes:**
- Arroz Diana x 500g — $3.200
- Aceite vegetal x 1L — $8.900
- Fríjoles x 500g — $4.500
- Panela x 500g — $2.800
- Huevos x 12 und — $9.500
- Leche entera x 1L — $3.400

### `contacto.html` — Contacto
- Teléfono y WhatsApp
- Correo electrónico
- Dirección: Cra. 80 # 38-20, Barrio Kennedy, Bogotá
- Horario de atención
- Formulario de contacto con campos: nombre, teléfono, correo, tipo de pedido y mensaje

---

## ⚙️ Referencia de comandos Git utilizados

| Comando | Acción |
|---|---|
| `git config --global user.name` | Configura el nombre del autor |
| `git clone <url>` | Clona el repositorio |
| `git add .` | Agrega todos los cambios al staging |
| `git commit -m "mensaje"` | Guarda los cambios con descripción |
| `git push origin main` | Sube los commits al repositorio remoto |
| `git checkout -b feature/catalogo` | Crea y cambia a una nueva rama |
| `git push origin feature/catalogo` | Sube la rama al repositorio remoto |

---

## 👤 Autor

**DiegoMedix**
- GitHub: [@DiegoMedix](https://github.com/DiegoMedix)
- Repositorio: [carnicos-abarrotes](https://github.com/DiegoMedix/carnicos-abarrotes)

---

## 📚 Recursos del taller

- Documentación oficial de GitHub: [docs.github.com](https://docs.github.com)
- GitHub Skills (cursos interactivos): [skills.github.com](https://skills.github.com)
- Guía de Markdown: [markdownguide.org](https://markdownguide.org)

---

*Proyecto desarrollado en el Taller Práctico de GitHub — Nivel Principiante–Intermedio · Duración 2 horas*
