# Exercício pertencente a disciplina de Engenharia de Software III

## Design Patterns

####Factory Method

Considere uma aplicação que gerencie a contratação de funcionários. A empresa tem 3 tipos de funcionários: Funcionários de Tempo Integral, de Tempo Parcial e Temporários.

Todos os funcionários tem id,nome e salário;
- Funcionários de Tempo integral tem banco de horas;
- Funcionários de Tempo Parcial tem hora de entrada e hora de saída;
- Funcionários Temporários tem dia, mês e ano para o fim do contrato.

A classe de controle tem a operação de contratação que inicializa o funcionário com seus atributos e retorna o funcionário;

A classe main chama o novo funcionário e imprime seus atributos, simulando a gravação em um BD;

Aplicar o Factory Method no diagrama, implementar em Java.
- Considere que pode-se, agora, contratar um estagiário que tem como atributo a instituição parceira.