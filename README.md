# basicWeb :globe_with_meridians:
Coleção útil de trechos para o uso cotidiano de aplicações Web

# Elementos

###### BLOCK :x:
Permitem o redimensionamento tanto da largura quanto de sua altura. Estes, no entanto, não permitem elementos vizinhos, pois "ocupam" toda a largura da linha em que estão inseridos. 

###### INLINE :o:
Não permitem a definição nem da largura e nem da altura e permitem a exibição de outros elementos ao seu lado.

###### INLINE-BLOCK :x::o:
São a mistura entre inline e block. Elementos que tenham essa definição permitem que outros elementos sejam definidos ao seu lado, e permitem o redimensionamento tanto da largura quanto de sua altura.

# Bootstrap

> Media queries 

###### Tipos de mídias:

- all – todos os dispositivos
- aural – sintetizadores de voz
- braille – leitores de Braille
- embossed – impressoras de Braille
- handheld – dispositivos de mão. Por exemplo: celulares com telas pequenas.
- print – impressoras convencionais
- projection – apresentações de slides
- screen – monitores coloridas
- tty – teleimpressores e terminais
- tv – televisores

###### Exemplo de utilização

< link rel="stylesheet" media="print" href="print.css" />

###### Exemplo de resolução de telas

- 320 pixels – Smartphones no modo retrato.
- 480 pixels – Smartphones no modo paisagem.
- 600 pixels – Tablets pequenos. Ex: Amazon Kindle (600×800)
- 768 pixels – Tablets maiores em modo retrato. Ex: iPad (768×1024)
- 1024 pixels – Tablets maiores em modo paisagem, monitores antigos.
- 1200 pixels – Monitores wide.

[Links sistema de grid](http://getbootstrap.com/css/#grid)

**Exemplo de utilização media queries**

@media screen and (max-width: 767px) {

}

[Link do recurso respond.js](https://cdnjs.com/libraries/respond.js/)

# javaScript

###### Eventos - mouse


- **onclick** - acionado no clique do mouse
- **ondblclick** - acionado no clique duplo do mouse
- **onmousedown** - acionado no clique do mouse (soltando ou não o botão)
- **onmouseover** - acionado quando cursor do mouse sobrepõe o elemento o elemento da página
- **onmouseout** - acionado quando o cursor do mouse sai da área de um elemeto da página
- **onclick** - acionado no clique do mouse.
- **ondblclick** - acionado no clique duplo do mouse.
- **onmousedown** - acionado no clique do mouse (soltando ou não o botão).
- **onmouseover** - acionado quando cursor do mouse sobrepõe o elemento o elemento da página.
- **onmouseout** - acionado quando o cursor do mouse sai da área de um elemeto da página.


###### Eventos - teclado


- **onkeydown** - acionado no momento em que uma tecla é pressionada (soltando ou não a tecla).
- **onkeypress** - acionado no momento em que uma tecla é pressionada (soltando ou não), porém não captura todas as teclas, como por exemplo: alt, ctrl, esc, shift etc.
- **onkeyup** - acionada no momento em que a tecla é liberada


###### Eventos - janela


- **onload** - acionado quando a página finaliza o carregamento
- **onresize** - acionado quando a página ou frame é redimensionado


###### Eventos - formulários


- **onfocus** - acionado quando o elemento recebe o foco do cursor
- **onblur** - acionado quando o elemento perde o foco do cursor.
- **onchange** - acionado quando o estado do elemento é modificado
