## @175 #05_str L3 - Separando a partir de tokens
## @qxcode

![](__capa.jpg)

## Ação

Dada uma frase (max 100 char) com palavras (letras minusculas), números e espaço, divida os elementos em n frases usando os tokens ' # ' e ' ; ' como referência de fim para aquela frase.

### Entrada

* Uma frase (max 100 char) com palavras (letras minusculas), números e espaços que podem ser separados por tokens.

### Saida

* n frases sem os tokens.

## Exemplos

```
>>>>>>>>
mamae me ama#15#1.76;
========
mamae me ama
15
1.76
<<<<<<<<

>>>>>>>>
aa 4#1 -f; -2.0;
========
aa 4
1 -f
 -2.0
<<<<<<<<

>>>>>>>>
coca zero;1.75#8;U;
========
coca zero
1.75
8
U
<<<<<<<<
```

#