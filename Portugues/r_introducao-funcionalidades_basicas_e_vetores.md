# R Básico - Parte 1
Felipe Galvão  
25 de outubro de 2015  

# R Básico: Introdução - Funções básicas e Vetores

## Introdução

Olá pessoal,

Vamos começar a falar de R aqui. Para os que não sabem, R é uma linguagem de programação voltada para análises de dados, estatística, mineração de dados, aprendizagem automática (machine learning), entre outros. Criada por Ross Ihaka e Robert Gentleman, baseada na linguagem S (daí, o nome).

Para instalação do R, acesse aqui: [link](https://cran.r-project.org/)

Também é recomendável a utilização do Rstudio, excelente IDE para R, que você pode encontrar aqui: [link](https://www.rstudio.com/products/rstudio/download/)

Com ambos instalados, você pode entrar no Rstudio e começar a escrever suas instruções e scripts em R.

## Funcionalidades Básicas

Ao entrar no Rstudio, esta é a cara dele:

![](rstudio.png)

Você pode começar a escrever seu código no console. Digite "Ola mundo" no console e veja o que acontece


```r
"Ola, mundo"
```

```
## [1] "Ola, mundo"
```

O R mostra o que você escreveu, juntamente com este [1] do lado. Logo veremos o que este [1] significa, mas como podemos ver, o R printa de volta o resultado de comandos que você dá. Tente por exemplo uma soma


```r
3 + 5
```

```
## [1] 8
```

Agora, o R mostra o resultado da soma que você escreveu. O R tem as seguintes operações básicas:

Sinal | Operação
----- | ---------
+     | Soma
-     | Subtração
/     | Divisão
*     | Multiplicação
^     | Potência
sqrt  | Raiz quadrada

Vamos ver alguns exemplos de cada um deles:


```r
4+5
```

```
## [1] 9
```

```r
7-2
```

```
## [1] 5
```

```r
6*8
```

```
## [1] 48
```

```r
9/3
```

```
## [1] 3
```

```r
4^3
```

```
## [1] 64
```

```r
sqrt(25)
```

```
## [1] 5
```

Para guardar os valores em uma variável em R, usamos "<-". Neste caso, o print automático não ocorre, e caso queira checar qual é o valor daquela variável, basta digitar seu nome novamente, ou utilizar o comando print(nome_da_variavel). Vejamos:


```r
a <- 5 + 3
a
```

```
## [1] 8
```

```r
print(a)
```

```
## [1] 8
```

Esta é uma variável numérica. Em R, os dados também podem ser do tipo "character", que é uma variável de texto (em outras linguagens pode ser conhecida como "string") e "logical" (que em outras linguagens pode ser conhecida como "boolean"), e que assume os valores TRUE ou FALSE. Exemplos:


```r
b <- "Ola mundo"
c <- TRUE
print(b)
```

```
## [1] "Ola mundo"
```

```r
print(c)
```

```
## [1] TRUE
```

