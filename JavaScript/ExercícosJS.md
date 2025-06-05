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