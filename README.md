# SEO Website

## Visão Geral

### Projeto que simula um Website que oferece ferramentas e soluções para melhorar o SEO de empresas na internet.
#

![](./Assets/images/seo-website.png)

#
## Construido com:
- HTML
- CSS / SASS
- JavaScript

#
## Funcionalidades
- Web site que oferece ferramentas e soluções para melhorar o SEO de empresas na internet. 
- Design responsivo, que se adapta a vários tamanhos de tela. 
- Botão para alterar tema da página claro/escuro.

## O que eu aprendi:
- Boas práticas com JavaScript

- Manipulação do DOM com:
```js
  document.querySelector('.main-container')
  document.querySelectorAll('.btn')
  document.getElementById('submit')
```
- Eventos na página
```js
  themeBtn.onclick = () => {
   themeBtn.classList.toggle('fa-sun')

   if (themeBtn.classList.contains('fa-sun')) {
      document.body.classList.add('active')
   } else {
      document.body.classList.remove('active')
   }
}

window.onscroll = () => {
   menu.classList.remove('fa-times')
   navbar.classList.remove('active')

   let maxHeight = window.document.body.scrollHeight - window.innerHeight
   let percentage = (window.scrollY / maxHeight) * 100
   document.querySelector('.header .scroll-indicator').style.width = percentage + '%'
}
```

#
## Link

Veja o projeto aqui: [Acessar 🌏](https://devhiderlan.github.io/seo-website/)

## Autor

Hiderlan Santana: [Linkedin](https://www.linkedin.com/in/hiderlan-santana/)