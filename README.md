<a id="readme-top"></a>

<h1 align="center">Free Link Tree</h1>

<div align="center">

![Astro](https://img.shields.io/badge/Astro-0C1222?style=for-the-badge&logo=astro&logoColor=FDFDFE)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

</div>

![Link Tree Screenshot](/screenshot.png)

### Prerequisites

- **Node.js** -> `v18.17.1` o `v20.3.0` o mayor. (`v19` no esta soportado) [Descarga aqui]("https://nodejs.org/en/download/prebuilt-installer/current").
- **Visual Studio Code** -> con la extensión [oficial de Astro](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode).
- **Git** -> [Descarga e instala Git](https://git-scm.com/downloads).

### Instalación

1. Abre una terminal y dirigete a la ruta o carpeta donde quieras tener el código.
2. Clona el repositorio:
   ```sh
   git clone https://github.com/alexjamesmx/link-tree.git
   ```
3. Cambiate al directorio del proyecto e instala las dependencias:
   ```sh
   cd link-tree
   npm install
   ```
4. Corre el servidor de desarrollo:
   ```sh
   npm run dev
   ```

<p align="right"><a href="#readme-top">Volver al inicio ⬆️</a></p>

## Edita tu Link Tree

La mejor parte de este árbol de enlaces es que puedes modificar todos los aspectos del sitio web muy fácilmente, sólo tienes que editar el archivo `index.json`. Este JSON contiene las siguientes secciones:

- **html** -> Editar idioma, título, descripción y favicon (reemplácelo en `/src/layouts/Layout.astro`).
- **fondo** -> Use el mismo color dos veces para un color sólido o use dos colores para un color degradado (use el formato de color hexadecimal).
- **foto de perfil** -> Edita tu imagen (reemplaza 'profile.webp' en `/public`).
- **socials** -> Agrega más íconos con la URL de tus redes sociales (consulta las redes disponibles).
- **destacado** -> Resalte enlaces con una imagen de fondo o color (igual que los botones).
- **botones** -> Agrega más botones con la URL de tus redes sociales (ver las redes disponibles).
- **pie de página** -> Edite los derechos de autor y la URL del desarrollador (Hecho solo para usted 😎).

### Iconos

Simplemente edite la clave `network` con cualquiera de los siguientes valores (distingue entre mayúsculas y minúsculas):

- Discord
- Facebook
- GitHub
- Instagram
- Link
- LinkedIn
- Mail
- Map
- Medium
- Spotify
- TikTok
- Twitch
- WhatsApp
- X
- YouTube

> [!NOTE]
> Si necesita más íconos, puede visitar este sitio: [Tabler Icons](https://tabler.io/icons)

<p align="right"><a href="#readme-top">Volver ⬆️</a></p>

### Despliegue

1. En el directorio del proyecto, ejecute el siguiente comando:

   ```sh
   npm run build
   ```

2. Se creará la carpeta `dist` con los archivos del proyecto, esos archivos puede subirlos a cualquier servicio de hosting estático. Simplemente baje esos archivos dentro de `dist` y copielos a el hosting de su agrado.

![Link Tree Desplegar](/public/desplegar.png)

Aquí está la lista de los servicios de hosting gratuitos más populares:
https://docs.astro.build/en/guides/deploy/

También puede usar su propio servidor o algún alojamiento con el que ya cuente, por ejemplo hostinguer.

## Licencia

Distribuido bajo la licencia MIT. `Código abierto`.

<p align="right"><a href="#readme-top">Volver ⬆️</a></p>
