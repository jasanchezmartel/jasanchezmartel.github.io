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
