test001: Validação de números iguais 
---
entrada: Primeiro número: 10 | Segundo número: 10
retorno_esperado: O sistema deve informar que os números são iguais.
resultado: Os dois números são iguais (Comportamento esperado. A lógica do if (num1 == num2) funciona perfeitamente para tipos primitivos como int).

test002: Validação de primeiro número maior 
---
entrada: Primeiro número: 50 | Segundo número: 25
retorno_esperado: O sistema deve informar que são diferentes e que o primeiro número é o maior.
resultado: Os números são diferentes seguido na linha de baixo por O primeiro número é maior. (Comportamento esperado. O aninhamento do if-else ocorreu de forma correta).

test003: Validação de segundo número maior com valores negativos
---
entrada: Primeiro número: -10 | Segundo número: 5
retorno_esperado: O sistema deve informar que são diferentes e que o segundo é maior.
resultado: Os números são diferentes seguido por O segundo número é maior. 

test004: Validação de entrada com tipo de dado incorreto 
---
entrada: Primeiro número: A
retorno_esperado: O sistema deveria avisar "Entrada inválida. Digite apenas números inteiros." e pedir a inserção novamente sem travar.
resultado: O sistema trava abruptamente e exibe um erro técnico no console (java.util.InputMismatchException). 

test005: Validação de números decimais 
---
entrada: Primeiro número: 10.5 ou 10,5
retorno_esperado: Como o texto na tela pede especificamente um número "inteiro", o sistema deveria rejeitar graciosamente a entrada ou arredondar o valor.
resultado: O sistema trava imediatamente com java.util.InputMismatchException. 
