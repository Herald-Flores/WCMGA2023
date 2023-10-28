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
          Desarrollador Frontend, apasionado por el aprendizaje continuo. Actualmente reclutador y desarrollador en Boombit.
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
		<span class="ml-8"></span>└── /testimonials <br>
				<span class="ml-16"></span>├── block.json <br>
				<span class="ml-16"></span>└── index.php <br>
  </div>
  <div v-click="4">
     /plugin-name <br>
      ├── index.php <br>
      └── /blocks <br>
        <span class="ml-8"></span>└── /testimonials <br>
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

<h4 class="font-bold text-gray-500 dark:text-emerald-100">Registramos nuestro bloque:</h4>

<div class="w-full grid grid-cols-12 grid-rows-3 gap-2">
<div className="col-span-6">
<v-clicks>

```ts {all|1|2|3|4|all}
add_action( 'init', 'register_acf_blocks' ); // action hook to register ACF blocks
function register_acf_blocks() {
  register_block_type( __DIR__ . '/blocks/testimonial' ); // file path to block type register
}
```
</v-clicks>
</div>
<div className="col-span-6 -mt-8 row-span-2 col-start-1 row-start-2">
<v-clicks>

```ts {all|1|2|3|4|5|6|7|8|9|10|11|all}
{
  "name": "testimonial",
  "title": "Testimonial",
  "description": "Custom testimonial block",
  "style": [ "file:./testimonial.css" ],
  "category": "formatting",
  "icon": "admin-comments",
  "keywords": ["testimonial", "acf", "custom"],
  "acf": {
    "mode": "preview",
    "renderTemplate": "testimonial.php"
  }
}
```
</v-clicks>
</div>
<div className="col-span-6 -mt-5 row-span-3 col-start-7 row-start-1">
<v-clicks>

```ts {all|1|2|3|4-10|12|all}
acf_register_block_type(
	array(
		'name'              => 'hero-image',
		'title'             => __( 'Hero Image Block', 'wcmga23' ),
		'description'       => __( 'hero custom block', 'wcmga23' ),
		'render_template'   => dirname( __file__ ) . '/template/hero-image/index.php',
		'category'          => 'formating', // formatting
		'icon'              => array(
			'background' => '#000000',
			'foreground' => '#ffffff',
			'src'        => 'cover-image',
		),
		'keywords'          => array( 'hero image', 'custom' ),
		'mode'              => 'preview',
		'align'             => 'full',
		'supports'          => array( 'wide', 'full' ),
		'example'           => array(
			'attributes' => array(
				'mode' => 'preview',
			),
		),)
  );
```
</v-clicks>
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

<h4 class="font-bold text-gray-500 dark:text-emerald-100">Registramos nuestras Categorias:</h4>


<v-clicks>

```ts {all|1|2|3|4-10|12|all}
function wcmga_block_category( $categories, $post ) {
  return array_merge(
    $categories,
    array(
      array(
        'slug'  => "wcmga2023-blocks",
        'title' => esc_html__( 'WCMGA Blocks', 'wcmga23' ),
      ),
    )
  );
}
add_filter( 'block_categories', 'wcmga_block_category', 10, 2 ); // block_categories acf hook
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


# Registramos nuestros custom fields

<h4 class="font-bold text-gray-500 dark:text-emerald-100">Agregamos los campos personalizados para nuestro bloque:</h4>

<div className="grid grid-cols-4 grid-rows-1 gap-6 py-6">
  <div className="col-span-2">
    <v-clicks>
      <img src="/acf-field-group.png" alt="ACF Group" class="w-full h-full lg:min-h-60 object-cover object-left img-shadow">
    </v-clicks>
  </div>
  <div className="col-span-2 col-start-3 py-8">
    <v-clicks>
      <img src="/acf-block-field-02.png" alt="ACF Field" class="w-full h-full lg:min-h-60 object-cover object-left img-shadow">
    </v-clicks>  
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

# Creemos nuestro template HTML

<v-clicks>

```html {all}
<section>
  <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-6">
    <div class="mx-auto max-w-screen-sm">
      <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Testimonials</h2>
      <p class="mb-8 font-light text-gray-500 lg:mb-16 sm:text-xl dark:text-gray-400">
        El WordCamp Managua 2023 es un evento genial organizado por la comunidad de WordPress Nicaragua.
      </p>
    </div> 
    <div class="grid mb-8 lg:mb-12 lg:grid-cols-2">
      <figure class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-b border-gray-200 md:p-12 lg:border-r dark:bg-gray-800 dark:border-gray-700">
        <blockquote class="mx-auto mb-8 max-w-2xl text-gray-500 dark:text-gray-400">
          <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Un Evento de Tecnología creado con amor</h3>
          <p class="my-4">"Me gusta formar parte de la comunidad de WordPress Nicaragua. El WordCamp Managua 2023 demuestra que el querer es poder. Gracias comunidad por el apoyo para este maravilloso evento!"</p>
        </blockquote>
        <figcaption class="flex justify-center items-center space-x-3">
          <img class="w-9 h-9 rounded-full" src="/herald-flores.jpg" alt="Herald Flores profile picture">
          <div class="space-y-0.5 font-medium dark:text-white text-left">
            <div>Herald Flores</div>
            <div class="text-sm font-light text-gray-500 dark:text-gray-400">Developer and Recruiter at Boombit</div>
          </div>
        </figcaption>    
      </figure>
    </div>
  </div>
</section>
```

</v-clicks>


<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
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

# Agregamos la información dinámica

<v-clicks>

```php {all|5|8|11|13|16|19|21|all}
<section>
  <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-6">
    <div class="mx-auto max-w-screen-sm">
      <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">
        <?php the_field( 'block_title' ); ?>
      </h2>
      <p class="mb-8 font-light text-gray-500 lg:mb-16 sm:text-xl dark:text-gray-400">
        <?php the_field( 'block_description' ); ?>
      </p>
    </div> 
    <?php if( have_rows( 'testimonial_list' ) ): ?>
    <div class="grid mb-8 lg:mb-12 lg:grid-cols-2">
      <?php while( have_rows( 'testimonial_list' ) ) : the_row(); ?>
        <figure class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-b border-gray-200 md:p-12 lg:border-r dark:bg-gray-800 dark:border-gray-700">
          <blockquote class="mx-auto mb-8 max-w-2xl text-gray-500 dark:text-gray-400">
            <h3 class="text-lg font-semibold text-gray-900 dark:text-white"><?php the_sub_field( 'title_testimonial' ); ?></h3>
          </blockquote> 
        </figure>
      <?php endwhile; ?>
    </div>
    <?php endif; ?>
  </div>
</section>
```
</v-clicks>


<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
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

# Recursos Adicionales

<br>

<v-clicks>

- [ACF Documentation](https://www.advancedcustomfields.com/resources/blocks/)
- [GitHub Repository Plugin Example](https://github.com/Herald-Flores/ACF-block-WCMGA23)
- [Local WP](https://localwp.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [WordCamp Managua 2023](https://managua.wordcamp.org/2023/)

</v-clicks>


<div class="absolute top-32 right-16 opacity-90">
  <img
    class="w-40"
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
</style>
---

# Gracias por su atención

<div class="max-w-xl mx-auto flex items-center justify-center mt-16 dark:bg-slate-900">
  <div class="p-1 rounded shadow-lg bg-gradient-to-r from-purple-500 via-green-500 to-blue-500">
    <div class="flex flex-col items-center p-12 space-y-2 bg-slate-900">
      <h1 class="text-4xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-blue-500 to-purple-500">
        Thank You!
      </h1>
      <p class="text-xl text-center">Hecho con amor para la comunidad de WordCamp Managua 2023.</p>
    </div>
  </div>
</div>


<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>

<!--
The last comment block of each slide will be treated as slide notes.
-->
<style>
h1 {
 @apply font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300;
}
</style>
---


# Creado con Slidev

<br >
<br >

[Documentations](https://sli.dev) 

<div class="absolute top-10 right-10 opacity-90">
  <img
    class="w-16"
    src="/wappu.png"
  >
</div>

<style>
h1 {
 @apply font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-emerald-200 via-indigo-300 to-purple-300;
}
</style>
