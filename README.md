# IA en la Investigación Educativa

Sitio web del **Ciclo de Seminarios «Investigar en el Nivel Superior, de la idea al proyecto»**.

- **Destinatarios:** Docentes del IES N.° 10 — Libertador General San Martín (Ledesma), Jujuy.
- **Responsable Académica:** Ing. Prof. María Cristina Cosme.

---

## 🚀 Cómo publicarlo en GitHub Pages

1. Creá un repositorio nuevo en GitHub llamado **`IAenInvestigacionEducativa`** (público).
2. Subí **todo el contenido de esta carpeta** (no la carpeta en sí, sino los archivos y subcarpetas que están adentro: `index.html`, `css/`, `js/`, etc.).
   - Opción simple: en el repo, botón **Add file → Upload files**, arrastrá todo y confirmá con **Commit changes**.
3. Andá a **Settings → Pages**.
4. En **Source**, elegí la rama **`main`** y la carpeta **`/ (root)`**. Guardá.
5. Esperá uno o dos minutos. Tu sitio quedará en:

   ```
   https://TUUSUARIO.github.io/IAenInvestigacionEducativa/
   ```

   (reemplazá `TUUSUARIO` por tu nombre de usuario de GitHub).

---

## 📁 Estructura del proyecto

```
IAenInvestigacionEducativa/
├── index.html            → Inicio (presentación, objetivos, cronograma, modalidad)
├── modulo1.html          → IA Generativa en la Investigación Educativa
├── modulo2.html          → Diseño de Encuestas y Lectura de Datos
├── modulo3.html          → Análisis Cualitativo con IA
├── modulo4.html          → Búsqueda Bibliográfica
├── modulo5.html          → Gestión Bibliográfica
├── prompts.html          → Banco de Prompts (filtrable)
├── herramientas.html     → Galería de Herramientas
├── biblioteca.html       → Biblioteca digital (descargas)
├── actividades.html      → Talleres e Informe Final
├── certificados.html     → Espacio para certificados
├── bibliografia.html     → Bibliografía en APA 7
├── recursos.html         → Página puente de descargas
├── css/
│   └── estilos.css       → Diseño, modo oscuro y responsive
├── js/
│   ├── script.js         → Navegación, buscador, modo oscuro, animaciones
│   └── prompts-data.js   → Datos del banco de prompts
├── assets/img/           → Imágenes y logos (vacío, listo para usar)
├── recursos/             → (Opcional) PDFs y materiales locales
├── .nojekyll             → Evita que GitHub procese el sitio con Jekyll
└── README.md
```

## ✨ Funciones incluidas

- ✅ Menú lateral fijo + menú hamburguesa en celular
- ✅ Buscador interno (busca en todas las páginas)
- ✅ Tarjetas interactivas con efecto al pasar el cursor
- ✅ Modo oscuro (recuerda la elección)
- ✅ Banco de prompts filtrable por categoría y con botón «Copiar»
- ✅ Línea de tiempo del seminario
- ✅ Galería de herramientas
- ✅ Espacio para certificados
- ✅ Diseño responsive (PC, tablet, celular)
- ✅ Animación de red neuronal en el inicio

## 🎨 Identidad visual

- Azul institucional: `#1E3A8A`
- Violeta IA: `#7C3AED`
- Tipografías: Space Grotesk (títulos) e Inter (texto).

---

## 🔧 Para personalizar antes de publicar

1. **Bibliografía** (`bibliografia.html`): completá título exacto, revista/editorial, volumen, páginas y DOI de cada referencia. *Verificá cada fuente en su base original; no copies datos generados por IA sin chequearlos.*
2. **Descargas** (`biblioteca.html`, `actividades.html`, `certificados.html`): reemplazá los `href="recursos.html"` por los enlaces reales de Google Drive de cada archivo.
3. **Cronograma** (`index.html`): cargá las fechas confirmadas de cada encuentro.
4. **Banco de prompts** (`js/prompts-data.js`): agregá o editá prompts; el filtro y el buscador se actualizan solos.
5. **Logo** (`assets/img/`): si tenés el logo del IES N.° 10, colocalo ahí y reemplazá el bloque `.sidebar__logo` en `js/script.js`.
