# shorthand-CSS
shorthand CSS
Segunda a W3C há duas formas de escrever a mesma regra de CSS: a padrão e a shorthand. Uma é a longa e a outra é a reduzida.

##Alguns exemplos de Shorthand

###background
- background-color: #000;
- background-image: url(images/bg.gif);
- background-repeat: no-repeat;
- background-position: top right;

###background shorthand
- background: #000 url(images/bg.gif) no-repeat top right;

###font
- font-style : italic ; 
- font-weight : bold ; 
- font-size :  1em ; 
- line-height :  1% ; 
- font-family : Arial, sans-serif ;


###font shorthand
- font: italic bold .8em/1.2 Arial, sans-serif;

###border
- border-width: 1px;
- border-style: solid;
- border-color: #000;

###border Shorthand
- border: 1px solid #000;

###margin 
- margin-top: 10px;
- margin-right: 5px;
- margin-bottom: 10px;
- margin-left: 5px;

###margin Shorthand
- margin: 10px 5px 10px 5px;
*Note que os valores estão em ordem no sentido horário, de cima: top, right, botton e left*

###padding
- padding-top: 10px;
- padding-right: 5px;
- padding-bottom: 10px;
- padding-left: 5px;

###padding Shorthand
- padding: 10px 5px 10px 5px;