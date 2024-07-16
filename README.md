<a id="readme-top"></a>

<h1 align="center">Free Link Tree</h1>

<div align="center">

![Astro](https://img.shields.io/badge/Astro-0C1222?style=for-the-badge&logo=astro&logoColor=FDFDFE)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

### Prerequisites

- **Node.js** -> `v18.17.1` or `v20.3.0` or higher. (`v19` is not supported)
- **Visual Studio Code** -> with the [Official Astro Extension](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode).

Personally I prefer using `pnpm` instead `npm` and to install it you can use:

```sh
npm install -g pnpm
```

### Installation

1. Clone this repo to your computer:
   ```sh
   git clone https://github.com/alexjamesmx/link-tree.git
   ```
2. Change directory into the project & Install dependencies:
   ```sh
   cd link-tree
   pnpm install
   ```
3. Run the dev server:
   ```sh
   pnpm dev
   ```

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>

## JSON

The best part of this link tree is that you can modify every aspect of the website very easily, you just have to edit the `index.json` file. This JSON contains the following sections:

- **html** -> Edit language, title, description and favicon (replace it in `/public`).
- **background** -> Use the same color twice for a solid color or use two colors for a gradient color.
- **header** -> Edit your image (replace it in `/public`), name and description.
- **socials** -> Add more icons with your socials URL (see the networks available).
- **featured** -> Highlight links with a background image or color (same as buttons). If you use featured, go to `/src/pages/index.astro` and uncomment the `Featured` section.
- **buttons** -> Add more buttons with your socials URL (see the networks available).
- **footer** -> Edit the copyright and URL of the developer (Made just for you 😎).

### Icons

Just edit the key `network` with any of the following values (case-sensitive):

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
> If you need more open-source icons, visit: [Tabler Icons](https://tabler.io/icons)

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>

## License

Distributed under the MIT License. `Open Source`.

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>
