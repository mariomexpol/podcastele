# 🎙️ PodcastELE — Generador de Cuentos para Podcasts de Español

> Herramienta profesional para crear cuentos originales, adaptados por nivel y género, con ejercicios pedagógicos para podcasts de aprendizaje de español (ELE).

---

## ✨ Características

### 🎭 Generación de Cuentos
- **Nivel MCER completo**: A1, A2, B1, B2, C1 y C2 con instrucciones lingüísticas precisas para cada nivel
- **14 géneros literarios**: Misterio, policíaco, ciencia ficción, fantasía, romance, aventura, terror, histórico, realismo, humor, drama, thriller, fábula y costumbrismo
- **12 tonos/atmósferas**: Suspenso, melancólico, cómico, romántico, oscuro, esperanzador, nostálgico, épico, satírico, lírico, intrigante y tierno
- **Control de duración**: De 5 a 70 minutos de lectura (~130 palabras/minuto)
- **Variedad del español**: Neutro, España, México, Argentina, Colombia, Perú, Chile
- **Protagonista y ambientación** personalizables
- **Modo serie**: Episodios conectados con coherencia narrativa
- **Notas para el narrador**: Sugerencias de énfasis, pausas, velocidad y efectos de sonido
- **Glosario previo**: Palabras clave definidas antes de escuchar el cuento
- **Sinopsis**: Para presentar el episodio a tus oyentes

### 📚 Ejercicios Pedagógicos (ELE)
- **Comprensión lectora**: Opción múltiple, preguntas abiertas, verdadero/falso con justificación
- **Vocabulario en contexto**: Definiciones, ejemplos y ejercicios de completar
- **Gramática práctica**: Ejercicios adaptados al nivel MCER del cuento
- **Expresiones idiomáticas**: Significado, origen y uso
- **Guía de pronunciación**: Palabras difíciles con orientación fonética
- **Conversación y debate**: Preguntas para discusión oral
- **Escritura creativa**: Actividades de extensión narrativa
- **Fragmento para dictado**: Con instrucciones para el docente
- **Contexto cultural**: Información y reflexión intercultural
- **Respuestas incluidas**: Clave de respuestas y notas metodológicas para el docente

### 📤 Exportación
| Formato | Descripción |
|---------|-------------|
| **PDF** | Ventana de impresión del navegador — formateado y con portada |
| **DOCX** | Archivo Word editable (.doc compatible con Microsoft Word) |
| **Copiar texto** | Portapapeles para pegar en cualquier app |
| **JSON** | Datos estructurados para archivar y reutilizar |

### ⚙️ Otros
- **Estadísticas automáticas**: Conteo de palabras, duración estimada, capítulos
- **Guardado de configuración**: Recuerda tus preferencias entre sesiones
- **Sin servidor**: 100% en el navegador, sin instalar nada

---

## 🚀 Instalación y Uso

### Opción 1: GitHub Pages (recomendado)
1. Haz fork de este repositorio
2. Ve a **Settings → Pages → Source → main branch**
3. Accede a tu URL de GitHub Pages
4. ¡Listo!

### Opción 2: Local
1. Descarga `index.html`
2. Ábrelo en cualquier navegador moderno
3. No necesitas servidor local

### Configurar la API Key
1. Obtén tu clave en [console.anthropic.com](https://console.anthropic.com)
2. Pégala en el campo **API KEY** en la parte superior de la app
3. Haz clic en 💾 para guardarla en el navegador (localStorage)

> ⚠️ **Seguridad**: La API key se guarda solo en tu navegador local. Nunca se envía a ningún servidor excepto directamente a la API de Anthropic.

---

## 💡 Guía de Uso

### Generar un cuento
1. Introduce un **tema o idea** (o déjalo vacío para sorprenderte)
2. Selecciona el **nivel MCER** de tus alumnos
3. Elige **género**, **tono** y **público**
4. Ajusta la **duración** con el deslizador
5. Opcionalmente: añade protagonista, ambientación, modo serie
6. Haz clic en **🎙️ Generar Cuento**

### Generar ejercicios
1. Marca los **tipos de ejercicio** que necesitas
2. (Genera el cuento primero si aún no lo has hecho)
3. Haz clic en **📚 Generar Ejercicios**

### Exportar
1. Ve a la pestaña **📤 Exportar**
2. Selecciona qué incluir
3. Elige el formato: PDF, DOCX, texto o JSON

---

## 📋 Referencia MCER

| Nivel | Nombre | Características lingüísticas |
|-------|--------|------------------------------|
| A1 | Principiante | Solo presente e infinitivos. ~500 palabras. Frases muy simples |
| A2 | Elemental | Presente, indefinido e imperfecto básicos. ~1.000 palabras |
| B1 | Intermedio | Todos los tiempos del indicativo. Subjuntivo básico. ~2.000 palabras |
| B2 | Intermedio alto | Subjuntivo natural. Expresiones idiomáticas. Estilo fluido |
| C1 | Avanzado | Léxico sofisticado. Estructuras complejas. Lenguaje figurado |
| C2 | Maestría | Dominio pleno. Riqueza léxica excepcional. Estilo literario |

---

## 🛠️ Tecnologías

- HTML5, CSS3, JavaScript vanilla (sin frameworks)
- [API de Claude](https://anthropic.com) (Anthropic) — modelos claude-opus-4-5 y claude-sonnet-4-5
- Google Fonts: Playfair Display + Source Serif 4 + DM Sans
- Exportación DOCX via Blob (Word-HTML compatible)
- Exportación PDF via `window.print()` con CSS optimizado

---

## 📁 Estructura del proyecto

```
PodcastELE/
└── index.html    # Aplicación completa (single-file app)
└── README.md     # Este archivo
```

---

## 🔒 Privacidad

- No hay backend ni base de datos
- Los cuentos generados solo se almacenan en tu sesión del navegador
- La API key se guarda en `localStorage` de tu navegador únicamente
- Todo el contenido generado es tuyo

---

## 📄 Licencia

MIT License — úsalo libremente para tu podcast y con tus alumnos.

---

## 🤝 Contribuciones

Pull requests bienvenidos. Ideas para mejoras:
- [ ] Historial de episodios generados
- [ ] Plantillas de series prediseñadas
- [ ] Exportación EPUB para e-readers
- [ ] Modo oscuro / claro toggle
- [ ] Generación de imágenes de portada
- [ ] Integración con plataformas de podcast

---

*Hecho con ❤️ para profesores y podcasters de español*
