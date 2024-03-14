# Operadores em JavaScript

Aprendendo a utilizar os operadores na linguagem JavaScript

## operadores-aritmeticos

Inicialmente, declaramos as variáveis com a palavra `const`

~~~js
const numero1 = 30;
const numero2 = 20;
~~~

Depois, realizaremos as operações utilizando aritméticos:

* `+`: soma  dois números
* `-`: subtrai dois números
* `*`: multiplica dois números
* `/`: divide dois números
* `%`: obtém o resto da divisão de dois números 

~~~js
console.log(`A soma dos números é: ${numero1 + numero2}`)
console.log(`A subtraçaão dos números é: ${numero1 - numero2}`)
console.log(`A multiplicação dos números é> ${numero1 * numero2}`)
console.log(`A divisão dos números é: ${numero1 / numero2}`)
console.log(`O resto da divisão dos números é: ${numero1 % numero2}`)
~~~


As operações são realizadas no momento da impressão do resultado e não necessitam ser armazenadas


## operadores-atribuicao.sj

~~~js
let numero = 10;
~~~

Declaramos a variável `número`´usando a palavra reservada `let`, pois
essa variável será reatribuida ao longo do nosso código.

Em seguida, fazemos uma série de reatribuição utilizando 
os operadores de atribuição.

~~~js
console.log(`O número inicial é: ${numero}`)
console.log(`Somando 10: ${numero +=10}`);
console.log(`Subtraindo 10: ${numero -= 10}`);
console.log(`multiplicando por 10: ${numero *= 10}`);
console.log(`dividindo por 10: ${numero /= 10}`);
console.log(`Elevando á potência de 10: ${numero **=10} `);
console.log(`Obtendo o resto da Divisão por 10: ${numero %=10} `);
console.log(`Incrementando 1: ${++numero}`);
console.log(`Decrementando 1: ${--numero}`);
console.log(`O número final é: ${numero} `);
~~~

Operadores de atribuição

* `=` -> atribui um novo valor para a variável
* `+=` -> o própio valor somado ao novo valor
* `-=` -> o própio valor subtraindo-se o novo valor
* `*=` -> o própio valor multiplicado pelo novo valor
* `/=` -> o própio valor dividido pelo novo valor
* `**=` -> o própio valor elevado a potência do novo valor
* `%=` -> o resto da divisão do própio valor pelo novo valor
* `++` -> o própio valor **incrementado (somado) com 1** (pode ser
um _pré-incremento_ ou _pós-incremento_)
* `--` -> o própio valor **decrementado (subtraído) com 1** (pode
ser um _pré-decremento_ ou um _pós-decremento_)
