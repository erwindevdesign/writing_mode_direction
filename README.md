<a name="readme-top"></a>

<!-- Hero -->
<br />
<div align="center">
  <h2 align="center">Writing Language Direction</h2>
  <p align="center">
    CSS text properties [ direction: | writing-mode: | text-orientation: | @mixin | interpolation | inheritance ]
    <br />
  </p>
  <p align="center">
    <a href="https://drive.google.com/drive/folders/1Fwcq_oC_1mS3oNofnh2TNvJHiXW1BvjZ?usp=sharing"><strong>Download the mixins for sass »</strong></a>
    <br />
    <a href="https://github.com/erwindevdesign/writing_mode_direction">View Demo</a>
    ·
    <a href="https://github.com/erwindevdesign/writing_mode_direction/issues">Report Bug</a>
    ·
    <a href="https://github.com/erwindevdesign/writing_mode_direction/issues">Request Feature</a>
  </p>

  <br />
  <a href="#">
    <img src="https://drive.google.com/uc?export=view&id=1PLt33EOMgjh3Wjl5rxmwvt2WsrGMLphM" alt="img" width="100%" height="100%">
  </a>
  <br />
  <br />
</div>

<!-- table of contents -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

<h4 align="center">
Multilingual text display in accessibility-focused development.
</h4>

In a multicultural society, where multiple languages are prevalent and web accessibility is crucial, it becomes essential to address specific requirements for displaying text in accessibility-focused development. The primary objective is to ensure the utmost satisfaction in meeting users' language and communication needs.

To expedite development efforts, we can leverage CSS preprocessor utilities like Sass and utilize `@mixins`. These `@mixins` enable us to create reusable style specifications following the DRY (Don't Repeat Yourself) framework, which accelerates the implementation process by reusing code structures.

Within this repository, we will employ `@mixins` to facilitate the development of style specifications, including:

- Writing mode-direction: `@import "writing_components.sass"`
- Font size: `@import "responsive_fonts.sass"`

<!-- En una sociedad multicultural, la diversidad de lenguajes y la accecibilidad web crean necesidades espesificaas de visualización de la escritura en cualquier desarrollo enfocado a la accecibilidad, buscando alcanzar el mayor ratio de satisfacción de las necesidades de lenguaje y comunicación en los usuarios.

Haciendo uso de utilidades de preprocesadores CSS, como Sass, los @mixins nos permiten crear espesificasiones de estilos de visualización bajo el marco de trabajo DRY, el cual permite reutilizar estructuras de código que agilisen el desarrollo en el cual sea implementado.

En este repositorio haremos uso de @mixin que proporcionene al desarrollo de espesificaciones de estilos como:

- Reboot builds upon Normalize : @import "bootstrap_reboot.scss"
- Media Querys : @import "breakpoints.scss"
- Grid Template : @import "grids.scss"
- Writing mode-direction : @import "writing_components.sass"
- Font-size : @import "responsive_fonts.sass"

-->
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This project was created with the following technologies:

<br />
<div align="center">

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![Pug](https://img.shields.io/badge/Pug-FFF?style=for-the-badge&logo=pug&logoColor=A86454)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

</div>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To make use of the @mixins included in this template, you need to install the `Sass` preprocessor using the `npm` package manager of `Node.js`.

To get a local copy up and running, follow these simple example steps.

<!--
Para hacer uso de los @mixins implementados en este template se requiere la instalación del preprocesador `Sass` mediante el gestor de paquetes `npm` de `Node.js`. -->

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

Install a binary package via pkg:

```sh
  pkg install node
```

If you use Node.js, you can also install Sass using npm by running.

```sh
  npm install -g sass
```

### Installation

1. Download the @mixins Files in .sass Format. You can download the files containing the @mixins in .sass format from the following link:
<br />
<div align="center">
  <p align="center">
    <a href="https://drive.google.com/drive/folders/1Fwcq_oC_1mS3oNofnh2TNvJHiXW1BvjZ?usp=sharing"><strong>Download the mixins for sass »</strong></a>
    <br />
  </p>
</div>

2. Place the downloaded files in the `components` folder of your Sass project or wherever your code modularizations are hosted.

```sh
proyecto-web/
├── src/
│   ├── assets/
│   │   ├── images/
│   │   ├── fonts/
│   │   └── styles/
│   │       ├── components
│   │       │   ├── _writing_components.sass    <--
│   │       │   └── _responsive_fonts.sass      <--
│   │       └── main.scss
│   ├── views/
│   │   ├── includes/
│   │   │   ├── header.pug
│   │   │   └── footer.pug
│   │   ├── pages/
│   │   │   ├── index.pug
│   │   │   └── about.pug
│   │   └── layout.pug
│   ├── scripts/
│   │   └── main.js
│   └── index.pug
├── public/
├── .gitignore
└── LICENSE
```

3. Remember to push the changes to your Git branch. Never forget it! :wink:.

```sh
  git add .
```

<!--
1. Descarga los archivos que contienen los `@mixins` en formato `.sass` en el siguiente link:



2. Coloca los archivos descargados en la carpeta componentes de tu proyecto en Sass o donde se alojen la modularizaciones de tu código.

3. Agrega los cambios a tu rama de Git, `NUNCA` lo olvides :wink:.
 -->

<!--
1. Forking a repository. In the top-right corner of the project page, click Fork and follow the process to complete the fork.

2. Creating a branch to work on
  ```sh
   git branch feature
   git checkout feature
  ```

3. Cloning a fork and follow the process to complete the cloning.
  ```sh
   git clone https://github.com/erwindevdesign/writing_mode_direction.git
  ```
  -->

## Usage

1. Declare the @mixins in the _global.sass file. It is recommended to declare them at the beginning of the file.
<!-- 
1. Se declaran los `@mixins` en el archivo `_global.sass`, recomendable declararlos al inicio del archivo.
 -->
~~~scss
// _global.sass

@import "writing_components.sass";   //<--
@import "responsive_fonts.sass";     //<--

body
  ...
~~~

2. Style the text element that requires the @mixin using Sass with the following prefixes.
<!-- 
2. Al elemento texto al que se requiera implementar el `@mixin` se incluira en sus estilos en Sass con los siguientes prefijos.
 -->
~~~scss
.text
  @include writing(latin)
~~~
<div align="center">
  <a href="#">
    <img src="https://drive.google.com/uc?export=view&id=1Go6kYmGT4_VA63tsu6C7Sy8LjsZjxZmD" alt="img" width="350px" height="100%">
  </a>
  <br />
</div>

~~~scss
.text
  @include writing(arabe)
~~~
<div align="center">
  <a href="#">
    <img src="https://drive.google.com/uc?export=view&id=1D68OgyiypFR0BnelMKbCEjxG5PJ0Yuvz" alt="img" width="350px" height="100%">
  </a>
  <br />
</div>

~~~scss
.text
  @include writing(japanese)
~~~
<div align="center">
  <a href="#">
    <img src="https://drive.google.com/uc?export=view&id=1LrFpCSF5QPOaxYxxLiX6demGjM-kSymv" alt="img" width="350px" height="100%">
  </a>
  <br />
</div>

~~~scss
.text
    @include writing(chinese)
~~~
<div align="center">
  <a href="#">
    <img src="https://drive.google.com/uc?export=view&id=1gO77d7hIVjYRVMLZXpUTJ0FnHoMKmwsY" alt="img" width="350px" height="100%">
  </a>
  <br />
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [x] Create a Sass & Pug schema
- [x] Implement responsive breakpoints
- [x] Develop `@mixins`
- [x] Apply writing direction styles
- [x] Push changes to GitHub repository
- [x] Create detailed documentation
- [x] Create GitHub Pages
- [ ] Create instructions for cloning using sparse-checkout

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! **Thanks again!**

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License. See LICENSE file for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

@erwindevdesign - erwindevdesign@gmail.com

Project Link: https://github.com/erwindevdesign/writing_mode_direction

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

- [Gitignore file](https://www.toptal.com/developers/gitignore/)
- [Open source icons.](https://ionic.io/ionicons)
- [Google Fonts](https://fonts.google.com/)
- [Markdown Badges](https://github.com/Ileriayo/markdown-badges)
- [Contributing to projects by GitHub](https://docs.github.com/en/get-started/quickstart/contributing-to-projects?tool=webui)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br /><br /><br /><br />
<p align="center"><a href="#readme-top">@erwindevdesign</a></p>


<!--

## Habilidades

- HTML semantico
  * flexbox
  * grid

- CSS
    * breakpoints
    * movile first
    * responsive design

- Sass
    * Reboot Codes - normalize file
    * Breakpoints mixins
    * Grids mixins
    *
    * Modularización de bloques de codigo en unidades más reducidas, manejables y sostenibles.

- PUG
    * Herencia de esquemas HTML, definiendo un layout e importando estructuras desde otros archivos.
    * Modularización de bloques de codigo en unidades más reducidas, manejables y sostenibles.

- Git
    * git pages
    * github repository
    * gitignore file

- sales funnel call to action

-->
