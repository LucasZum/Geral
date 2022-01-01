# Lista de Exercícios

1. Resolva as operações:


● 10 + 15 = 25
● “10” + 2 = '102'
● “10” * 2 = 20
● “10” / 3 = 3.3333333333333335
● “10” % 3 = 1
● 10 + true = 11
● 10 == ”10” = True
● 10 === “10” = False
● 10 < 11 = True
● 10 > 12 = False
● 10 <= 10.1 = True
● 10 > 9.99 = True
● 10 != “dez” = True
● 10 + true = 11 (repetida)
● “dez” + true = 'dez1'
● 10 + false = 10
● 10 * false = 0
● true + true = 2
● 10++ = Uncaught SyntaxError: Invalid left-hand side expression in postfix operation
● 10-- = Uncaught SyntaxError: Invalid left-hand side expression in postfix operation
● 1 & 1 = 1
● 1 & 0 = 0
● 0 & 0 = 0
● 1 & 0 = 0 (repetido)
● 0 / 1 = 0
● 5 + 5 == 10 = True
● “5” + ”5” == 10 = False
● “5” * 2 > 9 = true
● (10 + 10) * 2 = 40
● 10 + 10 * 2 = 30




2. Responda as perguntas de acordo com as variáveis.


var branco = “preto”;
var preto = “cinza”;
var cinza = “branco”;
var carro = “preto”;
var valor = 30000;
var prestacao = 750;



a) branco == “branco”
b) branco == cinza 
c) carro === branco
d) var cavalo = carro == “preto” ? “cinza” : “marron”;
e) Quantas prestações são necessárias para pagar o valor do carro com uma entrada
de 3.000? Demonstre a operação.
f) Somando as variáveis de cores é formada uma string de quantos caracteres?

Respostas:
a) False
b) False
c) False
d) cinza
e)
    30000 - 3000 = 27000
    27000 / 750 = 36
    resp: 36 Prestações

f) 21 caracteres, mas se colocarmos no Node, ele retornará o numero 20 porque a contagem se inicia no zero.