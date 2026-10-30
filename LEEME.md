# Diario de sueño – app instalable

Esta carpeta contiene una app web instalable en iPhone y Android. La app no envía datos a ningún servidor: todo lo que registras queda guardado solo en el teléfono donde la usas.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| index.html | La app completa |
| manifest.webmanifest | Nombre, colores e íconos para instalarla |
| sw.js | Permite abrir la app sin conexión |
| icon-*.png, apple-touch-icon.png | Íconos |

## 1. Publicarla gratis en GitHub Pages (una sola vez, ~10 minutos)

1. Crea una cuenta en github.com (si no tienes).
2. Crea un repositorio nuevo, por ejemplo `diario-sueno`. Debe ser **público** para usar GitHub Pages gratis. Solo queda público el código de la app, nunca tus datos.
3. En el repositorio: **Add file → Upload files**, arrastra todos los archivos de esta carpeta (no la carpeta) y presiona **Commit changes**.
4. Ve a **Settings → Pages**. En "Build and deployment" elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y guarda.
5. En uno o dos minutos la app queda en `https://TU-USUARIO.github.io/diario-sueno/`.

## 2. Instalarla en el teléfono

- **iPhone:** abre el link en **Safari** → botón Compartir → **Agregar a pantalla de inicio**.
- **Android:** abre el link en **Chrome** → menú ⋮ → **Instalar app** (o "Agregar a la pantalla principal"). La app también puede ofrecer el botón "Instalar" en su menú ☰.

Usa siempre el ícono instalado. En iPhone, el ícono y Safari guardan datos por separado.

## 3. Traer los datos de la versión que estaba en Claude (una sola vez)

1. En la versión de Claude: Historial → **Descargar respaldo** → **Copiar**.
2. En la app nueva: menú ☰ → **Traer datos de la versión anterior** → pegar → **Importar**.

Las noches antiguas marcadas con "café" quedan con café sin hora; las marcadas con "alcohol" quedan con una nota "cantidad no registrada".

## 4. Respaldo

Menú ☰ → **Descargar respaldo Excel**. En el teléfono se abre el menú de compartir: puedes guardarlo en Archivos/Drive o enviártelo por correo. Para recuperar datos: menú ☰ → **Cargar desde Excel**.

La app avisa si pasan 7 días sin respaldo. Si borras los datos del navegador o desinstalas la app, los datos del teléfono se pierden; el Excel es tu respaldo.

Recomendación: usa el Excel como respaldo, no para editar. Si lo editas, mantén los nombres de las columnas.

## 5. Actualizar la app

Si te entrego una versión nueva, reemplaza `index.html` (y los archivos que cambien) en el repositorio. Tus datos no se borran: quedan en el teléfono.
