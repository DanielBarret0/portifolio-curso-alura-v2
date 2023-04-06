<div align="center">
<img align="center" src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/capa-projeto.png#vitrinedev">
</div>

# 🗒️ Sobre o projeto

| 🪧 Vitrine.Dev |  [Minha Vitrine Dev](https://cursos.alura.com.br/vitrinedev/danielbarreto)   |
| -------------  | --- |
| ✨: Nome        | Mini portifolio
| 🏷️ Tecnologias | <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  | 🎇: Bibliotecas |  [IcoMoon](https://icomoon.io/),[Gradiente Animado](https://www.gradient-animator.com/), [Scrollbar](https://www.cssportal.com/css-scrollbar-generator/).
| 🚀: URL         | [Mini Portfólio](https://portifolio-curso-alura.bohr.io/)
| :laughing: Extras feito     | **animação do background, Scroll Bar.**
<!-- Inserir imagem com a #vitrinedev ao final do link -->

# 🖼️ Banner do Projeto
<div align="center">

<img src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/banner-projeto.png">
</div>


# :relaxed: Minha experiência

  
  ## :zap: Primeiro desafio desse projeto: Usar medidas relativas no projeto
  O que é uma medida relativa?
  
  Essas são as que normalmente não estamos habituados. Essas medidas são calculadas tendo como base 
  uma outra unidade de medida definida, como por exemplo:

  **em** e o **rem**. O uso delas é mais apropriado para que possamos fazer ajustes em diferentes dispositivos garantindo um layout consistente e fluido em diversas mídia.
  
  [fonte: Alura | Confira o artigo aqui](https://www.alura.com.br/artigos/guia-de-unidades-no-css)
  
   ~~~CSS
 .conteudo__texto {
    font-family: var(--fonte-secundario);
    font-weight: 400;
    font-size: 1.5rem;
    color: var(--cinza);
    line-height: 2.25rem;
    padding: 2rem 0;
}
  ~~~
  
  <img align="center" src="https://engage-site-cms.s3.amazonaws.com/production/engage-interactive/cms/processed/8c0194fc81cc2ce455910deffaa9b879.png">

  ## :zap: Segundo Desafio: Imagem responsiva!
 Nesse projeto o desafio é somente mudar o tamanho da imagem com medida fixa para uma relativa no caso a porcentagem.
  
  ~~~CSS
.imagem {
    width: 50%;
}
  ~~~
  
  <img align="center" src="">
  
  
   ## :zap: Pagina Sobre e Curriculo
  Essas duas páginas tem conteúdo muito semelhante, então acabei aproveitando várias classes CSS usada em outras páginas e a solução em CSS foi a mesma. A uma pequena diferença que na página do Currículo utilizei uma lista não ordenada como mostro abaixo:
  
  ~~~HTML
    <h2 class="conteudo__titulo">Experiências</h2>

         <ul class="conteudo__lista">
             <li class="conteudo__item">Empresa tal (2020 - 2021) - fazia isso e aquilo</li>
             <li class="conteudo__item">Empresa tal (2020 - 2021) - fazia isso e aquilo</li>
             <li class="conteudo__item">Empresa tal (2020 - 2021) - fazia isso e aquilo</li>
         </ul>
  ~~~
  
  <img align="center" src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/3-gif-sobre-e-curriculo.gif">
 
   ## :zap: Rodape
  Usada em todas as paginas do projeto, o rodapé super simples de ser feito apenas com texto e um link personalizado com todo conteúdo centralizado. Abaixo minha solução:
  
 ~~~CSS
.rodape {
    padding: 2rem;
    background: var(--azul);
    text-align: center;
    font-family: var(--fonte-secundario);
    font-size: 1.5rem;
}

.rodape__link {
    text-decoration: none;
    text-transform: bold;
    color: black;
}

.rodape__link:hover {
    cursor: pointer;
    text-decoration: underline;
}
  ~~~
  
  
  <img align="center" src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/4-rodape-solucao.png">
  

# 🙋‍♂️ Autor

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/DanielBarret0/codeChella/blob/main/LICENSE.md)

José Daniel Aragão Barreto

Acesse o meu [LinkedIn](https://www.linkedin.com/in/daniel-barreto-1b763216a/)
 
