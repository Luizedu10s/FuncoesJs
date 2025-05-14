# FuncoesJs

Atividade da matéria de linguagem de script Ifpb sobre funções em Javascript

## Declaration

> A estrutura é simples, a função é chamada com "Function" logo depois é passado o nome da função e em seguida o parâmetro dentro dos parênteses seguido de um par de chaves onde será passado o bloco de código a ser executado.
'''
function Multiplicar(x, y){
    return x * y
}

Nessa função, ela recebe dois parâmetros x e y e retorna a adição dos dois parâmetros.

Exemplo:
Multiplicar(3, 5)
> saída: 15


## VANTAGENS 
'''
> Maior Legibilidade:
A declaração de função com function torna mais fácil identificar visualmente que uma declaração é uma função, facilitando a leitura e compreensão do código. 
> Hoisting:
Permite que a função seja chamada antes de sua definição, o que pode ser útil em algumas situações, como chamar a função no início de um script. 
> Flexibilidade na Organização:
A declaração de função permite uma organização mais flexível do código, pois a função está disponível em todo o escopo onde foi declarada. 


## DESVANTAGENS
'''
> Não permite funções anônimas:
Declarações de função sempre precisam de um nome, enquanto expressões de função podem ser usadas para criar funções anônimas (sem nome). 
> Possíveis problemas com escopo:
Em algumas situações, a declaração de função pode ter um escopo mais amplo do que o desejado, o que pode levar a problemas se a função não for usada no escopo que foi declarada. 


## Expression

> A estrutura é simples, a função é criada e instanciada dentro de uma variável logo depois é passado os parâmetros dentro dos parênteses seguido de um par de chaves onde será passado o bloco de código a ser executado.

let Multiplicar = function(x, y){
    return x * y
}

Nessa função, o nome dela é atribuido na variável, ela também recebe dois parâmetros x e y e retorna a adição dos dois parâmetros.
porém a execução é a mesma.
Exemplo:
Multiplicar(3, 5)
> saída: 15


## VANTAGENS 

> Flexibilidade:
As expressões de função podem ser atribuídas a variáveis, usadas como argumentos de outras funções e invocadas de forma imediata, o que proporciona maior flexibilidade e organização do código. 
> Funções anônimas:
Podem ser criadas funções sem nome, o que é útil para funções que são usadas apenas em um contexto específico.
> Maior precisão:
Em alguns casos, as expressões de função, especialmente as arrow functions, podem ser mais concisas do que as declarações de função, tornando o código mais legível. 


## DESVANTAGENS

> Manutenção:
pode dificultar a identificação e a compreensão do código, especialmente em contextos complexos ou em código grande. 
> Possíveis problemas com escopo:
Em algumas situações, a declaração de função pode ter um escopo mais amplo do que o desejado, o que pode levar a problemas se a função não for usada no escopo que foi declarada. 


## Arrow-Function

> A estrutura é mais simples ainda, a depender do problema a ser resolvido,ela pode ser escrita em apenas uma linha. Contém a mesma estrutura de uma função tradicional, porém, mais reduzida e segue passagem de parâmetros dentro dos parênteses seguido de um par de chaves onde será passado o bloco de código a ser executado.

Exemplo:
let Multiplicar = (x, y) => { x * y}

Exemplo:
Multiplicar(3, 5)
> saída: 15


## VANTAGENS 

> Melhor legibilidade e clareza:
A sintaxe concisa das arrow functions contribui para um código mais legível, e de fácil compreensão do que está sendo feito.  
> Em resumo: 
As arrow functions tornam o código mais limpo, legível e fácil de escrever, especialmente em situações que envolvem funções de curta duração.


## DESVANTAGENS

> Funções anônimas:
Arrow functions são sempre anônimas, o que significa que não possuem nome. pode gerar dificuldade na depuração e a compreensão do código, especialmente em situações onde é importante identificar qual função está sendo executada e do que ela se trata. 
> Sintaxe curta pode dificultar a compreensão em alguns casos:
Embora a sintaxe mais curta seja vantajosa em alguns casos, ela pode dificultar a compreensão do código para outros desenvolvedores, especialmente se a função for complexa. 
