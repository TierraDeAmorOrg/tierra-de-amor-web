# Casa Hogar de Niños Tierra de Amor – Sitio web

Sitio web estático profesional desarrollado con HTML, CSS y JavaScript. Está preparado para publicarse gratis en GitHub Pages.

## Archivos principales

- `index.html`: estructura y contenido de la página.
- `styles.css`: diseño visual, colores, responsive y animaciones.
- `script.js`: menú móvil, botones de copiar y animaciones.
- `assets/img/`: imágenes institucionales o placeholders.
- `assets/video/`: colocar aquí el video institucional autorizado como `video-institucional.mp4`.

## Privacidad infantil

Antes de publicar fotos o videos:

1. Evita rostros, nombres, colegio, horarios o datos que permitan identificar a los niños.
2. Usa fotos de manos, donaciones, alimentos, ambientes, materiales o tomas de espalda.
3. Publica historias colectivas, no casos individuales.
4. Valida autorización formal de la dirección del hogar antes de subir material audiovisual.

## Cómo editar textos rápidos

Abre `index.html` y busca los títulos o frases que quieras modificar. Puedes cambiar:

- Datos de donación.
- Necesidades urgentes.
- Historia institucional.
- Enlace de Facebook.
- Número de WhatsApp.

## Cómo reemplazar imágenes

1. Guarda tus imágenes en `assets/img/`.
2. Reemplaza en `index.html` las rutas, por ejemplo:

```html
<img src="assets/img/mi-foto.jpg" alt="Descripción segura de la imagen">
```

## Cómo colocar el video

1. Copia tu video en `assets/video/`.
2. Renómbralo exactamente como:

```text
video-institucional.mp4
```

3. La web lo cargará automáticamente.

## Publicación en GitHub Pages desde cero

### 1. Crear una cuenta en GitHub

Entra a GitHub y crea tu cuenta. Luego inicia sesión.

### 2. Instalar Git

Descarga Git para Windows desde la web oficial de Git. Instálalo dejando las opciones por defecto.

### 3. Instalar Visual Studio Code

Descarga VS Code e instálalo. Servirá para editar los archivos.

### 4. Crear un repositorio

En GitHub:

1. Clic en **New repository**.
2. Nombre sugerido: `tierra-de-amor-web`.
3. Selecciona **Public**.
4. Marca **Add a README file** si quieres, aunque no es obligatorio.
5. Clic en **Create repository**.

### 5. Subir archivos sin saber comandos

Esta es la forma más simple:

1. Entra a tu repositorio.
2. Clic en **Add file**.
3. Clic en **Upload files**.
4. Arrastra todos los archivos y carpetas de este proyecto.
5. Baja hasta **Commit changes**.
6. Clic en **Commit changes**.

### 6. Activar GitHub Pages

1. En tu repositorio, entra a **Settings**.
2. En el menú izquierdo, entra a **Pages**.
3. En **Build and deployment**, elige:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
4. Clic en **Save**.
5. Espera unos minutos y GitHub mostrará el enlace público de la web.

### 7. Subir cambios después

Cada vez que edites algo:

1. Entra al archivo en GitHub.
2. Clic en el lápiz de edición.
3. Cambia el texto.
4. Clic en **Commit changes**.
5. GitHub Pages actualizará la web.

## Forma profesional con comandos Git

Abre la terminal en la carpeta del proyecto y ejecuta:

```bash
git init
git add .
git commit -m "Primera versión de la web Tierra de Amor"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/tierra-de-amor-web.git
git push -u origin main
```

Cambia `TU-USUARIO` por tu usuario real de GitHub.

## Recomendación de contenido institucional

Publicar una sección mensual de transparencia:

- Total recaudado.
- Gastos realizados.
- Lista de compras.
- Fotos seguras de donaciones.
- Necesidades del mes siguiente.

Esto aumenta confianza y mejora la posibilidad de conseguir donantes recurrentes.
