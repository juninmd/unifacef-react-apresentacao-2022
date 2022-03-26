---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# UniFacef

## Desenvolvimento FrontEnd (React JS)

Horários das aulas:

08h00 às 12h00 e das 13h00 às 17h00

Intervalos: 09h45 e 14h45

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
 Let's GO!
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/juninmd/unifacef-react-apresentacao-2022" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Quem sou eu?

Antonio Carlos

26 anos

Franca - SP

- 🧑‍💻 **Desenvolvedor Sênior** - 10 anos de experiência em programação
- 📝 **Formação** - Análise e desenvolvimentos de sistemas Na fatec, cursando atualmente Inteligência Artificial e Machine Learning
- 🎨 **Stack** - Atuo como Desenvolvedor FullStack, tendo mais foco em JavaScript.
- 🤹 **Linguagens Favoritas** - JavaScript, C#, Kotlin, Python e Java.
- 🎥 **Hobies** - Adoro Esportes, como tênis, beach tennis, volêi, skate.

<br>
<br>

Meu [github](https://github.com/juninmd?tab=repositories)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---

# O que vamos falar?

Iremos aprender a desenvolver aplicações Web utilizando React.

- 📝 **Código** - Muuuito JavaScript
- 🎨 **CSS** - O Básico para deixar aquela pagina estilosa
- 🧑‍💻 **Boas práticas** - Nada de gambiarras aqui em
- 🤹 **Apis** - Sempre vamos utilizar recursos disponíveis da net
- 📤 **Deploy** - Vamos aprender a publicar gratuitamente nossa app :D
- 🛠 **Ferramenta** - CRA / Webpack / TypeScript, o que são essas ferramentas?


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
class: text-center
---

# Leia Mais

[Repositório do Curso](https://github.com/juninmd/unifacef-react-2022)
[Projeto Final](https://github.com/juninmd/unifacef-react-typescript-2022)
