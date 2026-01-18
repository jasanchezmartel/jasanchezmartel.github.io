# 📝 Instrucciones de Uso del Portfolio

## 🎯 Pasos para completar tu portfolio

### 1. Agregar tu CV en PDF
Actualmente el portfolio incluye un CV en formato HTML. Para agregar tu CV en PDF:

1. Guarda tu CV de Europass como PDF con el nombre: `CV_JuanAntonioSanchezMartel.pdf`
2. Coloca el archivo en la carpeta `assets/`
3. El botón de descarga en el portfolio ya está configurado para usar este archivo

### 2. Agregar una foto de perfil (Opcional)
Si quieres añadir tu foto al portfolio:

1. Guarda tu foto como `perfil.jpg` o `perfil.png`
2. Colócala en la carpeta `assets/`
3. Abre `index.html` y busca la línea con `.avatar-circle`
4. Puedes agregar tu foto modificando el CSS o añadiendo un elemento `<img>`

### 3. Ver el portfolio localmente

#### Opción 1: Abrir directamente
- Haz doble clic en `index.html`
- Se abrirá en tu navegador predeterminado

#### Opción 2: Con servidor local (recomendado)
```bash
# Con Python (si lo tienes instalado)
python -m http.server 8000

# Con Node.js
npx http-server

# Luego abre: http://localhost:8000
```

### 4. Subir a GitHub Pages

1. **Crear el repositorio en GitHub:**
   - Ve a GitHub.com
   - Crea un nuevo repositorio con el nombre: `jasanchezmartel.github.io`
   - NO inicialices con README (ya tienes uno)

2. **Subir tus archivos:**
   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Initial commit: Portfolio personal"
   git branch -M main
   git remote add origin https://github.com/jasanchezmartel/jasanchezmartel.github.io.git
   git push -u origin main
   ```

3. **Configurar GitHub Pages:**
   - Ve a Settings → Pages
   - En "Source", selecciona la rama `main`
   - Guarda los cambios
   - Tu portfolio estará disponible en: `https://jasanchezmartel.github.io`

### 5. Personalizar el contenido

#### Modificar información personal
Edita `index.html` para cambiar:
- Texto de presentación
- Descripción de proyectos
- Información de contacto
- Enlaces a redes sociales

#### Ajustar colores y estilos
Edita `css/style.css`:
- Las variables CSS están al inicio del archivo (`:root`)
- Cambia los colores principales modificando `--primary-color`, etc.

#### Agregar más proyectos
En `index.html`, busca la sección `<div class="projects-grid">` y agrega nuevas tarjetas de proyecto siguiendo el mismo formato.

## 📊 Criterios de Evaluación Detallados (Parte 2)

Estos son los criterios específicos extraídos de la documentación oficial que debes cumplir:

### 1. Proyectos (Portfolio) — "La sección que decide entrevistas"
**Objetivo:** Mostrar capacidad real. Mínimo 3 proyectos (o 2 proyectos + 1 caso de prácticas).

Cada proyecto debe tener una ficha estándar obligatoria:
- **Título + Rol** (ej.: "App de tickets IT — rol: backend")
- **Contexto** (problema real o simulado, para quién, por qué)
- **Objetivo y Alcance** (qué hace y qué no hace)
- **Tecnologías** (lista concreta)
- **Arquitectura / Diseño** (diagrama simple o explicación clara)
- **Funcionalidades Clave**
- **Tu contribución exacta** (qué hiciste tú, qué hizo el equipo)
- **Evidencias:** Enlace a repositorio (GitHub) o Drive, capturas / demo, documentación.
- **Calidad:** Pruebas, validaciones, logs, control de errores.
- **Resultados y Aprendizaje:** Qué mejoró, métricas, qué repetirías/cambiarías.
- **Exigencia Máxima:** README profesional en GitHub (instalación, uso, endpoints, etc.).

### 2. Experiencia / Prácticas — "Impacto, no tareas"
**Objetivo:** Que se vea tu aportación.
- **Datos:** Empresa/centro, fechas, rol, área.
- **Bullets (4-6):** Acción + Herramienta + Resultado (formato impacto).
- **Herramientas reales usadas.**
- **Lecciones aprendidas:** 3 bullets.
- *Prohibido: listas de tareas genéricas sin resultados.*

### 3. Formación y Certificaciones
- Titulación, centro, fechas, módulos relevantes.
- Proyectos destacados vinculados.
- Certificaciones (o "En preparación" con fecha).
- Cursos relevantes (solo si aportan valor).

### 4. CV y Documentos
- CV en PDF (ATS-friendly, 1 página ideal).
- Carta de presentación breve (opcional).
- **Exigencia:** El CV debe estar alineado con la web (sin contradicciones).

### 5. Contacto
- Email profesional, LinkedIn, GitHub.
- Ciudad y disponibilidad.
- **Exigencia:** Enlaces probados y funcionales.

### 📌 Elementos Transversales Obligatorios
- **A) Enlaces verificables:** No puede haber enlaces rotos; repositorios públicos.
- **B) Evidencia y trazabilidad:** Cada habilidad debe apuntar a un proyecto/experiencia.
- **C) Profesionalidad documental:** Ortografía impecable, nombres técnicos correctos (ej. "PostgreSQL", no "Postgress").
- **D) Ética y privacidad:** No publicar datos sensibles; anonimizar capturas.

### ✅ Requisitos Mínimos para APTO
- Estructura completa con las 8 secciones.
- 3 proyectos con ficha completa.
- CV PDF descargable y coherente.
- LinkedIn y GitHub enlazados y actualizados.
- Cero errores ortográficos y cero enlaces rotos.

## 📋 Checklist antes de publicar

- [ ] Tu CV en PDF está en la carpeta `assets/`
- [ ] Has revisado que todos tus datos de contacto son correctos
- [ ] Los enlaces a tus repositorios funcionan
- [ ] Has probado el portfolio en diferentes navegadores
- [ ] El diseño se ve bien en móvil y escritorio
- [ ] Has corregido cualquier error ortográfico

## 🔧 Solución de problemas

### El portfolio no se muestra correctamente
- Asegúrate de que la carpeta `css/` y `js/` estén en el mismo nivel que `index.html`
- Verifica que los nombres de archivo coincidan (sensible a mayúsculas/minúsculas)

### GitHub Pages no funciona
- El repositorio debe llamarse exactamente: `jasanchezmartel.github.io`
- Espera unos minutos después de configurar Pages (puede tardar hasta 10 minutos)
- Asegúrate de que el repositorio sea público

### El CV no se descarga
- Verifica que el archivo PDF esté en `assets/CV_JuanAntonioSanchezMartel.pdf`
- El nombre debe coincidir exactamente con el especificado en `index.html`

## 📱 Contacto

Si necesitas ayuda o tienes preguntas, revisa la documentación de GitHub Pages:
- https://docs.github.com/es/pages

---

¡Buena suerte con tu portfolio! 🚀
