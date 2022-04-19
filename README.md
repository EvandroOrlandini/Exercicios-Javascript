# Exercícios-Javascript
Exercícios de nivelamento em Javascript

# Exercícios

## Variáveis
### Exercício 01 - Criando variáveis
Vamos escrever nossas primeiras variáveis juntos. Você irá usar tudo que aprendeu anteriormente! 

Declare duas variáveis chamadas  idade  e  peso,  e atribua um valor numérico a ambas.

#### Solução:

var idade = 41 

var peso = 60


### Exercício 02 - Criando variáveis
Agora para deixar todo esse conhecimento fixo na mente, precisamos praticar um pouco mais!

Declare 4 variáveis: nome, sobrenome, numeroDaSorte e idade. Atribua um valor para cada uma delas, conforme o tipo.

#### Solução:

var nome = "Evandro"

var sobrenome = "Orlandini"

var numeroDaSorte = 12

var idade = 41


### Exercício 03 - Tipos de dados
Escreva no arquivo script as variáveis expostas abaixo substituindo os tipos de dados citados por valores, conforme vimos no material teórico: 

var idade = Number

var sobrenome = String

var salarioMinimo = Float 

#### Solução:

var idade = 41

var sobrenome ="Orlandini"

var salarioMinimo = 1.212


### Exercício 04 - Tipos de dados
Vamos continuar praticando a declaração de variáveis e atribuição de valores: 


Declare cinco variáveis com a nomenclatura a seguir e atribua a tais, um valor que atenda o tipo de dado indicado:

- nome (string) 
- idade (number)
- altura (float)
- possuiPet (boolean)
- filmesFavoritos (array)


#### Solução:

var nome = "Evandro"

var idade = 41

var altura = 1.69

var possuiPet = false

var filmesFavoritos = [ "ET", "Rambo",]


### Exercício 05 - Usando variáveis - Cartão de Visita
Temos um desafio para você! 

Precisamos criar um código que gere cartão de visita com nome, sobrenome e profissão dos clientes, para isso:

Crie uma variável para guardar cada informação (cada uma deve receber um dos 3 nomes acima), 
Depois faça a concatenação das informações em uma nova variável chamada cartaoDeVisita.

Exemplo:

nome: Taylor

sobrenome: Alvarenga

profissão: Programadora


#### Solução:

var nome = "Taylor"

var sobrenome = "Alvarenga"

var profissao = "Programadora"


var cartaoDeVisita = nome + ' ' + sobrenome +  ' - ' + profissao

console.log(cartaoDeVisita)


### Exercício 06 - Operadores aritméticos - Cálculo de Lucros
Uma empresa separou os seus ganhos dos meses nas seguintes variáveis:



let janeiro =  100

let fevereiro = 300

let março = 90


Ela precisa da sua ajuda para saber o total do lucro adquirido. Sua missão é usar os operadores com as variáveis para realizar esse cálculo e use o console.log para imprimir o resultado!



Para lhe auxiliarmos, já deixamos o código inicial:

let janeiro =  100

let fevereiro = 300

let marco = 90

let valorTotal = ?


#### Solução:


let janeiro = 100

let fevereiro = 300

let marco = 90

console.log(janeiro + fevereiro + marco)

var valorTotal = (janeiro + fevereiro + marco )


### Exercício 07 - Cálculos
Declare 6 variáveis de memória com os seguintes nomes: numeroA, numeroB, soma, subtracao, multiplicacao e divisao (observem que nomes de variáveis não tem acento).

#### Solução:

let numeroA = 6

let numeroB = 2

console.log(numeroA + numeroB)

var soma = (numeroA+numeroB)

console.log(numeroA-numeroB)

var subtracao =(numeroA - numeroB)

console.log(numeroA * numeroB)
var multiplicacao =(numeroA * numeroB)

console.log(numeroA / numeroB)

var divisao =(numeroA / numeroB)


### Exercício 08 - Cálculo de média
Um sistema de gestão escolar quer calcular a média das notas de um aluno.

Ele guarda em variáveis as notas de cada um dos trabalhos realizados:

let trabalhoDeHistoria = 8.0
let trabalhoDeMatematica = 7.0
let trabalhoDeCiencia = 10
let trabalhoDeGeografia = 9.5


Sua missão é completar o código para fazer com que o sistema calcule a média das notas, somando-as e dividindo o total pela quantidade de trabalhos (variável quantidadeDeTrabalhos).

Atribua o resultado dessa conta a uma variável chamada media

#### Solução:

let trabalhoDeHistoria = 8.0

let trabalhoDeMatematica = 7.0

let trabalhoDeCiencia = 10

let trabalhoDeGeografia = 9.5

let quantidadeDeTrabalhos = 4

var media = (trabalhoDeHistoria + trabalhoDeMatematica + trabalhoDeCiencia + trabalhoDeGeografia) / quantidadeDeTrabalhos



## Condicionais


### Exercício 09 - Condicional IF
Precisamos de um código que verifique a idade do usuário para ver se já tem idade mínima para adquirir carta de habilitação. Para isso, teremos uma variável nome que guarda um valor do tipo string, e uma variável idade que guarda um valor do tipo numérico.

O sistema deve cumprimentar o usuário independente da idade, o resultado seria assim:

Caso o usuário tenha idade mínima para dirigir imprima: 

“Olá, NOME_DO_USUARIO_AQUI”

”Você passou no nosso teste e já pode dirigir!”.

Caso o usuário não tenha a idade mínima para dirigir imprima somente o cumprimento:

“Olá, NOME_DO_USUARIO_AQUI”


#### Solução:

let nome = "João"

let idade = 18

if(idade>=18){console.log("Olá,"  + nome +     "Você passou no nosso teste e já pode dirigir!")}

if(idade<=17){console.log("Olá,"+"nome")}


### Exercício 10 - Condicionais - Conta bancária
Queremos um código que oriente o usuário de acordo com o saldo da conta bancária. Para isso precisamos de uma variável saldo que guarda um número decimal(float), e imprime uma mensagem de acordo com a situação financeira.

Se o saldo for maior que 0 (zero) imprima:
 “Seu saldo está positivo! Gostaria de fazer um investimento?”

Se o saldo for menor que 0 (zero) imprima:
 “Seu saldo está negativo! Gostaria de fazer um empréstimo?” 

#### Solução:

var saldo = 100.00

if (saldo > 0) {console.log("Seu saldo está positivo! Gostaria de fazer um investimento?")}

if (saldo < 0) {console.log("Seu saldo está negativo! Gostaria de fazer um empréstimo?")}

### Exercício 11 - Operadores relacionais - Condicional - Votação
No sistema político atual, temos algumas regras para participar das eleições. A principal delas, é que o voto é obrigatório a partir dos 18 anos, e opcional quando idade for igual a 16! 


Diante desse cenário, escreva um código que de acordo com a variável idade informe ao usuário usando console.log(), “Você é obrigado a votar” caso ele cumpra o requisito ou “Seu voto é opcional”.

#### Solução:

let idade = 17

if (idade>= 18){console.log("Você é obrigado a votar")}

if (idade==16){console.log("Seu voto é opcional")}

### Exercício 12 - Condicional IF ELSE - Condicionais - Estrangeiro
Utilize a condicional if/else para verificar a variável estrangeiro que guarda um valor booleano. Caso o valor seja verdadeiro solicite o Registro Nacional de Estrangeiros(RNE). Se o valor for falso solicite o Cadastro de Pessoa Física (CPF).

Mensagem para estrangeiro: “Você poderia apresentar seu RNE, por favor?”
Mensagem para brasileiro: “Você poderia apresentar seu CPF, por favor?”

#### Solução:

let estrangeiro = true

if(estrangeiro){console.log("Você poderia apresentar seu RNE, por favor?")

}else{console.log("Você poderia apresentar seu CPF, por favor?")}




### Exercício 13 - Condicionais - Autoescola
Vamos otimizar nosso sistema de autoescola!
Caso o usuário tenha 18 anos ou mais, ele pode dirigir, se a afirmação for negativa precisamos imprimir a mensagem “Ops, você ainda não tem a idade mínima para dirigir!”.
Parte do código já está pronto, agora é sua vez de utilizar o else para dar um feedback ao usuário!

#### Solução:

var idade = 18

if ( idade >= 18){

 console.log("Você já pode dirigir!")

}else  

 console.log("Ops, você ainda não tem a idade mínima para dirigir!")




#### Solução:

## Loops



## Funções



## Exercícios integradores
