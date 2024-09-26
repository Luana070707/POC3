# Media Queries no CSS

<p align="center">Este repositório demonstra como utilizar media queries no CSS para criar layouts responsivos e adaptáveis a diferentes dispositivos e situações, como impressão, tamanho de tela (smartphone, tablet, desktop) e orientação. :page_facing_up: </p>

## Conceitos Explorados :mag:: 

- *Media Queries para a impressão*: Ajustes específicos para quando o conteúdo é impresso.
- *Larguras de Dispositivos*: Layouts adaptáveis para smartphones, tablets e desktops, com breakpoints adequados.
- *Orientação dos Dispositivos*: Alterações baseadas na orientação de tela, seja em modo retrato ou paisagem.

## Veja alguns exemplos desses conceitos: :bulb: 

1. `Print` :printer: : Ajuste de layout para melhorar a versão impressa, ocultando elementos como menus, rodapés e dividindo textos com colunas.

 ```
   @media print {
  body {
    font-size: 12px;
  }
  nav, footer {
    display: none; /* Ocultar navegação e rodapé na impressão */
  }
  article {
    column-count: 2; /* Exibir o conteúdo principal em duas colunas */
  }
}
```

2. `Smartphones, Tablets e Desktops` :iphone: :desktop_computer: : Criação de breakpoints para diferentes larguras e dispositivos.

```
@media print {
  body {
    font-size: 12px;
  }
  nav, footer {
    display: none; /* Ocultar navegação e rodapé na impressão */
  }
  article {
    column-count: 2; /* Exibir o conteúdo principal em duas colunas */
  }
}
```

3. `Disposição dos Dispositivos` :arrows_clockwise: : Adaptação da interface para as orientações dos dispositivos.

```
/* Modo retrato (portrait) */
@media (orientation: portrait) {
  header {
    font-size: 24px;
  }
  .menu {
    display: block; /* Exibir menu no modo retrato */
  }
}

/* Modo paisagem (landscape) */
@media (orientation: landscape) {
  header {
    font-size: 32px;
  }
  .gallery {
    grid-template-columns: repeat(4, 1fr); /* Mais colunas na galeria no modo paisagem */
  }
}
```

## Conclusão. :checkered_flag:

Média Queries são uma ferramenta poderosa para criar layouts responsivos e adaptáveis, proporcionando uma melhor experiência do usuário em diferentes dispositivos e situações. 



   


   
 
