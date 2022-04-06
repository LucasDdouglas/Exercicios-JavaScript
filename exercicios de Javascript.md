#                Exercícios de Javascript



### Desafio 01

let number = 9

if (number > 10) {

  console.log(`O numero ${number} é maior que 10`)

} 

else if ( number < 10) {

  console.log(`O numero ${number} é menor que 10`)

}

else {

  console.log(`O numero ${number} é igual a 10`)

}



### Desafio 02

 let pessoa =

{

  nome: "josé",

  idade: 20,

  nacionalidade: "Americano"

}



if (pessoa.nacionalidade === "Brasileiro") {

  console.log(`A pessoa cujo nome é ${pessoa["nome"]} é Brasileiro`)

}

else { console.log(`A pessoa cujo nome é ${pessoa["nome"]} não é Brasileiro`) }



### Desafio 03

 let numeroAleatorio01 =  Math.floor(Math.random() * (10 - 1)) + 2;

let numeroAleatorio02 =  Math.floor(Math.random() * (10 - 1)) + 2;



if (numeroAleatorio01 === numeroAleatorio02 ) {

  console.log(`PARABENS! Você Ganhou um Carro!!  Número sorteado foi: ${numeroAleatorio01} e ${numeroAleatorio02}`)

} else {

  console.log(`Que pena! Não foi dessa vez. Número sorteado: ${numeroAleatorio01} e ${numeroAleatorio02} `)

} 



### Desafio 04

 let PrimeiroNumero = 90

let SegundoNumero = 10

let TerceiroNumero = 60



if (PrimeiroNumero > SegundoNumero && PrimeiroNumero > TerceiroNumero) {

  console.log(`Primeiro Numero é o Maior ${PrimeiroNumero} `)



}

else if (SegundoNumero > TerceiroNumero) {

  console.log(`Segundo Numero é o Maior ${SegundoNumero}`)

}

else {

  console.log(`Terceiro Numero é o Maior ${TerceiroNumero}`)

}



if (PrimeiroNumero < SegundoNumero && PrimeiroNumero < TerceiroNumero) {

  console.log(`Primeiro Numero é o Menor ${PrimeiroNumero} `)



}

else if (SegundoNumero < TerceiroNumero) {

  console.log(`Segundo Numero é o Menor ${SegundoNumero}`)

}

else {

  console.log(`Terceiro Numero é o Menor ${TerceiroNumero}`)

} 



### Desafio 05

 let ProcessoSeletivo = 

  { nome: "Marcos",idade:"22",sexo:"Masculino", profissão: "Programador", nacionalidade:"Brasileiro" }

 





if (ProcessoSeletivo.idade >= 18 && ProcessoSeletivo.nacionalidade === "Brasileiro") {

  console.log(`PARABENS! ${ProcessoSeletivo.nome} Você Passou no Processo Seletivo`)

} else {

  console.log(`Infelizmente Você Não Passou no Processo Seletivo`)

}



### Desafio 06

 let notas = 4



switch (notas) {

  case 0:

​    console.log("Você foi Péssimo")

​    break;



  case 1:

​    console.log("Você foi Péssimo")

​    break;



  case 2:

​    console.log("Você foi Péssimo")

​    break;



  case 3:

​    console.log("Você foi Péssimo")

​    break;



  case 4:

​    console.log("Tem muito para melhorar")

​    break;



  case 5:

​    console.log("Da pra Melhorar")

​    break;



  case 6:

​    console.log("Da pra Melhorar")

​    break;



  case 7:

​    console.log("Otimo")

​    break;



  case 8:

​    console.log("Excelente")

​    break;



  case 9:

​    console.log("Excelente")

​    break;



  case 10:

​    console.log("Excelente")

​    break;

}



### Desafio 07

 let numero = 4



if (numero % 2 === 0) {

  console.log(`${numero} é Par`)



}

else {

  console.log(`${numero} é Impar`)

}



### Desafio 08

 let numero = 27

if (numero % 2 === 0) {



  if (numero % 5 === 0) {

​    console.log(`O ${numero} é Par e Divisivel por 5`)

  }

  else {

​    console.log(`O ${numero} é só Par e não é Divisivel por 5`)

  }

}



else {

  for (let i = 2; i < numero; i++)

​    if (numero % i === 0) {

​      console.log(`O ${numero} é só Impar, mas não é Primo`)

​      break

​    }

​    else {

​      if (i === numero -1)

​        console.log("ele é um numero primo")

​    }

}



### Desafio 09



let NumeroUm = 13

let NumeroDois = 15

let NumeroTres = 25

let NumeroQuatro = 1



if (NumeroUm % 2 === 0 && NumeroDois % 2 === 0 && NumeroTres % 2 === 0 && NumeroQuatro % 2 === 0 ) {

  console.log("Todos os Numeros são pares")

  

}

else if (NumeroUm % 2 !== 0 && NumeroDois % 2 !== 0 && NumeroTres % 2 !== 0 && NumeroQuatro % 2 !== 0) {

  console.log("Todos os Numeros são Impares")

}

else {

  console.log("Temos Numeros Pares e Impares Misturados")

}