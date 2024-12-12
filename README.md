# JavaScript-Proz

## Variáveis, Operadores, Aritméticos e Concatenação

Atividades presentes nas aulas de Linguagem de Programação 

<sub> Q1. Crie um programa cujo objetivo é inserir seus dados pessoais (nome, idade, gênero e cidade) e armazenar em cada variável determinada e depois exibidos na tela. </sub>

<table>

```
var nome = prompt("Digite o seu nome")
var idade = prompt("Digite a sua idade")
var genero = prompt("Digite qual é o seu gênero") 
var cidade = prompt("Digite qual a sua idade")

document.write("<br> O nome digitado foi " + nome)
document.write("<br> A idade do usuário é " + idade)
document.write("<br> O gênero digitado foi " + genero)
document.write("<br> A cidade digitada é " + cidade)
```

</table>

<sub> Q2. Dado o cálculo 12 * 3 + 4 - 8 / 2 % 3, qual o resultado segundo a precedência de operadores?</sub>

<table>

```
var calculo = 12 * 3 + 4 - 8 / 2 % 3

document.write("O resultado de sua operação é " + calculo)
``` 
</table>


<sub>Q3. Crie um programa que utilize os métodos de Strings, onde o usuário envia uma frase e o programa exibe as informações dessa frase (tamanho, letra maiúscula, letra minúscula, substring e index) </sub>

<table>

```
var frase = prompt("Escreva uma frase")

document.write("<br> O tamanho da frase é " + frase.length)
document.write("<br> A frase com letra maiúscula " + frase.toUpperCase())
document.write("<br> A frase com letra minúscula " + frase.toLowerCase())
document.write("<br> A subtring escolhidas para a frase " + frase.substring(0,7))
document.write("<br> Index da frase " + frase.indexOf())
```

</table>


Index em HTML para mostrar cada código em tela.

<table>

```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temas 02 e 03 - Variaveis e Operadores</title>
    <style>
        
        body{
            background-color: bisque;
        }

    </style>
</head>
<body>
    
    <hr><h2><b>Questão 01</b></h2>
    <script src="Q1.js"></script>
    <hr><h2><b>Questão 02</b></h2>
    <script src="Q2.js"></script>
    <hr><h2><b>Questão 03</b></h2>
    <script src="Q3.js"></script>

</body>
</html>
```

</table>


