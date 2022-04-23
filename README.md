# Exerc�cio pertencente a disciplina de Engenharia de Software III

## Design Patterns

####Factory Method

Considere uma aplica��o que gerencie a contrata��o de funcion�rios. A empresa tem 3 tipos de funcion�rios: Funcion�rios de Tempo Integral, de Tempo Parcial e Tempor�rios.

Todos os funcion�rios tem id,nome e sal�rio;
- Funcion�rios de Tempo integral tem banco de horas;
- Funcion�rios de Tempo Parcial tem hora de entrada e hora de sa�da;
- Funcion�rios Tempor�rios tem dia, m�s e ano para o fim do contrato.

A classe de controle tem a opera��o de contrata��o que inicializa o funcion�rio com seus atributos e retorna o funcion�rio;

A classe main chama o novo funcion�rio e imprime seus atributos, simulando a grava��o em um BD;

Aplicar o Factory Method no diagrama, implementar em Java.
- Considere que pode-se, agora, contratar um estagi�rio que tem como atributo a institui��o parceira.