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






#### Solução:

#### Solução:
#### Solução:



## Loops



## Funções



## Exercícios integradores
