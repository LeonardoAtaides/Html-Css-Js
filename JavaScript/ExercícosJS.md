*MÉDIA DE UMA NOTA DE ALUNO COM QUANTIDADE DE FALTAS*
var nota = prompt('Digite sua nota: ')
var faltas = prompt('Quantas faltas teve: ')

var media = 7
var faltas_max = 15

if(nota >= media && faltas <= faltas_max ){
    document.write('Aprovado!')
} else{
    document.write('Reprovado!')
}

*IDENTIFICAR A FAIXA ETÁRIA E CLASSIFICAR DE ACORDO COM A IDADE, INFORMADA PELO USUÁRIO*
var idade= prompt('Digite sua idade: ')

if(idade >= 0 && idade < 15){
document.write('Criança')
}
else if(idade >= 15 && idade < 30){
document.write('Jovem')
}
else if(idade >= 30 && idade < 60){
document.write('Adulto')
}
else if(idade >= 60){
document.write('Idoso')
}
else{
document.write('Idade inválida')
}

*CALCULAR O IMC, E MOSTRAR O RESULTADO EM PRINT*    

var name = prompt('Digite seu nome: ')
var height = prompt('Digite sua altuta em CM: ')
var weight = prompt('Digite o seu peso:  ')

height = (parseFloat(height)) / 100
weight = parseFloat(weight)
classification = null

Imc = weight / (height * height)
Imc = parseFloat(Imc)

if( Imc < 16){
    classification = 'Abaixo do peso, muito grave!'
}
else if( Imc >= 16 && Imc <= 16.9){
    classification = 'Abaixo do peso, grave!'
}
else if( Imc >= 17 && Imc <= 18.49){
    classification = 'Abaixo do peso!'
}
else if( Imc >= 18.50 && Imc <= 24.99){
    classification = 'Peso Normal!'
}
else if( Imc >= 25 && Imc <= 29.99){
    classification = 'Sobrepeso'
}
else if( Imc >= 30 && Imc <= 34.99){
    classification = 'Obesidade grau I'
}
else if( Imc >= 35 && Imc <= 39.99){
    classification = 'Obesidade grau II'
}
else{
        classification = 'Obesidade grau III'
}

document.write(name + ' possui índice de massa corporal igual a ' + Imc.toFixed(2) + ' sendo classificado como ' + classification)