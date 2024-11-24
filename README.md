<a id="readme-top"></a>

<h1 align="center">Free Link Tree</h1>

<div align="center">

![Astro](https://img.shields.io/badge/Astro-0C1222?style=for-the-badge&logo=astro&logoColor=FDFDFE)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

</div>

![Link Tree Screenshot](/screenshot.png)

### Prerequisites

- **Python** -> `v18.17.1` o `v20.3.0` o mayor. (`v19` no esta soportado)
- **Visual Studio Code** -> with the [Official Astro Extension](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode).
- **Git** -> [Download & Install Git](https://git-scm.com/downloads).

### Instalación

1. Clona el repositorio:
   ```sh
   git clone https://github.com/alexjamesmx/link-tree.git
   ```
2. Cambiate al directorio del proyecto:
   ```sh
   cd link-tree
   npm install
   ```
3. Corre el servidor de desarrollo:
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
- **destacado** -> Resalte enlaces con una imagen de fondo o color (igual que los botones). Si usa botones destacados (botones más grandes y llamativos), vaya a `/src/pages/index.astro` y descomente la sección `Destacados`.
- **botones** -> Agrega más botones con la URL de tus redes sociales (ver las redes disponibles).
- **pie de página** -> Edite los derechos de autor y la URL del desarrollador (Hecho solo para usted 😎).

### IConos

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

Aquí está la lista de los servicios de hosting gratuitos más populares:
https://docs.astro.build/en/guides/deploy/

NOTA: Una vez desplegado, si tiene problemas agregue un archivo `.htaccess`. Copie todo este texto, peguelo en chatGPT y pida que le cree un archivo `.htaccess`

## Licencia

Distribuido bajo la licencia MIT. `Código abierto`.

<p align="right"><a href="#readme-top">Volver ⬆️</a></p>
