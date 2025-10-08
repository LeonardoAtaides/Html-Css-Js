# ANOTAÇÕES EM JAVA SCRIPT
_O JS PERMITE APLICAR DINÂMICA AOS ELEMENTOS DA PÁGINA WEB_

# VARIÁVEIS
Como e feita a declaração: sendo opcional mais importante utilizada-se 
o termo _var_ antes da variável, *não podem ser iniciados com números,apenas com letras com ou "_", não pode ser utilizado caracteres especiais como "ç" , "$" e nãopodeutilizar palavras reservadas da linguagem_*

Ex: var Soma = 10 + 10;

# TIPOS DE VARIÁVEIS
*Strings* -  Armazenagem os caracteres 
*Number* -  Armazenamento número inteiro, negativos, inteiros ou fracionados 
*Boolean* - Permite o valor de estado, False ou True

## NULL 
É declarada no momento sem valor, depois geralmente guarda um valor após ser atribuido.
Ex var nome =_null_

## UNDEFINED 
É declarada sem valor, é utilizado quando não temos valor para uma variável
Ex var nome =_undefined_

# Comandos:

*alert()* -  Mostra uma caixa com uma mensagem definida pelo dev, pode ser utilizar variáveis também para mostrar o valor da variável.
ex: alert("Olá, mundo!");

*document.write()* - Escreve algo na página, pode ser utilizar variáveis também para mostrar valores.
**É POSSIVEL CONCATENAR STRINGS COM O +**
Ex: 
var nome = 'Ataídes'; -> _define uma variável_

document.write('<h1> Olá ' + nome +'</h1>');
    |            |            |-> passa o nome da varoável
    |            |-> passa a tag em html
    |-> chama o comando

**PODE SE PEDIR OS DADOS DO USUARIO COM O PROMPT()**
Funciona como o input que recebe o valor digitado pelo usuário, pela caixa de mensagem exibida
pelo navegador,_estes dados são salvos como strings_
Ex: 
var nome = prompt("Qual é o seu nome?"); -  _"Ataídes"_
var idade = prompt("Qual é a sua idade?"); - _"19"_


*console.log()* - Utilizado no processo de debug, para testar os valores de variáveis, atravez do console do navegador.


# If e Else
If (condição){
_Lógica_ 
} else if{
_Lógica_
} else {
_Lógica_
}

# Operadores de comparação 
Igual: == - verifica se os valores comparados são *iguais*
Identifico: === - verifica se os valores são *iguais e do mesmo tipo*
Diferente: != - verifica se os valores comparados são *diferentes*
Não idêntico !== - Verifica se os valores comparados são *diferentes e de tipos diferentes*
Menor < - Verifica se o valor da esquerda é *menor* que o valor da direita
Maior > - Verifica se o valor da esquerda é *maior* que o valor da direita
Menor <= - Verifica se o valor da esquerda é *menor ou igual* ao valor da direita
Menor >= - Verifica se o valor da esquerda é *maior ou igual* ao valor da direita

Ex:
var num1 = prompt('Digite um número: ')
var num2 = prompt('Digite mais um número: ')

if(num1 == num2){
document.write(+num1+' e '+num2+' são iguais!')
} else{
document.write(+num1+' e '+num2+' não são iguais!')
}

# Operadores Lógicos
E = && - Verdadeiro se todas as expressões forem verdadeiras
Ex:
if(1 < 2 && 4 > 3){
    document.write('Verdadeiro')
}

OU || - Verdadeiro se pelo menos uma das expressões for verdadeira
if(1 > 2 || 3 == 3){
    document.write('Verdadeiro')
}else{
    document.write('Falso')
}
       
NEGAÇÃO ! - Inverte o resultado da expressão de comparação  
if(1 > 2){
    document.write('Verdadeiro')
}else{
    document.write('Falso')
}

# Operadores Aritméticos
A ordem de precedência, executa de acordo com a prioridade
Ex:
10 + 5 - 5 * 2 / 2
1- Multiplicação e subtraçãoo
2 - Soma e divisão
Adição( + ) - soma dois valores
Ex:
var n1 = 77
var n2 = 700
document.write(n1 + ' + ' + n2 + ' = '+ (n1 + n2))

Subtração ( - ) - Diferença entre valores
Ex:
var n1 = 700
var n2 = 77
document.write(n1 + ' - ' + n2 + ' = '+ (n1 - n2))
       
Multiplicação ( * ) - Multiplica dois valores
Ex:
var n1 = 10
var n2 = 7
document.write(n1 + ' x ' + n2 + ' = '+ (n1 * n2))

Divisão ( / ) - Divisão entre dois valores
var n1 = 10
var n2 = 2
document.write(n1 + ' / ' + n2 + ' = '+ (n1 / n2))

Módulo ( % ) - Resto da divisão entre dois valores
var n1 = 10
var n2 = 2
document.write(n1 + ' % ' + n2 + ' = '+ (n1 % n2))

Incremento ( ++ ) - Aumenta o valor de uma variável em 1
var n1 = 10
var n2 = 2
document.write(n1 + ' + 1' + ' = '+ (++n1))

Decremento ( -- ) - Diminui o valor de uma variável em 1
var n1 = 10
var n2 = 2
document.write(n1 + ' - 1' + ' = '+ (--n1))

# Operadores de Ternário
É uma estrutura de decisão mais tem uma estrutura mais simples:
var resultado = <condição> ? <verdadeiro> : <falso>
**Recomendado apenas quando a condição é simples e não complexa.**

# Troca de Tipo
É possível alterar o tipo de uma variável, por exemplo, de string para número, usando o comando *parseInt()* ou *parseFloat()*, que convertem a string em número, e o comando *toString()* que converte o número em string.

Ex:*parseInt()*
var number = prompt('digite um número:')
var number = parseInt(number)

Ex:*parseFloat()*
var v3  = 10.5
v3 = parseFloat(v3)

Ex:*toString()*
var v1  = 10
var v2  = 20
document.write(v1.toString() + v2.toString())

# Switch
O Switch é uma estrutura de decisão que permite comparar um valor com vários valores, utilizado geralmente em menus
Ex:
var opcao = 2
switch(opcao){
    case 1:
        //código
        break;
    case 2:
        //código
        break;
    default:
        //código
        break;   
}

# Funções
Encapsular um bloco de código com um objetivo definido, tendo um *retono*
Ex:

fuction calcularAreaTerreno(largura, comprimento){
    var area = largura * comprimento
    return area
}

**Função tipo VOID**
Quando chamada apenas irá processar algo
Ex:

function Imprimir(){
    document.write('hello, Word')
}

**Função Anônima**
Uma função sem nome , geralmente utilizada em eventos
Ex:     
       |-> atribui ela a uma variavel para poder ser chamada 
var saudacao = function(){
document.write('Olá'+ name + 'Bem vindo!')
}

**Funções de callback**
Funções que são passadas como argumentos para outra função
Ex:
callbackSucesso(titulo, descricao)                      callbackErro(erro)

__________________________________________________________________________
|       fuction exibirArtigo( id, callbackSucesso, callbackErro )         |
|                                                                         |
|       _Lógica para recuperar o artigho com base no id                   |
|                                                                         |
|       if(){                                                             |
|           callbackSucesso('Título', 'Descrição')                        |
|       }                                                                 |
|      else{                                                              |
|            callbackErro('Erro')                                         |
|        }                                                                |
___________________________________________________________________________

**Funções Nativas Mat**
*Math.round()* : recebe um valor fracionado e arredonda de acordo com o seu valor
*Math.ceil()* : recebe um valor fracionado e arredonda para um valor acima
*Math.floor()* : recebe um valor fracionado e arredonda para um valor abaixo
*Math.random()* : gere um valor aleatório entre 0 e 1

**Funções Nativas para Manipular Datas**
*new Date()* : cria uma nova data, buscando a data atual do sistema, atribuido 
 a uma variavel - Ex: var data = new Date()
 
*getDate()* : retorna o dia do mês em número - Ex: data.getDate()
*getMonth()* : retorna o mês em número - Ex: data.getMonth() + 1 *para o mês certo*
*getFullYear()* : retorna o ano - Ex: data.getFullYear()

# Strings

## Propriedade
**lenght**: serve para contar a quantidade de caracteres de uma string
EX:  document.write('Hello, Word!'.length) - *12 caracteres*

## Métodos
**charAt()**: retorna a letra de acordo com o indice que o caracter representa
EX: 'Hello, Word!'.charAt(0) - *H* 

**indexOf()**: retorna o indice da primeira ocorrencia de uma string
EX:
var name = 'Ataídes'
document.write(name.indexOf('A')) - *0*

**replace**: substitui uma string por outra
EX: 
var name = 'Leonardo'
document.write(name.replace('Leonardo', 'Ataídes')) - *Ataídes*

**substr()**: retorna uma parte da string
EX:
var name = 'Leonardo'
document.write(name.substr(3, 5)) - *nardo*

**toLowerCase()**: converte a string para minuscula
EX:   
var name = 'LEONARDO'
document.write(name.toLowerCase()) - *leonardo*

**toUpperCase()**: converte a string para maiuscula
EX: 
var name = 'leonardo'
document.write(name.toUpperCase()) *LEONARDO*

**trim** : remove os espaços em branco em uma string
EX:   
var name = ' leonardo '
document.write(name.trim())
