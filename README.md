# shorthand-CSS
shorthand CSS
Segunda a W3C há duas formas de escrever a mesma regra de CSS: a padrão e a shorthand. Uma é a longa e a outra é a reduzida.

##Alguns exemplos de Shorthand

###background
- background-color: #000;
- background-image: url(images/bg.gif);
- background-repeat: no-repeat;
- background-position: top right;
- background-attachment: fixed;

###background shorthand
- background: #000 url(images/bg.gif) no-repeat top right fixed;

###font
- font-weight: bold;
- font-style: italic;
- font-variant: small-caps;
- font-size: 1.5em;
- line-height: 200%;
- font-family: Georgia, "Times New Roman", serif;

###font shorthand
- font: bold italic small-caps 1.5em  200% Arial, Georgia, "Times New Roman", serif;

###border
- border-width: 1px;
- border-style: solid;
- border-color: #000;

###border Shorthand
- border-left: 1px solid black;
- border-right: 1px solid black;
- border-top: 1px solid black;
- border-bottom: 1px solid black;

###margin, padding
- margin-top: 10px;
- margin-right: 5px;
- margin-bottom: 10px;
- margin-left: 5px;

###margin, padding Shorthand
- margin: 10px 5px 10px 5px;
*Note que os valores estão em ordem no sentido horário, de cima: top, right, botton e left*

### outline
- outline-width: 3px
- outline-style: dotted;
- outline-color: gray;

###outline Shorthand
- outline:3px dotted gray;

###list
- list-style-type: circle;
- list-style-position: inside;
- list-style-image: url(bullet.gif);

###list Shorthand
- list-style: circle inside url(bullet.gif);

**THAT'S IT!** CSS Shorthand Generator [http://shrthnd.volume7.io/](http://shrthnd.volume7.io/)

