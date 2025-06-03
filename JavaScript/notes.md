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
} else if_{
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

OU || - Verdadeirp se pelo menos uma das expressões for verdadeira
NEGAÇÃO ! - Inverte o resultado da expressão de comparação


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

