![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![StencilJS](https://img.shields.io/badge/StencilJS-DD0031?style=for-the-badge&logo=stencil&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)


<div id="top"></div>


<!-- PROJECT LOGO --> <br /> <div align="center"> <a href="#"> <img src="https://png.pngtree.com/png-clipart/20190705/original/pngtree-gallery-vector-icon-png-image_4279768.jpg" alt="Logo" height="80"> </a> <h1 align="center">StencilJS Image Gallery</h1> <p align="center"> A responsive and dynamic image gallery built with StencilJS. <br /> <a href="https://main--image-gallery-components.netlify.app/">View Demo</a> </p> </div> 

This project is an image gallery built using StencilJS Components.The gallery consists of three main components: the gallery container, individual image elements, and a popup for viewing images and specific details. The components are designed to be reusable, customizable, and responsive.

<img src="./img.png">


<h2>Components</h2>

<h3>Image Gallery Container</h3>

This component wraps the entire gallery and arranges the images in a grid layout.

<h3>Image Element</h3>
Each image in the gallery is an instance of this component. Clicking an image triggers the popup component.

<h3>Image Popup</h3>
This component displays a larger version of the selected image along with details when an image is clicked.

<img src="./img_1.png">

<br>

Built With
StencilJS
TypeScript
CSS3
Node.js
<p align="right">(<a href="#top">back to top</a>)</p>
<!-- GETTING STARTED -->
<h2>Getting Started</h2>

To get a local copy up and running, follow these steps.

Clone the repo

```
git clone https://github.com/your-username/image-gallery.git
```
Go to project folder

```
cd image-gallery
```
Install dependencies

```
npm install
```

Run the development server

```
npm start
```

Tree Structure

```
image-gallery
|   .editorconfig
│   .gitignore
│   .prettierrc.json
│   LICENSE
│   package-lock.json
│   package.json
│   tsconfig.json
│   readme.md
│   stencil.config.ts
├───src
│    ├───components
│    │   ├───image-gallery
│    │   │       image-gallery.tsx
│    │   │       image-gallery.css
│    │   ├───image-element
│    │   │       image-element.tsx
│    │   │       image-element.css
│    │   └───image-popup
│    │           image-popup.tsx
│    │           image-popup.css
│    ├───assets
│    ├───global
│    ├───utils
│    ├───_redirects
│    ├───components.d.ts
│    ├───index.html
│    ├───index.ts
│
├───assets
```

<p align="right">(<a href="#top">back to top</a>)</p>
