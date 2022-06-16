# Exercicio-14-em-Java
Operadores incremento e descremento

Operadores de incremento e decremento
Da mesma forma que C e C, Java oferece operadores de incremento e decremento. 
De forma mais específica, oferece os operadores incremento de um () e decremen-
to de um (). Se tais operadores são usados na frente de um nome de variável, então 
1 é somado ou subtraído à variável, e seu valor é empregado na expressão. Se for utili-
zado depois do nome da variável, então primeiro o valor é usado, e depois a variável é 
incrementada ou decrementada de 1. Assim, por exemplo, o trecho de código
 int i -
 8;
 int j -
 i;
 int k -
 i;
 int m -
 i;
 int n -
 9  i;
atribui 8 para j, 10 para k, 10 para m, 18 para n e deixa i com o valor 10.
Operadores lógicos
Java oferece operadores padrão para comparações entre números:
 menor que
-
 menor que ou igual a
-
-
 igual a
 !-
 diferente de
-
 maior que ou igual a
 maior que
Os operadores -
-
 e !-
 também podem ser usados como referências para objetos. O 
tipo resultante de uma comparação é boolean.
Os operadores que trabalham com valores boolean são os seguintes:
 ! negação (prefixado)
 && e condicional
 | | ou condicional
Os operadores booleanos && e | | não avaliarão o segundo operando em suas 
expressões (para a direita) se isso não for necessário para determinar o valor da 
expressão. Esse recurso é útil, por exemplo, para construir expressões booleanas 
em que primeiro é testado se uma determinada condição se aplica (como uma re-
ferência não ser null) e, então, testa-se uma condição que geraria uma condição de 
erro, se o primeiro teste falhasse.
