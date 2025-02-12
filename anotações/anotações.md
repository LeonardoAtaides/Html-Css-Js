# Estruturas Principais de um site:
**1°** <html></html>
**2°** <head></head> *2.1* <meta></meta> *2.2* <title></title>
**3º** <body></body>

# Tags de Cabeçalho:
São utilizadas para formatações de textos
*Usada para definir Títulos* sendo 6 tamanhos de títulos
<h1>    <h2>   <h3>
<h4>    <h5>   <h6>

# Tags <br> e <hr>:
O <br> faz uma *quebra de linha*
O <hr> *Cria uma linha* na página

# A tag *<strong>* serve para deixa o texto em negrito
# A tag *<em>* serve para deixa o texto em itálico
# A tag *<u>* serve para deixa o texto em sublinhado
# A tag *<strike>* serve para deixa o texto riscado ao meio

# Listas

# Lista não ordenada: **<ul>**
- Dentro desta tag usa-se <li> para definir os itens
- onde não há uma ordem nos componentes da 
lista, sendo marcandos com *marcadores*
**Tipos de marcadores**
Usa-se a tag *type*:
- disc •
- circle ◦
- square  ■



# Lista ordenada **<ol>**
- Dentro desta tag usa-se <li> para definir os itens
- Segue uma ordem nos itens como ex: 1º, 2º e etc
**Tipos de marcadores**
Usa-se a tag *type*:
- 1 (1. 2. 3.)
- A ou a (A. B. C.)
- I ou i (I. II. III.)

# Inserir Imagens **<img>**
•Usa- se a <img> juntamente com  **src** e **alt**
- SRC onde busca a imagem
- ALT se a imagem não aparecer serve com descrição

# Âncoras/ Links **<a>**
• Usa-se para criar novas páginas ou abrir links externos
- Dentro da tag temos:
*href=""* que busca de onde e o link
*target""* que é como está página vai abrir

**tipos de target**
1º *_blank-* abre o link em uma nova aba
2° *_parent* abre no link pai,se não tiver abre ns mesma aba
3° *_top*abre o link na janela inteira
4º *_self* abre o link na mesma aba (comportamento padrão)

# Tabela **<table>**
• Usa-se para criar tabelas
- Dentro da tag temos:
*border=""*-- para definir a borda
*width="%"* -- para definir a largura da tabela
*<tr>* -- para definir as linhas da tabela
*<td>* -- para definir os dados da tabela
*<th>* -- é cabeçalho da tabela
*colspan = ""* -- agrupa as colunas da tabela
*rowsoan=""* -- agrupa as linhas da tabela
*border-collapse: separate;* -- separa as colunas da tabela
*border-collapse: collapse;* -- junta as colunas da tabela

*letter-spacing: 0px* -- Da espaçamento entre os caracteres

# Formulário **<form>**
• Usa-se para criar formulários
*action=""* envia para devido lugar os dados ex: action="processo.php"

- Dentro da tag temos:
*<input>* -- é um campo de digitação de dados
- *type=""*         

0 - **PlacaHolder** Deixa uma mensagem ao usário com o deve digitar e etc

1 - **Text** - texto

2 - **Passoword** - senha

3- **Button** - botão -- value(O valor/Atribui o nome que vai aparacer)

4- **Radio** - cria um botão de escolha redondo

5 - **Checkbox** -cria um quadrado de escolha(para escolha de +1 opção)
6 - **email** - não permite digitar o email sem o @

7 - **required** - exige que o campo seja preenchido antes de ser enviado

8 - **autofocus** - Destaca o campo a ser preenchido pelo usuário

9 - **number** - cria um input de escolha de números podendo aumentar ou diminuir, sendo possivel passar:
MÍNIMO:   |   MÁXIMO:  |   PULAR:   |
*min="0"* | *max="10"* | *step="2"* |

10 - **url** serve para colocar url, com https

11 - **Search** Serve para usuário realizar uma pesquisa

12 - **Range** E uma barra que aumenta e diminiu, sendo possivel:
MÍNIMO:   |   MÁXIMO:  | VALOR FIXO
*min="1"* | *max="3"*  | *value="2"*

13 - **Date** E uma barra que é possivel escolher uma data

14 - **Color** permite ao usuário escolher uma cor 

- *name=""* - nome --  serve para passar o dados 

*<select>* -- define uma "lista" de escolha
-Dentro dessa tag temos <option> -- para definir vuma opção

*<textarea>* -- cria uma área de digitação para o usuário

# Escrever caracteres especiais:
**HTML ENTIDADES**:
< -- name(&lt;)	number(&#60;)
> -- name(&gt;) number(&#62;)
& -- name(&amp;) number(&#38;)
" -- name(&quot;) number(&#34;)
para mais pesquisar = "html entities"

# CSS:
*Existe 3 formas de css*
**External style sheet** -- Arquivo fora ex: pag.css(sendo necessário linkar)
# <link rel="stylesheet" href="pag.css">
**Internal style sheet** -- Estilo dentro do código
# <style> type="text/css"> </style>
**Inline style** -- Coloca o estilo dentro da linha com tag *style=""*
# <p style="color: red;">

# Classes e ID:
Classe - Identifica mais de um elemento
ID - identifica um elemento especifico dentro do código


# Divs e Span:
Div -- divisão cria um bloco de elementos
Span -- sendo mais usada para estilizar textos(deixando um do lado do outro)

# Estilos de bordas:
*solid* -- cria uma borda padrão
*dashed* -- cria uma borda fragmentada em retângulos
*dotted* -- cria uma borda fragmentada em bolinhas
*double* -- cria uma borda dupla
*groove* -- cria uma borda com sombra interna
*ridge* -- cria uma borda com sobra externa
*inset*/*outset* -- cria uma borda 3d com "degrade"
*none* -- não cria uma borda

# Color:
Usa-se no CSS para definir uma cor
*color*: red;
=================================================
# Font Family:
Usa-se no CSS para definir uma fonte dos textos
*font-family:* Arial, Helvetica, sans-serif;
=================================================
# Font-size
Usa-se no CSS para definir os tamanhos dos textos
*font-size:* 20px;
**medidas**
*px* -> tamanho fixo
*%* -> tamanho relativo
*em* -> tamanho relativo ao conteiner pai
=================================================
# font-weight
Usa-se para deixar o texto em 
*font-weight:* bold; bolder; 100 a 900;
=================================================
# font-style
Usa-se para denifir um estilo de fonte
*font-style:* italic; normal:
=================================================
#  text-decoration
Usa-se para fazer uma sublinhar o texto

*text-decoration:* underline; overline; line-through;
=================================================
# Background-Image
Usa-se para inserir uma imagem de fundo
**Usa URL para localizar a imagem**
*background-image: url('imgs/yoshi.png');*
#  Background-repeat
Usa-se para definir a repetição da imagem de fundo
*Background-repeat:* background-repeat; repeat x e y;
# Background-attachment:
Usa-se para definir a rolagem da imagem na página
*background-attachment:* fixed; scroll;
# Background-position
Usa-se para definir a posição da imagem na página
*background-position:*center; left center; right; center top; center bottom;

# Padding: espaçamento interno
**padding: 5px;**
*padding-top:* espaçamento de cima
*padding-right:* espaçamento a direita
*padding-bottom:* espaçamento de baixo
*padding-left:* espaçamento a esquerda

# Float: fazem que os conteúdos flutuem a esquerda e direita
float: right; left; none;

# Elementos Inline,Block e inline-block

**Inline** - um elemento ao lado do outro
Ex: <a>, <span>, <img>
-> A largura do elemento e de acordo com seu conteúdo
-> Se posionam-se um ao lado do outro

**Block**
Ex: <h1> , <p>, <table>
-> Obtém uma largura que ocupa todo o espaçamento da tela
-> Se posionam-se um embaixo do outro

**Inline-Block**
Ex: display: inline-block
-> A largura e definida baseada em seu conteúdo
-> Se posionam-se um embaixo do outro
-> quando acaba a linha do contéudo pula para linha
de baixo

# Posicionamento estático, relativo, absoluto e fixo:

*position: static*
-> mantém o elemento estático no mesmo local(já vem por padrão)

*position: relative*
-> A posição fica relativa passivel de alteração
E NECESSÁRIO PROPRIEDADES PARA SE FAZER O DESLOCAMENTO
        **>> top, right, bottom, left <<**
Ex:
    position: relative;
    left: 20px;

*position: absolute*
-> Se sobrepõe as demais elementos
-> Acompanha a rolagem da tela

*position: fixed*
-> Se sobrepõe as demais elementos
-> Fica fixo na tela

# SOBREPOR ELEMENTOS

*z-index:*defini qual elemento aparece primeiro
com números 0, 1 , 2, 3...
**quanto maior o número mais ele se sobrepõe**

# FORMATAÇÃO DE LINKS
*Os links obtém estados*
*1°- Links Visitados*
Ex:
a:visited{
    color: red;
}

*2° - Links não visitados*
Ex:
a:link{
    color: red;
}

*3° - Links hover*
**Quando passa o cursor sobre o link**
a:hover{
    color: red;
}

*4° - Links Ativos*
**link ativo, quando clicado**
a:active{
    color: red;
}

# TIPOS DE SELETORES CSS

*Seletor Universal* - Aplica-se em todos os elementos no documento
Ex:
*{}
**Seleciona todos os elementos da página**

*Seletor de Texto* -  Seleciona elementos pelo tipo
Ex:
h1, h2, h3 {}
**Seleciona os elementos <h1>, <h2> e <h3>**

*Seletor de Classe* - Seleciona um elemento cujo atributo class tem o valor especificado depois do ponto
Ex:
.verde{}
**Seleciona qualquer elemento cujo atributo class tem o valor "verde"**
p.verde{}
**Seleciona somente elemento <p> cujo atributo class tem o valor "verde"**

*Seletor de ID* - Seleciona um elemento cujo atribuido id tem o valor especificado após ao símbolo de cerquilha ou jogo da velha
Ex:
#cabecalho{}
**Seleciona o elemento cujo atributo id tem o valor "cabecalho"**

*Seletor de filho* - Seleciona um elemento que é filho direto do outro
Ex:
li>a{}
**Seleciona quaisquer elementos <a> que são filhos de um elemento <li> (mas não outros elelementos na página)**

*Seletor de descendente* - Seleciona um elemento que é descendente de outro elemento especificado(e não apenas filho direto desse elemento)
Ex:
p a {}
**Seleciona quaisquer elementos <a> que residem dentro de um elemento <p>, mesmo se houver outros elementos aninhados entre eles**

*Seletor de irmão adjacente* - Seleciona um elemento que é o irmão próximo de outro
Ex:
h1 + p{}
**Seleciona o primeiro elemento <p> depois de qualquer elemento <h1> (mas não outros elementos <p>)**

*Seletor de irmão geral* - Seleciona um elemento que é um irmão de outro, embora ele não precise ser o elemento diretamente
Ex:
h1~p{}
**Se houvesse dois elementos <p> que fossem irmãos de um elemento <h1> essa regra se aplicaria ao dois**

# LINE HEIGHT
*Serve para alterar a altura da linha*
line-height: 0px;

# TEXT INDENT
*Serve para indentar o texto/movimentar*
text-indent: 0px;

# Tipos de Layout
Fixo: onde se define por *width: 0px;*
se mantendo fixo de acordo com o tamanho da janela

Líquido: Usa-se %, *width: 100%* para se tornar líquido
Se ajustando para ocupar toda a janela

**min-width:** usa-se para definir uma largura mínima
ao diminuir a janela de navegação.
**max-width:** usa-se para definir uam largura máxima
ao aumentar a janela de navegação.

**min-height:** usa-se para definir uma altura mínima
ao diminuir a janela de navegação.
**max-height:** usa-se para definir uma altura máxima
ao aumentar a janela de navegação.

*<fieldset>* -- Utilizado para agrupar dados semelhantes,como nome,email,telefone e etc
Ex:
__Detalhes de Contato___
| Nome:                 |
| Email:                | -> Cria está espécie de borda
| Telefone:             |
|_______________________|

# SELETOR DE ATRIBUTO []
*input[type=text]* - desta forma seleciona apenas inputs com tipo "text"
**sempre passando dentro de [] colchetes**

# PARALLAX
**Trabalha com camadas de imagens, dando expressão de movimento**
- Imagens são fixas e outras se sobrepõem a outra 

# FONTES CUSTOMIZADAS
- Usa-se qualquer site de fontes para localizar a desejada
**É necessário realizar uma conervsão de tipo na fonte para ".woff"**
- Vá até o GOOGLE e pesquise: *converter woof*

Para carregar a fonte com o css:

@font-face{
    font-family: "nome fonte" - *posso definir qualquer nome*
    src: url("NOMEFONTE.woff"); - *Para puxar a fonte usa-se src ou source*
}


# Normalize css
- Usa-se pra deixar as configurações padrões para todos os navegadores
- Preserva as configurações padrões do navegadores
- Faz correções de bugs

link: https://necolas.github.io/normalize.css/
copia e cola seu conteúdo em um arquivo css e linkando
ao html:
Ex: 
<link rel="stylesheet" href="normalize.css">


# Border Radius
- Usa-se para definir um arrendondamento para um elemento
Ex:
- pode definir 4 valores sendo:
*border-radius: 0px 0px 0px 0px;*
                |    |   |  |-> para baixo a esquerda
                |    |   |-> para baixo a direita
                |    |-> para o topo a direira
                |-> para o topo a esquerda

**Existem navegadores que precisam de prefixos para usar a propriedade border radius**
# Prefix:
Chrome: -webkit- | -webkit-border-radius: 0px;
Mozilla: -moz-   | -moz-border-radius: 0px;
Safari: -webkit- | -webkit-border-radius: 0px;

# Border Sizing
- Usa-se para ajustar o tamanho da caixa, evitando que o padding aumente o tamanho da caixa

**Existem navegadores que precisam de prefixos para usar a propriedade border sizing**
# Prefix:
Chrome: -webkit- | -webkit-border-radius: 0px;
Mozilla: -moz-   | -moz-border-radius: 0px;
Safari: -webkit- | -webkit-border-radius: 0px;

# Transparencia
- Usa-se para dar um efeito de transparencia no elemento
Ex:
                            |-> *E NO FINAL DEFINA A PORCENTAGEM*
                            |    *DE TRANSPARÊNCIA*
background: rgb(255, 255, 255, 0.5);
                    |-> PASSA UM CÓDIGO DE COR

# Gradient
- Usa-se para fazer uma mistura de cores como especie de degrade
background: *linear-gradient*(color, color, color)

linear-gradient(to top, red, green, blue)
                |      |-> Define-se três cores que vão 
                |          ser utilizadas
                |-> Define onde vai começar o degrade:
                        TO (*Top, Bottom, Left and Right*)
                                    ou em graus
                        *90deg, 50deg, 20deg, 10deg...*
                    
# Sombra, Text-shadow , Box Shadow
Usa-se para aplicar uma sombra em um texto
a sombra funciona como um background, sendo assim ela não empurra
os outros elementos
*text-shadow: 0px 0px color;*

**passe três argumentos na tag**
text-shadow: 0px 0px color;
                |    |-> define a cor da sombra
            |    |-> controla a posição vertical( top e bottom)
            |-> controla a posição horizontal(left e right)

Pode usar *rgb* ou *rbga* para definir a opacidade da sombra
Ex:
text-shadow: 0px 0px rgb(0, 0, 0, 0.5);
                                    |-> passa o valor de 0 ate 1

Pode passar um terceiro argumento para denifir um blur na sombra
Ex:
text-shadow: 0px 0px 10px rgb(0, 0, 0, 0.8);
                    |-> passa um valor e já define o blur

*box-shadow: 5px 5px 8px 0px black;*
Usa-se da mesma maneira que text-shadow mais aqui
e possível passar um 4° argumento
Ex:
box-shadow: 5px 5px 8px 0px black;
                        |-> Define a proporção que a sombra se 
                            espalha no elemento


# Animações
Usa-se para dar uma animação ao um alemento
Ex:
*@keyframes nome-class/id*

    form{ *Estado Inicial* | Onde Começa a 
        background: gray;  | Animação
    }

    to{ *Estado Final*     | Onde Termina a 
        background: purple;| Animação
    }
**Dentro da class ou id define as tags**
1° - animation-name: animacao-caixa; | Busca o Nome da animação
2° - animation-duration: 5s;         | Define o Tempo da animação
3° - animation-delay: 3s;            | Define o delay da animação
4° - animation-iteration-count: 2;   | Define quantas vezes a animação ocorrerá
5° -animation-direction: alternate;  | Define a direção da animação

É possivel definir todos esse paramêtros em uma só linha:
animation: nome-class/id, 5s, 3s, 2 alternate;
            |              |  |   |    |-> direção da animação
            |              |  |   |-> quantidade de execução
            |              |  |-> tempo de delay
            |              |-> tempo de duração
            |-> nome da animação

# Transições
Usa-se a propriedade *transition* sendo passados tais argumentos:

transition: width 2s ;
            |    |-> O tempo de duração da animação
            |-> 1° elemento para a animação

**É possível passar vários elementos**
Ex:
*DE FORMA MANUAL*
transition: width 3s, background 3s ;
*TODOS OS ELEMENTOS*
transition: all 3s;
            |-> Para selecioanar tudo


# Tag Header
E uma tag para definir dentpo do site o cabeçalho do seu site
sem precisar utilizar uma div e um id para estilizar o mesmo, utilizando: 
*<header>*

# Tag Nav
E uma tag para definir dentro do site a navegação do seu site
sem precisar utilizar uma div e um id para estilizar o mesmo, utilizando: 
*<nav>*

# Tag Footer
E uma tag para definir dentro do site o footer do seu site
sem precisar utilizar uma div e um id para estilizar o mesmo, utilizando: 
*<footer>*

# Tag Article
e uma tag para colocar conteúdos que representam uma "postagem", podendo ser informações sobre a empresa.

#  Tag Section
E uma tag que permite voçê criar seções dentro do conteúdo site

# Tag Time
E uma tag para definir uma data

# Tag Aside
E uma tag para colocar conteúdos laterais no site

# Flex Box
E um modo de layout, que torna a inclusão de elmentos dentro de um container de forma mais simples e flexivel. Usa-se a TAG <display:>
**<display: flex;>** Com o flex permite você alterar as direções das colunas usando: <flex-direction:>

*TENDO COMO ARGUMENTOS: ROW | ROW-REVERSE | COLUMN | COLUMN-REVERSE*

1° - *Row:* Deixa os elementos um ao lado do outro de maneira horizontal

2° - *Row-Reverse:* Deixa os elementos um ao lado do outro de maneira horizontal, mas de forma invertida ao lado direito da tela

3° - *Column:* Deixa os elementos em forma de coluna um embaixo do outro de maneira vertical

3° - *Column-Reverse:* Deixa os elementos em forma de coluna um embaixo do outro de maneira vertical, mas invertendo a ordem dos elementos

Permite que você defina a quebra dos elementos usando: <flex-wrap:>
*TENDO COMO ARGUMENTOS: NOWRAP | WRAP | WRAP-REVERSE*
**Trabalha junto ao width do container**

1° - *nowrap*: Se o width for menor que a largura dos elementos ele os comprimi para caber um ao lado do outro.

2° - *wrap*: Se o width for menor que a largura dos elementos ele vai permitir a quebra jogando os elementos para baixo.

3° - *wrap-reverse*: Se o width for menor que a largura dos elementos ele vai permitir a quebra jogando os elementos para baixo, mas com a ordem invertida.


Permite que você defina a posção dos elementos usando: <justify-content>
*TENDO COMO ARGUMENTOS: FLEX-START | FLEX-END | CENTER | SPACE-BETWWEN | SPACE-AROUND*

1° - *flex-start*: É um alinhamento que já vem definido como padrão, alinhado no canto superior esquerdo

2° - *flex-end*: É um alinhamento que fica no canto superio a direita

3° - *center*: É um alinhamento que permite centralizar os elementos

4° - *space-between*: É um alinhamneto que distribui os itens adicionado um espaçamento entre eles, os itens das pontas ficam colados nos cantos

5° - *space-around*: É um alinhamneto que distribui os itens adicionado um espaçamento entre eles, os itens das pontas NÃO ficam colados nos cantos , mas com certo espaçamento.

**Align-items**
Permite que voçe ajuste a posição de um determinador container, sendo motidos sna vertical

1° - *stretch*: É posionamento que deixa os elementos na vertical esticados

2° - *center*: É um posicionamento que deixa os elementos centralizados

3° - *flex-start*: É um posicionamento que deixa os elementos "colados" na parte superior

4° - *flex-end*: É um posicionamneto que deixa os elementos "colados" na parte inferior

5° - *baseline*: É um posicionamento que utiliza a linha como base para realizar os alinhamento dos conteúdos

# ORDEM DE ITENS
Usa-se para definir a ordem de exibição do elemento, usando:
*Obs: Todos elementos por padrão tem o valor 0*
**Definidos por valores de 0, 1 ,2 3...**
a tag <order: 0;>
    |-> passa uma class
Ex: .ordem1{
    order: 1; |-> define um valor
}
*NOS ELEMENTOS:*
Ex: Ordem decrescente 4, 3 , 2 , 1:

<div class="item ordem4">01</div> | 04
<div class="item ordem3">02</div> | 03
<div class="item ordem2">03</div> | 02
<div class="item ordem1">04</div> | 01

# Flex Grow
Usa-se para definir a proporção de espaço ocupado por um item, usando:
A tag <flex-grow: 0;>
**Definidos por valores de 0, 1 ,2 3...** Quanto maior o número maior
o espaçamento ocupado pelo item

Ex:
.item              | Tamanho padrão
    flex-grow: 0 ; |

.item1          | Ele não tem mais um tamanho fixo como os
flex-grow: 1;   | demais itens, crescendo até o final do container

# Flex Shrink
Usa-se para definir a capacidade de redução de tamanho do item
A tag <flex-shrink: 1;>
**Definidos por valores de 0, 1 ,2 3...** Quanto maior o número maior
menor será a área ocupada quando se diminui a aba de navegação

Ex:
.item              | Tamanho padrão
flex-shrink: 1 ; |

.item1          | Quanto maior o número mais ele irá
flex-shrink: 2; | diminuir dentro do seu layout

# Flex Basis
Usa-se para indicar o tamanho inicial do flex item antes da distribuição
do espaço restante

Ex:
flex-basis: 100px;  | "tomando o lugar" do *width* quando não definido
    
# Bootstrap
Permite colocar elementos pré prontos, como cards, carrocéis, botões e etc

# Formatação de Textos
*Cabeçalho*: Com o bootstrap um <h5> pode ganhar uma formatação de <h1>
apenas colocando uma class="h1", exemplo: <h5 class="h1">

*Cabeçalho Display*: Colocando a (class display-1) ele altera o <h1> deixando o maior, e com a borda fina, exemplo: <h1 class="display-1"> **tendo do 1 até 4**

*Paragráfo*: Colocando a (class lead) ele altera o <p> deixando com uma fonte com bordas mais finas e visualmente mais bonito, exemplo: <p class="lead">

*Paragráfo Monospace*: Tem o o mesmo espaçamento para todas as letras, utiliza-se da 
(class text-monospace) alterando o <p>, exemplo: <p class="text-monospace">

*Paragráfo Negrito*: Deixa um texto em Negrito, utiliza-se geralmente em <p> usando 
(class font-weight-bold), exemplo: <p class="font-weight-bold>

*Paragráfo Itálico*: Deixa um texto em Itálico, utiliza-se geralmente em <p> usando 
(class font-italic), exemplo: <p class="font-italic>

*Letras Maiúculas*: Deixa o texto todo em maiúculo, utiliza-se geralmente em <p> usando 
(class text-uppercase), exemplo: <p class="text-uppercase>

*Letras Minúsculas*: Deixa o texto todo em minúsculas, utiliza-se geralmente em <p> usando (class text-uppercase), exemplo: <p class="text-lowercase">

*Primeira Letra Maiúscula*: Deixa a primeira letra em maiúscula, utiliza-se geralmente em <p> usando (class text-capitalize), exemplo: <p class="text-capitalize">

*Texto centralizado* : Deixa o texto no centro da tela, utiliza-se <class="text-center">
*Texto a direita* : Deixa o texto no centro da tela, utiliza-se <class="text-right">
*Texto a esquerda* : Deixa o texto no centro da tela, utiliza-se <class="text-left">

*Texto Justificado* : Deixa o texto com um exibição maior evitando de quebrá-lo, utiliza-se
<class="text-justify">

*Texto Truncado* : Corta o texto em certa parte, mostrando de acordo com o tamanho de exibição do layout, utiliza-se geralmente em <p>, exemplo: <p class="text-truncate">

*Bloco de Citação*: Deixa um bloco em destaque, utiliza-se a tag <blockquote>, exemplo:
<blockquote class="bockquote">

*Bloco de Citação com Footer*: Deixa um bloco em destaque com um rodapé destacando o autor, utiliza-se as tag <blockquote>, <footer> e <cite>, exemplo: <footer class="bockquote-footer">

*Lista sem estilo*: Essa class retira • da lista, utilizando <ul class="list-unstyled">

*Itens da lista na mesma linha*: Deixa os itens da lista um ao lado do outro, utilizando,
<ul class="list-inline"> e logo após acrescentando nós <li class="list-inline-item"> para
identificar o item

# Alinhamento Responsivo
É responsável por fazer o alinhamento de acordo com tamanho da tela a partir do critério >= tamanho da tela, neste caso no texto <p>
utilizando: <p class="text-(tela)-(alinhamento)">
**| tela:sm, md, lg, xl  | alinhamento: let, center, right |**

  |     *Small* : Sm    |  Celular   |
  |     *Medium* : md   |   Tablet   |
  |     *Large* : lg    |  Nootebook |
  |  *Extra Large* : xl | Computador |
**Com Float:**
utilizando: <div class="float-(tela)-(alinhamento)">

# BLock para em Inlline em BootStrap
Transforma um elemento block em um elemento inline, utilizando:
                <h1 class="d-inline">

                
# BLock para em Inline em BootStrap
Transforma um elemento block em um elemento inline, utilizando:
                <h1 class="d-inline">
        **Para realizar o inverso basta utilizar:**
                <span class="d-block">

# Float em BootStrap
utiliza-se apenas:
 <div class="float-left"> | <div class="float-right"> | <div class="float-none">
             |-> flutua a esquerda      |-> flutua a direita        |-> não flutua

# Clear Both em BootStrap
Utiliza-se em elementos pai de floats, sendo <div class="clearfix">

# Posionamento Fixo Top e Bottom em BootStrap
Utiliza-se para deixa um elemento fixo na tela, referente ao scroll do mouse, exemplo:
            <h1 class="fixed-top">  | <h1 class="fixed-bottom">

# Colar no Topo Sticky em BootStrap
Usa-se para colar um elemento que era fixo quando feita a rolagem depois dele ele gruda na parte definida tendo apenas o *topo*, utiliza-se:
<h1 class="sticky-top">

# Cores em BootStrap
Sendo utilizado para definir cores em diversos elementos

Azul - *class="text-primary"*
Cinza - *class="text-secondary"*
Verde - *class="text-success"*
Ciano - *class="text-info"*
Amarelo - *class="text-warning"*
Vermelho - *class="text-primary"*
Cinza Claro - *class="text-light"*
Cinza Escuro - *class="text-dark"*
Branco - *class="text-white"*
Preto Clarida de 50% - *class="text-dark-50"*
Branco Clarida de 50% - *class="text-dark-50"*

# Backgrounds em BootStrap
Sendo utilizado para definir cores de fundo em diversos elementos

Background Azul - *class="bg-primary"*
Background Cinza - *class="bg-secondary"*
Background Verde - *class="bg-success"*
Background Ciano - *class="bg-info"*
Background Amarelo - *class="bg-warning"*
Background Vermelho - *class="bg-primary"*
Background Cinza Claro - *class="bg-light"*
Background Cinza Escuro - *class="bg-dark"*
Background Branco - *class="bg-white"*
BackgroundTransparente - *class="bg-transparent"*

# Margin em BootStrap
Sendo utilizado para definir uma margem no elemento, utilizando classes:
**Utiliza-se a unidade de medida REM**
*mt* -> Margin Top
*mb* -> Margin Bottom
*ml* -> Margin Left
*mr* -> Margin Right
*mx* -> Margin no eixo x (horizontal) esquerda/ direita
*my* -> Margin no eixo y (horizontal) top/ bottom
*m* -> Margin em todos os lados 
**A definir um valor para a margem de 0 até 5**
            Ex:<p class="mt-2">

# Padding em BootStrap
Sendo utilizado para definir uma padding no elemento, utilizando classes:
**Utiliza-se a unidade de medida REM**
*pt* -> Padding Top
*pb* -> Padding Bottom
*pl* -> Padding Left
*pr* -> Padding Right
*px* -> Padding no eixo x (horizontal) esquerda/ direita
*py* -> Padding no eixo y (horizontal) top/ bottom
*p* -> Padding em todos os lados 
**A definir um valor para a margem de 0 até 5**
            Ex:<p class="p-2">

# Witdh em BootStrap
Sendo utilizado para definir uma largura aos elementos utilizando
classes:
*w-25%* -> Ocupa 25% da área total
*w-50%* -> Ocupa 50% da área total
*w-75%* -> Ocupa 75% da área total
*w-100%* -> Ocupa 100% da área total
*w-auto* -> Ocupa de forma automática a área
Ex: <div class="w-50">

# Height em BootStrap
Sendo utilizado para definir uma altura aos elementos utilizando
classes:
*h-25%* -> Ocupa 25% da área total
*h-50%* -> Ocupa 50% da área total
*h-75%* -> Ocupa 75% da área total
*h-100%* -> Ocupa 100% da área total
*h-auto* -> Ocupa de forma automática a área
Ex: <div class="h-50">

# Bordas em BootStrap
Sendo utilizado para definir uma borda aos elementos utilizando
classes:
*border*        -> todas as bordas
*border-top*    -> borda superior
*border-bottom* -> borda inferior
*border-right*  -> borda direita
*border-left*   -> borda esquerda
**Cores de bordas: border-(cor)**
Azul - *border-primary*
Cinza - *border-secondary*
Verde - *border-success*
Ciano - *border-info*
Amarelo - *border-warning*
Vermelho - *border-danger*
Cinza Claro - *border-light*
Cinza Escuro - *border-dark*
Branco - *border-white"*

# Bordas Arrendondadas em BootStrap
Sendo utilizado para definir cantos arredondados nos elementos
classes:
*rounded* - Arrendonda o elemento inteiro
*rounded-top* - Arrendonda apenas o topo
*rounded-right* - Arrendonda apenas o lado direito
*rounded-left* - Arrendonda apenas o lado esquerdo
*rounded-circle* - Cria uma espécie de circulo 

## Media Types
Usado para fazer exebições diferentes baseado no tamanho do dispositivo, no link do css
De forma manual usa-se assim: <link rel="stylesheet" media="all" href="all.css">

Tipo de Mídias:
*all* - todos os dispositivos
*aural* - sintetizadores de voz
*braille* - leitores de Braille
*embossed* - impressoras de Braille
*handheld* - dispositivos de mão. Por exemplo: celulares com telas pequenas.
*print* - impressoras convencionais
*projection* - apresentações de slides
*screen* - monitores coloridas
*tty* - teleimpressores e terminais
*tv* - televisores

Resoluções de Telas:
*320 pixels* - Smartphones no modo retrato.
*480 pixels* - Smartphones no modo paisagem.
*600 pixels* - Tablets pequenos. Ex: Amazon Kindle (600×800)
*768 pixels* - Tablets maiores em modo retrato. Ex: iPad (768×1024)
*1024 pixels* - Tablets maiores em modo paisagem, monitores antigos.
*1200* pixels - Monitores wide.

# Media Queries no BootStrap
Usado para a responsividade do site usa-se o comando dentro do css
Ex:
 <style>                                     _______________________________________
        /*   (Layout para Celular)    */    | Oque define que o body vermelho       |
        @media(min-width: 576px) {          | será aplicado quando a largura        |
            body {                          | for maior que 576px como estabelecido |
                background: red;            | se menor não terá a cor vermelha      |
            }                               |_______________________________________|
        }
/*  DEFINE QUE DENTRO DE 576 A 767.98 O BODY VAI SER AZUL */ 
        @media(min-width: 576px) and (max-width: 767.98px) {
            body {
                background: blue;
            }
        }
</style>    
        *ONDE O MIN-WIDTH DEFINE DE ONDE COMECA E MAX-WIDTH ATÉ ONDE VAI*

# Botões em BootStrap
formatação padrão para usar um botão com bootstrap: *class="btn"*
Formatação específicas: 
**USADAS ASSIM: CLASS:"btn btn-primary**
*btn-primary* : Botão Azul
*btn-secondary* : Botão Cinza
*btn-success* : Botão Verde
*btn-info* : Botão Ciano
*btn-warning* : Botão Amarelho
*btn-danger* : Botão Vermelho
*btn-light* : Botão Branco
*btn-dark* : Botão Preto
*btn-link* : Deixa com aspecto de link

## Botões com Contorno
Usa-se a formatão: *class="btn btn-outline-cor*

## Tamanho dos Botões
opções de tamanho: 
*btn-lg* - Botão Grande
*btn-sm* - Botão Pequeno
*btn-block* - Deixa o botão ocupando a tela toda

## Estado dos Botões
*btn* - Normal
*active* - Ativo
*disable* - Inativo
*data-toggle="button"* - Alterna de Normal para Ativo

## Grupo de Botões na Horizontal
Uni vários botões em uma espécie de "barra de navegação", usando
a *class="btn-group"*, na div em que os botões se encontram
Ex:
<div class="btn-group">
    <button class="btn btn-info">Esquerda</button>
    <button class="btn btn-danger">Centro</button>
    <button class="btn btn-warning">Direita</button>
</div>

## Grupo de Botões na Vertical
Uni vários botões em uma espécie de "barra de navegação", usando
a *class="btn-group-vertical"*, na div em que os botões se encontram
Ex:
<div class="btn-group-vertical">
    <button class="btn btn-secondary" type="button" >Topo</button>
    <button class="btn btn-dark" type="button" >Meio</button>
    <button class="btn btn-info" type="button" >Base</button>
</div>

## Toolbar de Botões
Uni grupos de botões em uma espécie de "barra de navegação", usando
a *class="btn-toolbar"*, na div mais exterior em que os botões se encontram
Ex:
<div class="btn-toolbar">
    <div class="btn-group">
        <button class="btn btn-secondary">1</button>
        <button class="btn btn-dark">2</button>
        <button class="btn btn-info">3</button>
    </div>
    <div class="btn-group">
        <button class="btn btn-secondary">4</button>
        <button class="btn btn-dark">5</button>
        <button class="btn btn-info">6</button>
    </div>
</div>

## Botões Dropdown
Permite dentro de um botão mostrar várias opções usando:
*class="dropdawn"* na div central e exterior
No botão usa-se *class="dropdawn-toggle"* e *data-toggle="dropdawn* 
Na div de links que deseja exibir dentro do botão usa-se *class="dropdawn-menu* 
Nos itens *class="dropdawn-item1"* 
Possivel usar um divisor com uma div entre os links, *class="dropdawn-divider"*

Ex:
<div class="dropdown">
    <button class="btn btn-secondary dropdown-toggle" data-toggle="dropdown" >Clique</button>
    <div class="dropdown-menu">
        <a href="#" class="dropdown-item">Link 1</a>
        <a href="#" class="dropdown-item">Link 2</a>
        <a href="#" class="dropdown-item">Link 3</a>
    </div>
</div>

# Barra de Navegação Com Abas em BootStrap
Define barras de navegação por meio de classes padrões:
*nav* - para o elemento mais ao exterior (div)
*nav-item* - para o elemento identado (li)
*nav-link* - para o link dentro do elemento identado (a) **Podendo deixar active e disabled**
Ex:
<div class="nav">
    <li class="nav-item">
        <a href="" class="nav-link">Home</a>
    </li>
</div>

*nav-pills* - sendo usado na div mais exterior define como página marcada, no elemento
utiliza a *classe="active"*
Ex:
<ul class="nav nav-pills">
    <li class="nav-item">
        <a href="" class="nav-link active">Home</a>
    </li>
</ul>
**CRIA UM PADDING EM VOLTA DO NAV**

*nav-tabs* sendo usado na div mais exterior define também como página marcada, no elemento
utiliza a *classe="active"*
Ex:
<ul class="nav nav-tabs">
    <li class="nav-item">
        <a href="" class="nav-link active">Home</a>
    </li>
</ul>
**CRIA UM MARCADOR COMO UMA ESPECIE DE PASTA**

## Opções de alinhamento
*justify-content-center* - Deixa a Barra de Nav ao centro
*justify-content-end* - Deixa a Barra de Nav a direita
*flex-column* - Deixa a barra de Nav na Horizontal

# Barra de Navegação Simples em BootStrap
Utilizado para combinar uma logo e a barra de navegação, sendo utilizado dentro de um <nav>
com a classe principal, *class="navbar"*, Combinado junto com:

*class="navbar-nav"* - É utilizado para definir dentro da ul onde será aplicado a barra de nagação é logo após nos <li> usa-se *class="nav-item"*, <a> usa *class="nav-link"*

*class="navbar-brand"* - Identifica o elemento como uma logo
*class="navbar-expand-sm"* - Define o tamanho da barra de navegação
*class="navbar-dark"* - Define a cor do texto dentro da navegação
*class="navbar-dark"* - Define a cor de funfo dentro da navegação
**Usando o ml-auto(margin-left) empurrou os links de nagação para o canto**
Ex:
<h2 align="center">Barra de Navegação simples</h2>
 <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
    <!--Logo-->
    <a href="" class="navbar-brand">Chalé Hotel</a>
    <!--navegação-->
    <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a href="" class="nav-link">Home</a></li>
        <li class="nav-item"><a href="" class="nav-link">Sobre</a></li>
        <li class="nav-item"><a href="" class="nav-link">Serviços</a>
    </ul>
</nav>

# Barra de Navegação com Menu Responsivo em BootStrap
Permite esconder os links de navegação em um icone, onde clicando pode se expandir é mostrar as opções, mas ele depende da class="navbar-expand-sm" definida na tag <nav>, onde so aparecerá quando a tela for *Small(Celular) - sm*
Ex:
                        |-> Definindo quando aparecerá o menu responsivo no caso *Small*
<nav class="navbar navbar-expand-sm">
    <a href="" class="navbar-brand">Chalé Hotel</a>

Para definir o icone do menu cria um tag <button> e <span>, no button passa as seguintes classes:
*class="navbar-toggler"* - 
*data-toggle="collapse"* -
*data-target="#nav-target"* -

No Span passa as seguintes classes:
*navbar-toggler-icon* - Para criar o icone

<button class="navbar-toggler" data-toggle="collapse" data-target="#nav-target">
    <span class="navbar-toggler-icon"></span>
</button>

    <!--navegação-->
    <div class="collapse navbar-collapse" id="nav-target">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item"><a href="" class="nav-link">Home</a></li>
            <li class="nav-item"><a href="" class="nav-link">Sobre</a></li>
            <li class="nav-item"><a href="" class="nav-link">Serviços</a>
        </ul>
    </div>
</nav>


