---
theme: default
background: /background.jpg
class: 'text-center'
highlighter: shiki
lineNumbers: false
titleTemplate: '%s - WCMGA 2023'
info: |
  ## WCMGA 2023
drawings:
  persist: false
css: unocss
colorSchema: both
author: Herald Flores - Luis Lopez
keywords: WordPress, WCMGA
download: true
exportFilename: 'bloque-de-gutenberg-con-acf-wcmga-2023'
favicon: '/favicon.png'
fonts:
  sans: 'DM Sans'
---
<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>

<div class="max-w-2xl mx-auto backdrop-blur-md bg-gray-900/30 px-8 py-10 shadow-xl shadow-purple-950">
  <div class="font-sans font-extrabold tracking-tighter leading-none font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300">

# Mi primer bloque de Gutenberg con ACF
### Herald Flores & Luis López
  </div>
</div>

<div class="absolute bottom-0 left-0 w-full px-10 pb-6 flex gap-2 items-center opacity-70">
  <img
    class="w-10"
    src="/logo.png"
  />
  <h2 class="font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300">WordCamp Managua 2023</h2>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Sobre nosotros

<div class="max-w-full mx-auto grid gap-6 mb-6 lg:mb-16 grid-cols-2 pt-10">
  <v-clicks>
    <div class="card items-center bg-gray-50 rounded-xl flex dark:bg-slate-900 dark:border-gray-700">
      <img class="w-[43%] h-full object-cover rounded-xl sm:rounded-none sm:rounded-l-xl" src="/luis-lopez.jpeg" alt="Luis López Avatar">
      <div class="p-5">
        <h3 class="text-xl font-bold tracking-tight text-gray-900 dark:text-white">
          <a href="https://github.com/luisperalta182" class="hover:text-gray-300 dark:hover:text-gray-500">Luis López</a>
        </h3>
        <span class="text-gray-500 dark:text-gray-400">
          Software Engineer
        </span>
        <p class="mt-2 mb-4 font-light text-gray-500 dark:text-gray-400">
          Entusiasta del desarrollado Frontend y WordPress, actualmente Software Engineer en Nicasource.
        </p>
        <ul class="flex space-x-4 sm:mt-0 list-none">
          <li class="list-none">
            <a href="https://github.com/luisperalta182" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
              <mdi-github />
            </a>
          </li>
          <li  class="list-none">
            <a href="https://www.linkedin.com/in/luisperalta182/" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
              <mdi-linkedin />
            </a>
          </li>
          <li class="list-none">
            <a href="https://profiles.wordpress.org/luisperalta182/" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
              <mdi-wordpress />
            </a>
          </li>
          <li class="list-none">
            <a href="https://www.instagram.com/luisperalta182/" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
              <mdi-instagram />
            </a>
          </li>
        </ul>
      </div>
    </div>
    <div class="card items-center bg-gray-50 rounded-xl flex dark:bg-slate-900 dark:border-gray-700">
      <img class="w-[43%] h-full object-cover rounded-lg sm:rounded-none sm:rounded-l-xl" src="/herald-flores.jpg" alt="Herald Flores Avatar">
      <div class="p-5">
        <h3 class="text-lg font-bold tracking-tight text-gray-900 dark:text-white">
            <a href="https://github.com/Herald-Flores" class="hover:text-gray-300 dark:hover:text-gray-500">Herald Flores</a>
        </h3>
        <span class="text-gray-500 dark:text-gray-400">
          Web Developer & Recruiter
        </span>
        <p class="mt-2 mb-4 font-light text-gray-500 dark:text-gray-400">
          Entusiasta del desarrollo, apasionado por el aprendizaje continuo y dedicado principalmente al desarrollo web.
        </p>
        <ul class="flex space-x-4 sm:mt-0 list-none">
          <li class="list-none">
            <a href="https://github.com/Herald-Flores" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
              <mdi-github />
            </a>
          </li>
          <li  class="list-none">
            <a href="https://www.linkedin.com/in/herald-flores/" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
              <mdi-linkedin />
            </a>
          </li>
          <li class="list-none">
            <a href="https://profiles.wordpress.org/heraldflores/" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
              <mdi-wordpress />
            </a>
          </li>
          <li class="list-none">
            <a href="https://www.instagram.com/heraldfloresdev/" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
              <mdi-instagram />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </v-clicks> 
</div>

<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>
<div class="absolute bottom-0 left-0 w-full px-10 pt-4 pb-6 flex gap-2 items-center opacity-90 bg-black/40">
  <img
    class="w-10"
    src="/logo.png"
  />
  <h2 class="font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300">
    WordCamp Managua 2023
  </h2>
</div>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
 @apply font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300;
}

.card{
  box-shadow: 5px 5px rgb(231 228 129 / 40%), 10px 10px rgb(227 229 127 / 31%), 15px 15px rgb(239 241 79 / 35%), 20px 20px rgb(187 168 67 / 10%), 25px 25px rgb(113 129 31 / 22%); box-shadow: 5px 5px rgba(0, 98, 90, 0.4), 10px 10px rgba(0, 98, 90, 0.3), 15px 15px rgba(0, 98, 90, 0.2), 20px 20px rgba(0, 98, 90, 0.1), 25px 25px rgba(0, 98, 90, 0.05);
}
</style>

---

# Qué es Gutenberg


<div class="grid max-w-screen-2xl px-4 py-8 mx-auto lg:gap-8 lg:py-10 lg:grid-cols-12">
<div class="mr-auto place-self-center lg:col-span-5">
<v-clicks>

- **Editor de Bloques**
- **Bloques Reutilizables**
- **Mayor Flexibilidad**
- **Interfaz de Arrastrar y Soltar**
- **Bloques Predeterminados**
</v-clicks>
</div>
<div class="hidden lg:mt-0 lg:col-span-7 lg:flex min-h-full">
  <img src="/gutenberg.png" alt="gutenberg editor" class="w-full h-full lg:min-h-60 object-cover object-left img-shadow">
</div>                
</div>

<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>
<div class="absolute bottom-0 left-0 w-full px-10 pt-4 pb-6 flex gap-2 items-center opacity-90 bg-black/40">
  <img
    class="w-10"
    src="/logo.png"
  />
  <h2 class="font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300">
    WordCamp Managua 2023
  </h2>
</div>

<!--
The last comment block of each slide will be treated as slide notes.
-->
<style>
h1 {
 @apply font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300;
}
.img-shadow{
  box-shadow: 7px 7px 0px 0px #8b5cf6;
}
</style>
---

# Qué es Advanced Custom Fields *(ACF)*


<div class="grid max-w-screen-2xl px-4 py-8 mx-auto lg:gap-8 lg:py-10 lg:grid-cols-12">
<div class="mr-auto place-self-center lg:col-span-5">
<v-clicks>

- ACF es un popular plugin de WordPress para la creación de campos personalizados.
- Permite ampliar las funcionalidades de WordPress, incluyendo: custom fields, bloques, theme options, post types y taxonomías.

</v-clicks>
</div>
<div class="hidden lg:mt-0 lg:col-span-7 lg:flex min-h-full">
  <img src="/acf.png" alt="ACF" class="w-full h-full lg:min-h-60 object-cover object-left img-shadow">
</div>                
</div>

<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>
<div class="absolute bottom-0 left-0 w-full px-10 pt-4 pb-6 flex gap-2 items-center opacity-90 bg-black/40">
  <img
    class="w-10"
    src="/logo.png"
  />
  <h2 class="font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300">
    WordCamp Managua 2023
  </h2>
</div>

<!--
The last comment block of each slide will be treated as slide notes.
-->
<style>
h1 {
 @apply font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300;
}
.img-shadow{
  box-shadow: 7px 7px 0px 0px #8b5cf6;
}
</style>
---

# Introducción a los Bloques *(ACF)*


<div class="grid max-w-screen-2xl px-4 py-8 mx-auto lg:gap-8 lg:py-10 lg:grid-cols-12">
<div class="mr-auto place-self-center lg:col-span-6">
<v-clicks>

- Los Bloques ACF te permiten crear secciones personalizados en WordPress.
- Son secciones reutilizables.
- Tenemos una vista previa en tiempo real de cada bloque en el panel de administración.
- Brinda felicidad tanto a sus clientes como a nosotros.



</v-clicks>
</div>
<div class="hidden lg:mt-0 lg:col-span-6 lg:flex min-h-full">
  <img src="/block-acf-01.jpg" alt="ACF" class="w-full h-full lg:min-h-60 object-cover object-left img-shadow">
</div>                
</div>

<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>
<div class="absolute bottom-0 left-0 w-full px-10 pt-4 pb-6 flex gap-2 items-center opacity-90 bg-black/40">
  <img
    class="w-10"
    src="/logo.png"
  />
  <h2 class="font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300">
    WordCamp Managua 2023
  </h2>
</div>

<!--
The last comment block of each slide will be treated as slide notes.
-->
<style>
h1 {
 @apply font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300;
}
.img-shadow{
  box-shadow: 7px 7px 0px 0px #8b5cf6;
}
</style>
---

# Configuración del Entorno de Desarrollo


<div class="grid max-w-screen-2xl px-4 py-8 mx-auto lg:gap-8 lg:py-10 lg:grid-cols-12">
<div class="mr-auto place-self-center lg:col-span-6">
<v-clicks>

- Requisitos previos:
  - WordPress instalado y en funcionamiento.
  - Plugin ACF Pro instalado y activado.
  - Un editor de código (por ejemplo, Visual Studio Code).

- Decide si deseas incluir los Bloques ACF en tu tema o como un plugin independiente.

</v-clicks>
</div>
<div class="lg:col-span-6">

  <div  v-click="3">
  /theme-name <br>
	├── functions.php <br>
	└── /blocks <br>
		<span class="ml-8"></span>└── /hero <br>
				<span class="ml-16"></span>├── block.json <br>
				<span class="ml-16"></span>└── index.php <br>
  </div>
  <div v-click="4">
     /plugin-name <br>
      ├── index.php <br>
      └── /blocks <br>
        <span class="ml-8"></span>└── /hero <br>
          <span class="ml-16"></span>├── block.json <br>
          <span class="ml-16"></span>└── index.php <br>
  </div>
</div>                
</div>

<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>
<div class="absolute bottom-0 left-0 w-full px-10 pt-4 pb-6 flex gap-2 items-center opacity-90">
  <img
    class="w-10"
    src="/logo.png"
  />
  <h2 class="font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300">
    WordCamp Managua 2023
  </h2>
</div>

<!--
The last comment block of each slide will be treated as slide notes.
-->
<style>
h1 {
 @apply font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300;
}
.img-shadow{
  box-shadow: 7px 7px 0px 0px #8b5cf6;
}
</style>
---


# Creemos un bloque con ACF

Registramos nuestro bloque:

<v-clicks>

```ts {all|1|2-3|all}
add_action( 'init', 'register_acf_blocks' );
function register_acf_blocks() {
  register_block_type( __DIR__ . '/blocks/hero' );
}
```

```ts {all|1|2-3|all}
{
  "name": "acf/testimonial",
  "title": "Testimonial",
  "description": "A custom testimonial block that uses ACF fields.",
  "style": [ "file:./hero.css" ],
  "category": "formatting",
  "icon": "admin-comments",
  "keywords": ["testimonial", "quote"],
  "acf": {
    "mode": "preview",
    "renderTemplate": "testimonial.php"
  }
}
```

</v-clicks>


<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>
<div class="absolute bottom-0 left-0 w-full px-10 pt-4 pb-6 flex gap-2 items-center opacity-90">
  <img
    class="w-10"
    src="/logo.png"
  />
  <h2 class="font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300">
    WordCamp Managua 2023
  </h2>
</div>

<!--
The last comment block of each slide will be treated as slide notes.
-->
<style>
h1 {
 @apply font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300;
}
.img-shadow{
  box-shadow: 7px 7px 0px 0px #8b5cf6;
}
</style>
---

# Creemos nuestro template

<v-clicks>

```ts {all|1|2-3|all}
<div class="offer-data">
    <div class="about">
        <div class="title">
            <div class="inner">
                <h3 class="m-b-0"><a href="<?php the_field( 'url' ); ?>"><?php the_field( 'name' ); ?></a></h3>
                <?php the_field( 'description' ); ?>
            </div>
        </div>
        <div class="price">
            <div class="inner">
                <span class="smaller">FROM</span> <?php the_field( 'price' ); ?> EUR
            </div>
        </div>
    </div>
</div>
```

</v-clicks>


<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>
<div class="absolute bottom-0 left-0 w-full px-10 pt-4 pb-6 flex gap-2 items-center opacity-90">
  <img
    class="w-10"
    src="/logo.png"
  />
  <h2 class="font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300">
    WordCamp Managua 2023
  </h2>
</div>

<!--
The last comment block of each slide will be treated as slide notes.
-->
<style>
h1 {
 @apply font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300;
}
.img-shadow{
  box-shadow: 7px 7px 0px 0px #8b5cf6;
}
</style>
---

# Creado con Slidev

[Documentations](https://sli.dev) 
