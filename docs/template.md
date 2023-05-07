# Template padrão do site

Layout padrão do site (HTML e CSS) que será utilizado em todas as páginas com a definição de identidade visual, aspectos de responsividade e iconografia.

Explique as guias de estilo utilizadas no seu projeto.

## Design

## Header
<div align="center">

### Cabeçalho Desktop
![Wireframe Destinos em MG](img/cabecalho-desktop.png)  

### Cabeçalho Desktop
![Wireframe Destinos em MG](img/cabecalho-mobile.png)

</div>  

<details>
  <summary>Header HTML</summary>

 ```html
<header class="header">
    <!--Logo -->
    <div class="logo">
        <img src="imagens/logo.png">
    </div>
    <!--Logo -->
    <!--Cabeçalho-->
    <div class="navigation-bar">
        <ul class="nav">
              <li>
                <a href="#">Sobre Nós</a>
              </li>
              <li>
                <a href="#">Transporte seu Pet</a>
              </li>
              <li>
                <a href="index.html"><i class="fa-solid fa-house"></i></a>
              </li>
              <li>
                <a href="#">Destinos em MG</a>
              </li>
              <li>
                <a href="#">Entre</a>
              </li>
        </ul>
    </div>
    <!--Cabeçalho-->
     <!--Responsive Navbars-->
     <div class="responsive-navbar">
      <div class="collapse" id="navbarToggleExternalContent">
        <div class="p-4" style="background-color: #8cd4c8;">
          <h5 class="text-white h4">Meu Pet Viaja</h5>
          <ul class="nav-responsive">
            <li>
              <a href="index.html">Home</a>
            </li>
            <li>
              <a href="#">Sobre Nós</a>
            </li>
            <li>
              <a href="#">Transporte seu Pet</a>
            </li>
            <li>
              <a href="#">Destinos em MG</a>
            </li>
            <li>
              <a href="#">Entre</a>
            </li>
      </ul>
        </div>
      </div>
      <nav class="navbar-responsive navbar-dark bg-dark">
        <div class="container-fluid">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
        </div>
      </nav>
     </div>
</header>

 ```
</details>

<details>
  <summary>Header CSS</summary>

  ```css
.logo{
    display: flex;
    justify-content: center;
    margin-top: 2rem;
}

.logo img{

    max-width: 350px;
    min-width: 250px;
   
}

.navbar{
    display: block;
    margin-left: auto;
    margin-right: auto;
}

.navigation-bar{
    display: flex;
    justify-content: center;
    margin-top: 2rem;
    margin-bottom: 2rem;

}

.navbar ul li
{
    align-self: center;
    list-style: none;
    margin-top: -50px;

}

.nav {
    width: 750px;
    display: flex;
    justify-content: space-around;
    flex-direction: row;
    margin-right: 55px;
}

.nav li a{
    border-radius: 25px;
    transition: 0.3s;
    color: black;
}

.nav li a:hover{
   padding-left: 25px;
   padding-right: 25px;
    color: white;
    background-color: cadetblue !important;
    cursor: pointer;
    border-radius: 25px;
    transition: 0.3s;
}

.responsive-navbar{
  display: none;
}
/**Navbar*/
```
</details>
--------------------------------------------------------------------------------------------------------------------------------------------------
## Cores

A paleta de cores do projeto é composta das seguintes cores:

![COLOR PALETTE (1)](https://user-images.githubusercontent.com/116188910/236004081-c197b787-c1d4-450d-8051-196e3966c5b1.png)

Sendo as cores #00977B2, #4ECDC4 e #15EEA3, as cores presentes na logo e as cores que dão personalidade e estão em maior destaque no site. Já as cores #FFFFFF e #000000 são as cores utilizadas para dar contraste e, em especial, a segunda será utlizada no corpo do texto do site.

## Tipografia

Apresente as fontes que serão utilizadas e sua função no site. As principais funções são: Título de página, Título de Seção, Rótulos de componentes e Corpo de Texto.


## Iconografia

Defina os ícones que serão utilizados e suas respectivas funções.

Apresente os estilos CSS criados para cada um dos elementos apresentados.
Outras seções podem ser adicionadas neste documento para apresentar padrões de componentes, de menus, etc.


> **Links Úteis**:
>
> -  [Como criar um guia de estilo de design da Web](https://edrodrigues.com.br/blog/como-criar-um-guia-de-estilo-de-design-da-web/#)
> - [CSS Website Layout (W3Schools)](https://www.w3schools.com/css/css_website_layout.asp)
> - [Website Page Layouts](http://www.cellbiol.com/bioinformatics_web_development/chapter-3-your-first-web-page-learning-html-and-css/website-page-layouts/)
> - [Perfect Liquid Layout](https://matthewjamestaylor.com/perfect-liquid-layouts)
> - [How and Why Icons Improve Your Web Design](https://usabilla.com/blog/how-and-why-icons-improve-you-web-design/)
