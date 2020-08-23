<h1 align="center"> Atomic Design
</h1>

## Sobre

Curso de arquitetura "Atomic design" da plataforma [Alura](https://rocketseat.com.br/)

## Estrutura das Pastas

A primeira pasta a ser criada é a **"assets"**, onde geralmente colocamos todos os arquivos estáticos, como arquivos CSS, imagens, arquivos JavaScript, ícones, fontes e dentro dela encontraremos subpastas especificando cada conteúdo, como **"css"**, referente aos arquivos de estilo, e **"img"**, referente às imagens do projeto, normalmente utilizamos uma pasta chamada **"js"** para arquivos JavaScript.

### reset.css e normalize.css

Temos também importados o **"normalize.css"** e o **"reset.css"**, ambos presentes na pasta "assets/css", que são arquivos para remover as configurações que já vem por padrão dos navegadores e para que desse modo podemos estilizar nossas páginas totalmente do zero.

## BEM - Block Element Modifier

O **Block Element Modifier** ou **BEM**, é um metodologia, um padrão de nomeclaturas que utilizamos para que nosso projeto fique mais legível e simples para o entedimento. Tem como objetivo manter os projetos limpos e com facilidade principalmente em sua manutenção, para que qualquer desenvolvedor possa com facilidade manusear o projeto.

### Sintaxe

```sh

  - bloco
  - bloco__elemento
  - bloco__elemento--modificador ou bloco--modificador
  
  ```
