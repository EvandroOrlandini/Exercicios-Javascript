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


### Exercício 24 - Loop Array - Frutas
Um sacolão montou uma lista com as frutas que eles vendem, e de acordo com a fruta que o usuário busca eles querem informar se existe a fruta na lista ou não! 

var listaDeFrutas = [ "Uva", "Banana",  "Manga", "Cajá", "Pinha"]

Você deverá criar um loop que verifique se a fruta contida na variável busca existe na lista de frutas do sacolão. Se existe basta exibir uma mensagem, “Sim, temos a fruta banana disponível”. Use a variável busca para exibir o nome da fruta nessa mensagem de forma dinâmica. 

#### Solução:

var listaDeFrutas = ["Uva", "Banana", "Manga", "Cajá", "Pinha"];

var busca = "Banana"

for (var i=0; i < listaDeFrutas.length; i++){if (busca == listaDeFrutas[i]) {console.log('Sim, temos a fruta '+ busca +' disponível')}}


### Exercício 25 - Loop com Array - Saldo negativo
Uma empresa mandou uma lista contendo os números mensais de tudo o que ela faturou, e nosso trabalho é ajudá-los a criar um relatório que exiba em quantos meses eles tiveram o saldo negativo.


var listaDeGanhos = [10, 30, -10, -5, -1, 40]

Com base no array acima, que está disponível no código, faça um loop que verifique quantos meses tiveram valores negativos e armazene a contagem uma variável chamada totalNegativos que também está disponível no código.


#### Solução:

let listaDeGanhos = [10, 30, -10, -5, -1, 40]

let totalNegativos = 0

for(let i = 0; i< listaDeGanhos.length; i++){if(listaDeGanhos[i] < 0){ totalNegativos++; }}





#### Solução:
#### Solução:


## Funções



## Exercícios integradores
