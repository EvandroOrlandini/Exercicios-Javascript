# Exercícios-Javascript
49 Exercícios de nivelamento em Javascript.

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

 {console.log("Ops, você ainda não tem a idade mínima para dirigir!")}


### Exercício 14 - Condicional IF ELSE - Aposentado
Precisamos verificar se uma pessoa pode se aposentar com base na idade. Utilize a condicional if else para verificar se a variável idade é maior que 65 e imprima uma mensagem para cada caso:

Condição verdadeira : “Você já pode se aposentar”

Condição falsa: “Você ainda não pode se aposentar”


#### Solução:

var idade = 40

if (idade > 65){ console.log("Você já pode se aposentar")}
else{console.log("Você ainda não pode se aposentar")}


### Exercício 15 - Condicionais - IF ELSE - Par ou ímpar?
Dentro do código estará criada uma variável numeroDaSorte  contendo um número. Sua missão é verificar se o valor da variável é par ou ímpar utilizando o operador relacional módulo (%). Imprima “Par” ou “Ímpar” de acordo com o resultado.

#### Solução:

var numeroDaSorte = 18

if(numeroDaSorte %2 == 0){console.log("Par")} 

else {console.log("Ímpar")}
 

### Exercício 16 - Condicional ELSE IF - Petshop
Precisamos criar um código que ajude um petshop a dizer se o pet está com o peso ideal. E para isso eles deixaram para você as informações que eles usam para fazer essa classificação:

 - Abaixo de 4kg = "Abaixo do Peso"
 - Maior que 10kg = "Acima do Peso"
 - Se tiver entre esses dois valores =  "Peso normal"

Utilizando o ELSE IF e crie o código para suprir essa necessidade e imprimindo as mensagens de acordo com a lista acima!

#### Solução:

var petPeso = 7

if(petPeso<4){console.log("Abaixo do Peso")}

else if(petPeso>=4 <=10){console.log("Peso normal")}

else{console.log("Acima do Peso")}
 

### Exercício 17 - Condicional ELSE IF - Lados Iguais
Precisamos de ajuda para escrever um código que de acordo com a quantidade de lados iguais de um triângulo, exiba com console.log se ele é Equilátero, Isósceles ou Escaleno, sem a necessidade de repetir no código a palavra “triângulo”. 

− Triângulo Equilátero: possui os 3 lados iguais.	
− Triângulo Isósceles: possui 2 lados iguais.	
− Triângulo Escaleno: possui 3 lados diferentes

Nesse exercício a variável ladosIguais já estará definida.

#### Solução:

var ladosIguais = 0

if(ladosIguais == 3){console.log("Equilátero")}

else if (ladosIguais == 2){console.log("Isósceles")}

else{console.log("Escaleno")}


### Exercício 18 - Condicionais - Operadores lógicos - Pode subir?
Pode subir?

Um parque de diversão te contratou para criar um código para ajudar os usuários a saber se eles podem ir em uns dos brinquedos. As regras são:

- Ser maior que 1,50m ou ter 21 anos ou mais.


Diante disso, crie condições que supra essa necessidade, exiba a seguinte mensagem caso o usuário possa usar o brinquedo: “Você pode subir”. Caso ele não possa: “Desculpe, você não atende os requisitos para usar o brinquedo”.

Vale dizer que para esse exercício você terá duas variáveis: usuarioAltura e usuarioIdade

#### Solução:

let usuarioAltura = 170

let usuarioIdade = 21

if(usuarioAltura > 150 || usuarioIdade >= 21){ console.log("Você pode subir")}

else{console.log("Desculpe, você não atende os requisitos para usar o brinquedo")}


### Exercício 19 - Condicionais - Operadores lógicos
Posso comprar esse produto?

Queremos criar um código que ajude o usuário a saber se ele pode comprar um produto ou não. Para acontecer a venda, a quantidade do produto no estoque tem que ser maior que zero e o produto está ativo.


Para escrever este código, teremos duas variáveis já definidas: produtoQtd, produtoAtivo. 

Faça uma condição que supra a necessidade acima, se o usuário puder comprar o produto exiba a seguinte mensagem “Você pode finalizar essa compra”. Caso contrário exiba “Produto não está disponível para compra”.

#### Solução:

var produtoQtd = 3

var produtoAtivo = true

if(produtoQtd >0 && produtoAtivo){console.log("Você pode finalizar essa compra")}

else{console.log("Produto não está disponível para compra")}


### Exercício 20 - Condicional - Operadores lógicos - Banco
Será que posso ir ao banco?

Precisamos criar um código que ajude os usuários a saber se podem ir ao banco. Sabemos que o banco está aberto em todos os os dias da semana, exceto em  finais de semana. Caso o usuário possa ir ao banco você deve exibir com console.log a seguinte mensagem: “Você pode ir ao banco”, caso contrário, "O banco está fechado, tente outro dia".

Para esse exercício leve em consideração as seguintes informações:

- Dias da semana pro sistema: segunda, terca, quarta, quinta, sexta, sabado e domingo.
- Você terá a seguinte variável no código: diaSemana
- Para esse exercício você deve usar na condição do if o operador && para juntar as condições lógicas junto ao operador diferente de(!=).

#### Solução:

let diaSemana = 'sabado'

if(diaSemana != 'sabado' && diaSemana != 'domingo'){console.log("Você pode ir ao banco")}

else { console.log("O banco está fechado, tente outro dia")}


## Loops

### Exercício 21 - Loop For - Tabuada
Precisamos de um código que calcule a tabuada de multiplicação do 7 e imprima a expressão seguido do resultado. 
Exemplo:


7 x 1 = 07

7 x 2 = 14

7 x 3 = 21

7 x 4 = 28

7 x 5 = 35

7 x 6 = 42

7 x 7 = 49

7 x 8 = 56

7 x 9 = 63

7 x 10 = 70


Lembre-se de fazer a multiplicação do 7 x 1 até 7 x 10! 

Ah, uma última dica: Você deve usar a variável i que é nosso contador para concatenar na hora de montar a mensagem “7 x 1”!
Afinal os valores depois do " x " (1,2,3,4…) são os valores que mudam de acordo com cada interação do loop.

#### Solução:
var valor = 7;

for(var i = 1; i < 11; i++)

console.log(valor + " x " + i + " = " + valor * i)  


### Exercício 22 - Bom dia!
Vamos criar um robô que manda “Bom dia, grupo!” 7 vezes. Utilize o laço de repetição for para fazer com mais praticidade!

Bom dia, grupo!

Bom dia, grupo!

Bom dia, grupo!

Bom dia, grupo!

Bom dia, grupo!

Bom dia, grupo!

Bom dia, grupo!


#### Solução:
for(var i = 0; i < 7; i++){console.log("Bom dia, grupo!");}

### Exercício 23 - Loop com Array - Lucros
Uma empresa separou em uma lista, os valores dos lucros mensais. Com isso você terá no código um array com o seguinte nome: listaDeLucro contendo em cada posição o valor de recebido de cada mês!

var listaDeLucro = [100, 30, 300, -10, 600, 10]


Seu trabalho será criar um loop que calcule o valor total baseado nessa lista, e coloque o valor em uma variável já existente no código chamada: lucroTotal

#### Solução:

let listaDeLucro = [100, 30, 300, -10, 600, 10]

var lucroTotal = 0;

for (var i=0; i < listaDeLucro.length; i++) {lucroTotal = lucroTotal + listaDeLucro[i]}

console.log(lucroTotal)


### Exercício 24 -Loop com Array - Lista de Carros
Uma agência de carros quer exibir os itens do seu catálogo para os clientes. Eles exportaram os nomes dos carros no formato de array e guardamos essas informações na variável listaDeCarros que já vai estar disponível no código. 

Crie um loop que atenda o problema acima utilizando uma variável chamada i como contador. Use o console.log para exibir o nome dos carro de acordo com o exemplo abaixo:

“Nome do Carro: NOME_DO_CARRO”

#### Solução:

var listaDeCarros = [ "Fox", "Uno", "Gol", "Astra", "Fiesta"]

var frase = "Nome do Carro: "var numeroDePosicoes

for (let i = 0; i < listaDeCarros.length; i++) {console.log(frase + listaDeCarros[i])}


### Exercício 25 - Loop Array - Frutas
Um sacolão montou uma lista com as frutas que eles vendem, e de acordo com a fruta que o usuário busca eles querem informar se existe a fruta na lista ou não! 

var listaDeFrutas = [ "Uva", "Banana",  "Manga", "Cajá", "Pinha"]

Você deverá criar um loop que verifique se a fruta contida na variável busca existe na lista de frutas do sacolão. Se existe basta exibir uma mensagem, “Sim, temos a fruta banana disponível”. Use a variável busca para exibir o nome da fruta nessa mensagem de forma dinâmica. 

#### Solução:

var listaDeFrutas = ["Uva", "Banana", "Manga", "Cajá", "Pinha"];

var busca = "Banana"

for (var i=0; i < listaDeFrutas.length; i++){if (busca == listaDeFrutas[i]) {console.log('Sim, temos a fruta '+ busca +' disponível')}}


### Exercício 26 - Loop com Array - Saldo negativo
Uma empresa mandou uma lista contendo os números mensais de tudo o que ela faturou, e nosso trabalho é ajudá-los a criar um relatório que exiba em quantos meses eles tiveram o saldo negativo.


var listaDeGanhos = [10, 30, -10, -5, -1, 40]

Com base no array acima, que está disponível no código, faça um loop que verifique quantos meses tiveram valores negativos e armazene a contagem uma variável chamada totalNegativos que também está disponível no código.


#### Solução:

let listaDeGanhos = [10, 30, -10, -5, -1, 40]

let totalNegativos = 0

for(let i = 0; i< listaDeGanhos.length; i++){if(listaDeGanhos[i] < 0){ totalNegativos++; }}


### Exercício 27 - Break e Continue - Números Pares
Precisamos imprimir somente os números pares de 0 a 20. Mas temos alguns requisitos, você precisa utilizar, o loop for, o comando continue e o número deve ser o contador do loop! Vamos lá?

Dica: no seu for, utilize como contador uma variável chamada i.

#### Solução:
for ( let  i  =  0 ;  i  <=  20 ;  i ++ ) { if ( i % 2 != 0 ) { continue } 

else { console . log ( i )  } }


### Exercício 28 - Break e Continue - Bingo
Vamos criar um bingo, onde os números da cartela serão representados por um array chamado cartela, e o número sorteado deve ficar em uma variável chamada numeroSorteado. Seu trabalho será  verificar se existe o número sorteado na cartela, quando encontrar deve imprimir “Encontrei o número!” e parar o loop! 

#### Solução:
var cartela = [8, 13, 18, 22, 42, 49]

var numeroSorteado = 42

for(var i = 0; i < cartela.length; i++) {if(cartela[i] == numeroSorteado) {console.log("Encontrei o número!")
break}}



### Exercício 29 - Break e Continue - Sobrenome da família

Temos uma lista com nomes de todos os integrantes da família mas esqueceram de colocar o sobrenome! 
Seu desafio será imprimir nome junto com o sobrenome “Macedo” para cada integrante da família. Mas temos uma exceção, temos um integrante com sobrenome diferente, se tiver algum “Pedro”, coloque o sobrenome “Sousa”.

Joana Macedo

Felipe Macedo

Gabriela Macedo

Carlos Macedo

Pedro Sousa

Bruno Macedo


Dica: Utilize for  e continue para criar a solução.

  Acrescente um espaço antes do sobrenome, por exemplo: “ Sousa”. 

#### Solução:

var familia = ["Joana", "Felipe", "Gabriela", "Carlos", "Pedro", "Bruno"]

for (var i = 0; i < familia.length; i++){if (familia[i] == "Pedro") 

{console.log(familia[i] + " Sousa");

continue}console.log(familia[i] + " Macedo");}



### Exercício 30 - Break e Continue - Baralho
Temos um array em uma variável chamada baralho e precisamos de um script que procure a carta “Rei” entre as cartas do baralho. Assim que encontrar o “Rei” pare o loop utilizando break  e exiba um console.log a seguinte frase: Encontrei o Rei!

#### Solução:

let baralho = ["Ás", "Dama", "Rei", "Valete"]

for(let i = 0; i< baralho.length; i++){if(baralho[i] == "Rei")

{console.log("Encontrei o Rei!")
 break}}




## Funções

### Exercício 31 - Declarando funções - Listar produtos
Um mercado tem uma lista de produtos, que eles querem exibir para todo novo cliente que chegar! Como o processo é um pouco trabalhoso e repetitivo eles precisam do seu conhecimento em funções para ajudá-los.

Eles já tem um código, porém toda vez eles precisam reescrever o código para exibir ao cliente:

var lista = [ 'Leite', 'tomate', 'Biscoito', 'Tapioca']

for(var i = 0; i < lista.length; i++){console.log(lista[i])}

Seu trabalho é melhorar esse código, para ficar mais simples utilizá-lo. Precisamos que você transforme o código acima em uma função chamada listarProdutos.

#### Solução:

function listarProdutos(){
var lista = [ 'Leite', 'tomate', 'Biscoito', 'Tapioca']

for(var i = 0; i < lista.length; i++){console.log(lista[i])}}



### Exercício 32 -Declarando funções - Cartão de visita
Crie uma função chamada cartaoDeVisitas, ela deverá imprimir o seu nome em conjunto com sobrenome! 

Para isso lembre, da estrutura de que uma função deve ter. 

#### Solução:

function cartaoDeVisitas (nomeCompleto){var nome = "Evandro"

var sobrenome = "Orlandini"

var nomeCompleto= nome + " " + sobrenome 

{console.log (cartaoDeVisita) }
}

### Exercício 33 - Declarando funções - Tabuada do Sete
Uma professora quer ajudar os alunos a decorarem a tabuada do 7 exibindo o resultado para eles! 
Crie uma função chamada tabuadaDoSete que imprima a tabuada do sete utilizando um loop.

O resultado da sua função deve ser:

7 x 1 = 7

7 x 2 = 14

7 x 3 = 21

7 x 4 = 28

7 x 5 = 35

7 x 6 = 42

7 x 7 = 49

7 x 8 = 56

7 x 9 = 63

7 x 10 = 70


Nesse exercício, não é necessário executar sua função na solução.


#### Solução:

function tabuadaDoSete(){

for( var i = 1; i <= 10; i++) {console.log('7 x ' + i +' = ' +7*i) } }

   tabuadaDoSete()


### Exercício 34 -Funções parametrizadas - Menor Número
Escreva uma função chamada menorNumero. Ela deve receber dois números como parâmetro e retornar o menor entre eles. Caso os números sejam iguais, basta que se retorne qualquer um deles.

#### Solução:

function menorNumero(a,b){ if(a < b) {return a;}

else {return b;}}



### Exercício 35 -Funções parametrizadas - calculaValorDevido 2
Depois de nossa consultoria, a lavanderia DigitalLaundry percebeu que poderia deixar a sua cobrança mais sofisticada e justa. Ela decidiu cobrar R$10,00 fixo, a título de taxa de serviço (independente da quantidade de roupa), mais R$ 3,00 por quilo de roupa suja. Reescreva a função calculaValorDevido

function calculaValorDevido(pesoDeRoupaSuja){
	...
}

Essa função recebe como único parâmetro a quantidade de roupa suja. Ela deve retornar o valor a ser cobrado do cliente usando a nova política de preços.

#### Solução:

function calculaValorDevido(pesoDeRoupaSuja){ var preco = pesoDeRoupaSuja*3

   preco+=10

   return preco

}


### Exercício 36 -Funções parametrizadas - Autonomia
Os engenheiros de uma montadora estão projetando o computador de bordo de um carro. Eles precisam de uma função que possa calcular a autonomia atual do automóvel, em outras palavras, quantos quilômetros ele consegue andar com a quantidade de combustível atual. A autonomia pode ser obtida multiplicando a quantidade de combustível pelo rendimento. Será que você consegue ajudá-los?

Escreva uma função chamada autonomia:


function autonomia(quantidadeDeCombustivel, rendimento){
	...
}
 Essa função deve receber dois parâmetros:

O primeiro, que represente a quantidade de combustível que está no tanque
O segundo, que represente o rendimento do automóvel


A função deve retornar a autonomia do automóvel.

Lembre-se: a autonomia do automóvel pode ser obtido multiplicando o rendimento pela quantidade de combustível presente no tanque.

#### Solução:

function autonomia(quantidadeDeCombustivel, rendimento)

{	var autonomia = rendimento*quantidadeDeCombustivel

return autonomia}



### Exercício 37 - Funções parametrizadas - calculaValorDevido
A lavanderia DigitalLaundry lava roupa por quilo. Ela cobra dos seus clientes R$ 5,00 por cada quilo de roupa suja. Atualmente, eles usam um caderninho e uma calculadora para descobrir o valor que cada cliente tem a pagar. Precisamos automatizar essa empresa!

Escreva uma função calculaValorDevido

function calculaValorDevido(pesoDaRoupaSuja) {
	…
}

A função recebe como parâmetro o peso de roupa suja (em quilos) e deve retornar o valor a ser cobrado do cliente.

#### Solução:

function calculaValorDevido(pesoDeRoupaSuja){

   var preco = pesoDeRoupaSuja*5

   return preco}


### Exercício 38 - Usando funções - Começa com Maiúscula
O código abaixo já tem a função comecaComMaiuscula(palavra) definida. Essa função retorna true caso a palavra passada no parâmetro seja iniciada por uma letra maiúscula e false caso contrário. Use um for  com um contador i para imprimir para cada palavra no array de palavras as seguintes frases: “Começa com maiúscula” caso a palavra comece com maiúscula e “Não começa com maiúscula” caso contrário.


#### Solução:

function comecaComMaiuscula(palavra){
   return /^[A-Z]/.test(palavra);
}
 
var palavras = ["Amor", "copo", "Bolacha", "biscoito"];
 
 
for (var i = 0; i<palavras.length; i++){if(comecaComMaiuscula(palavras[i]))

{ console.log("Começa com maiúscula") } 

else {console.log("Não começa com maiúscula")}}



### Exercício 39 - Usando funções - Valida CPF
Para este exercício considere uma função que já foi definida, ela se chama validaCPF.

Esta função recebe um parâmetro que representa um possível CPF e tudo que ela faz resume-se em um único objetivo: retornar true caso o parâmetro seja um CPF válido ou false caso contrário. 


Eis aqui algo legal sobre funções: tudo que você precisa para utilizá-las é saber o que ela faz. Você não precisa ver como ela faz.


Utilize a função validaCPF para imprimir “CPF válido” caso o cpf “576.524.020-85” seja válido. Caso contrário, imprima “CPF inválido”

#### Solução:

//Lembre-se: a função validaCPF já está definida, mesmo que você não esteja vendo, basta executá-la!

validaCPF("576.524.020-85")

for(var i=0; i<validaCPF.lenght; i++){if(validaCPF[i]==true)

{console.log('CPF válido')}

else{ console.log("CPF inválido")}}



### Exercício 40 - Usando funções - Filtrar produtos
Uma loja virtual permite a seus visitantes filtrar produtos pelo preço. Existe um array com os preços dos produtos. Um programador já criou uma função maisBaratosQue(valor, precos) que retorna um array com os preços dos produtos mais baratos que o valor passado como parâmetro. Outro programador já criou uma função maisCarosQue(valor, precos) que retorna um array com os preços mais caros que o valor passado como parâmetro. Chegou sua vez!

Ao testar sua função com os valores: precosEntre(5, 10, [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]), o resultado é [ 5, 6, 7, 8, 9, 10 ].

[ 5, 6, 7, 8, 9, 10 ]


Crie uma função precosEntre(valorMenor, valorMaior, precos) que deve utilizar as funções maisBaratosQue e maisCarosQue para retornar os preços que estão entre o valorMenor e o valorMaior. Sua função deve receber então dois parâmetros:

valorMenor para representar o valor mínimo dos preços a serem listados

valorMaior para representar o valor máximo dos preços a serem listados

precos para representar um array com os preços dos produtos

Ela deve retornar um array com todos os preços entre valorMenor e valorMaior

#### Solução:

function maisBaratosQue(valor, precos) {
   return precos.filter(p => p <= valor);}

function maisCarosQue(valor, precos) {

   return precos.filter(p => p >= valor);}
   
function maisCarosQue(valor, precos) {

   return precos.filter(p => p >= valor);

}

function precosEntre(valorMenor, valorMaior, precos) {

   return maisCarosQue(valorMenor, maisBaratosQue(valorMaior, precos));}

console.log(precosEntre(5, 10, [1,2,3,4,5,6,7,8,9,10]));


### Exercício 41 - Usando funções - deixaEntrar
Uma rede de cinemas quer implementar um sistema para controlar a entrada nas suas salas. Os clientes, antes de entrar na sala, devem apresentar o RG em uma câmera. A câmera seria capaz de ler a data de nascimento do cliente e, caso ele não tenha idade suficiente para assistir a sessão, o acesso dele não seria autorizado.

Um dos programadores já fez uma função que calcula a idade com base na data de nascimento. Ela recebe como parâmetro uma data de nascimento no formato dd/mm/aaaa (dia com dois dígitos, mês com dois dígitos e ano com quatro dígitos) e retorna idade da pessoa hoje.


Precisamos agora que você escreva a função deixaEntrar(dataDeNascimento, censura).


A função deve receber dois parâmetros:

O primeiro deve representar a data de nascimento do cliente no formato dd/mm/aaaa 


O segundo deve representar a censura da sessão, ou seja, a idade mínima do cliente para que ele possa acessar a sala.


A função deve retornar true caso o cliente tenha idade maior ou igual a censura e false caso contrário.

#### Solução:

// A função a seguir (calculaIdade) não precisa ser alterada
// A sua função deve ser escrita logo abaixo desta
function calcularIdade(dataDeNascimento) {
   let [dia, mes, ano] = dataDeNascimento.split('/');
   const d = new Date();
   const anoAtual = d.getFullYear();
   const mesAtual = d.getMonth() + 1;
   const diaAtual = d.getDate();
   ano = +ano; mes = +mes; dia = +dia;
   let quantosAnos = anoAtual - ano;
   if (mesAtual < mes || mesAtual == mes && diaAtual < dia) {
       quantosAnos--;
   }
   return quantosAnos < 0 ? 0 : quantosAnos;}
 
// Escreva aqui sua função

function deixaEntrar(dataDeNascimento, censura)

{ return calcularIdade(dataDeNascimento, censura);}


### Exercício 42 -Funções Nativas - Estava presente na aula?
Nas escolas do futuro não haverá necessidade de chamadas. Ao entrar em sala, uma câmera fará o reconhecimento facial do aluno e registrará sua presença!
Imagine que, a cada aula, um array guardasse o nome de todos os alunos que estiveram presentes na aula.

Escreva uma função estavaPresenteNaAula(nomeDoAluno, nomesDosPresentes)

Essa função deve receber dois parâmetros:

O primeiro deve representar o nome de um aluno

O segundo deve representar um array com o os nomes dos alunos presentes.

A sua função deve retornar true caso o nome do aluno passado como parâmetro estiver entre os presentes. false caso contrário.

#### Solução:

function estavaPresenteNaAula(nomeDoAluno, nomesDosPresentes)

{if (nomesDosPresentes.indexOf(nomeDoAluno) != -1){return true;}

else{return false;}}



### Exercício 43 - Funções Nativas - Gerar Dezenas
Uma fábrica de biscoitos da sorte precisa de um sistema. O sistema deve gerar seis dezenas aleatórias para serem impressas. Sabe como é: Palpites para seus clientes jogarem na mega sena! O seu trabalho é escrever uma função gerarDezenas(). Essa função não recebe nenhum parâmetro. Tudo que ela deve fazer é gerar e retornar um array contendo seis números aleatórios entre 1 e 60.

#### Solução:

function gerarDezenas(){
array = []
for(var i = 0; i < 6; i++){
array.push(Math.round(Math.random()*60))}
return array}


### Exercício 44 - Funções Nativas - Maximo e Minimo
Escreva uma função maxmin(a, b, c, d, e) que receba cinco números como parâmetros.
Sua função deve retornar um array onde o primeiro elemento é o menor dos parâmetros da função maxmin e o segundo elemento é o maior dos parâmetros da função maxmin.

#### Solução:

function maxmin(a,b,c,d,e){

   var array=[0,0]

   array[0]=Math.min(a,b,c,d,e)

   array[1]=Math.max(a,b,c,d,e)

   return array}

//Caso queira testar a funçao

console.log(maxmin(1,2,3,4,5))



## Exercícios integradores


### Exercício 45 - Exercícios integradores -Variáveis, if e loop
No fim de semana o elevador do nosso prédio quebrou, restringindo muito o fluxo de pessoas. Considerando isso, apenas os moradores dos apartamentos com número par poderão usar o elevador.

Escreva um código que nos informe quais moradores poderão utilizar o elevador com base na variável moradores. O número do apartamento é a sua posição no array. O nome do morador é o valor.

Imprima no console a seguinte frase: 'O morador <nome do morador> pode usar o elevador', substituindo <nome do morador> pelo nome do morador.

#### Solução:
	
    var moradores = [

   "Fulano de Tal",

   "Beltrano da Cia",

   "Viajante do Tempo",

   "Morador da Lua",

   "Marciano Azul",

   "Et da Eslováquia",

   "Jedi do Lado Cinza da Força",

   "Baby Yoda Amarelo"]

   for(i=0; i<moradores.length; i++){

   if(i%2==0){console.log("O morador " + moradores[i] + " pode usar o elevador")}}
	
					
				
### Exercício 46 - Exercícios integradores - Dados de um usuário
Em uma  academia estão cadastrando nome, idade e altura de vários usuários.

Um determinado treino exige os seguintes requisitos: Ter 18 anos ou mais e ter uma altura igual ou maior a 1,70.

Crie uma função chamada maiorAlto. Essa função irá receber um array como parâmetro. Este array terá o nome na primeira posição, a idade na segunda posição e a altura em centímetros na terceira posição. Ela também deve retornar verdadeiro (true) caso o aluno atenda os requisitos, ou falso (false) caso contrário.

Exemplo:

maiorAlto(["João da Silva", 18, 170]) // retorna true
maiorAlto(["Arlete Moura", 17, 150]) // retorna false

#### Solução:
     
function maiorAlto (array)

{if(array[1] >= 18 && array[2] >=170 )

{return true}

else{return false}}
	
	
	
### Exercício 47 - Exercícios integradores - Academia
Uma academia precisa separar grupos de pessoas tendo como base as suas alturas. Temos um array alunos que contem a altura de cada aluno da academia.

Temos outros 3 arrays: grupoA, grupoB e grupoC. Eles devem ser preenchidos da seguinte forma: 


grupoA - Alunos com altura entre 150 a 159
grupoB - Alunos com altura entre 160 a 169
grupoC - Alunos com altura de 170 ou mais


Seu trabalho é pegar cada valor do array alunos e colocar o valor correspondente em seu respectivo grupo. Para esse exercício, você precisará usar loops, condicionais e funções de arrays. 
	
#### Solução:
	
var alunos = [170, 159, 151, 187, 156, 191, 165, 154, 167, 169, 171, 170, 160]

var grupoA = [159, 151, 156, 154 ];

var grupoB = [165, 167, 169, 160 ];

var grupoC = [170, 187, 191, 171, 170 ];

function zumbaClass(alunos) {

  for (var i = 0; i < alunos.length; i++) {

  if (grupoA[i] > 150 && alunos[i] <= 159) {

  grupoA.push(alunos[i])} 
					     
else if (grupoB[i] > 159 && alunos[i] < 170) 
						    
{ grupoB.push(alunos[i])} 
			
else if (grupoC[i] >= 170)
	
{grupoC.push(alunos[i]) }}}
	
	
### Exercício 48 - Exercícios integradores - Estacionamento
Um estacionamento deseja automatizar a cobrança de mensalistas. Para isso decidiu simplificar a forma de calcular o valor devido pelo seu cliente. A quantia a ser paga pelos seus usuários depende do número de entradas que o veículo realiza no estacionamento. A cada entrada, a placa do veículo é registrada. Ao final do mês, conta-se o número de entradas que o veículo realizou e faz-se o seguinte cálculo:
	
	

Se o motorista realizou até 20 entradas, ele deve pagar R$ 10,00 por entrada realizada.


Da vigésima primeira entrada em diante, cada entrada custa R$ 5,00 ao cliente.


	Agora, você deve ajudar na automatização da cobrança escrevendo duas funções.


A primeira função se chama calcularNumeroDeEntradas(placa). Ela deve receber um único parâmetro que representa a placa de um carro. A função deve retornar o número de entradas que esse carro realizou no estacionamento. Em outras palavras, o número de vezes que a placa passada como parâmetro aparece no array placas.


A segunda função se chama calcularValorDevido(placa). Ela deve receber um único parâmetro que representa a placa de um carro. A função deve calcular o valor que o proprietário do carro tem que pagar segundo a política de preços estabelecida. Naturalmente, será necessário utilizar a primeira função dentro da segunda.
	
	
	
#### Solução:
	
var placas = [

  'RXB-2525', 'AKX-3333', 'ORO-7142','RXB-2525', 'AKX-3333', 'ORO-7142',

  'AKX-3333', 'RXB-2525', 'AKX-3333','AKX-3333', 'RXB-2525', 'AKX-3333',   'RXB-2525', 'AKX-3333', 'ORO-7142','AKX-3333', 'AKX-3333', 'RXB-2525',

  'AKX-3333', 'ORO-7142', 'ORO-7142','AKX-3333', 'AKX-3333', 'RXB-2525',

  'AKX-3333', 'AKX-3333', 'RXB-2525','AKX-3333', 'AKX-3333', 'RXB-2525',

  'AKX-3333', 'ORO-7142', 'ORO-7142','AKX-3333', 'ORO-7142', 'ORO-7142',

  'ORO-7142', 'RXB-2525', 'AKX-3333','AKX-3333', 'ORO-7142', 'ORO-7142',

  'AKX-3333', 'RXB-2525', 'AKX-3333','AKX-3333', 'RXB-2525', 'AKX-3333',

  'RXB-2525', 'AKX-3333', 'ORO-7142','AKX-3333', 'AKX-3333', 'RXB-2525',

  'AKX-3333', 'ORO-7142', 'ORO-7142','AKX-3333', 'AKX-3333', 'RXB-2525',

  'AKX-3333', 'AKX-3333', 'RXB-2525','AKX-3333', 'AKX-3333', 'RXB-2525'

]

function calcularNumeroDeEntradas(placa){

  var cont = 0;

  for (var i = 0 ; i < placas.length ; i++) {

     if (placas[i] == placa) 
				    

{ cont++; } }

  return cont;}

function calcularValorDevido(placa){

  var numEntradas = calcularNumeroDeEntradas(placa);

  if (numEntradas <= 20) 
	
{ return 10.00 * numEntradas;} 
 else {return (200 + (numEntradas - 20) * 5);}}
	

### Exercício 49 - Exercícios integradores - Cinema
Em um site sobre cinema, os visitantes cadastrados podem dar notas de 0 a 5 para um filme que ele tenha assistido. Cada filme tem um grande array de notas atribuídas pelos visitantes. Contudo, além de dar notas para os filmes, os visitantes querem ver o que as outras pessoas acharam do filme! É aí que você entra com seu código:

Escreva uma função calculaGostos(notas)

Essa função deve ser escrita para receber somente um parâmetro: um array de notas. Ela deve retornar também um array com três elementos:

O primeiro, com a quantidade de notas iguais a 0 ou 1. Seriam os que não gostaram do filme

O segundo, com a quantidade de notas iguais a 2 ou 3. Seriam os que acharam o filme mediano

O terceiro, com a quantidade de notas iguais a 4 ou 5. Seriam os que gostaram do filme.
	
	

#### Solução:
	
function calculaGostos (notas) {

   var nNaoGostaram = 0;

   var nMediano = 0;

   var nGostaram = 0;

   for (var i = 0 ; i < notas.length ; i++) {

   if (notas[i] >= 0 && notas[i] < 2) { nNaoGostaram++; }  

      else if(notas[i] >= 2 && notas[i] < 4) { nMediano++;} 
					   
      else {nGostaram++;}}

   return [nNaoGostaram, nMediano, nGostaram];}
					    
					    
      Resultado da sua função = 3,2,1
				
				
				
				
				
				
