![PARADIGMAS DE PROGRAMAÇÃO](https://github.com/isabelaacr/Paradigma-Prolog/assets/118640598/01130b5d-02e8-48bd-8ea2-0e9930ddd8f6)

  Revisão realizada para a disciplina de Paradigmas de Programação.

# Prolog
  Prolog, ou seja, programação lógica, é uma linguagem declarativa que se baseia no cálculo de predicados. Constituindo-se de uma coleção de fatos (base de dados) e regras (relações lógicas) realiza deduções para obter conclusões a partir de consultas realizadas pelos usuários. O que achei mais interessante em estudar Prolog foi a possibilidade da automação de tarefas e seu sistema de banco de dados baseado em lógica. Através de suas inúmeras possilibidades, permite a facilitação do estudo através da resolução de problemas de modo interativo e divertido, como a atividade realizada no repl.it de descobrir quem cometeu um assassinato em um hotel através de premissas.

![PROLOG](https://github.com/isabelaacr/Paradigma-Prolog/assets/118640598/1d3abdbb-19da-4e8d-9367-4b9aa5d5e6f7)

## Compilador
  Para as práticas foram utilizados os compiladores do repl.it e swish (https://swish.swi-prolog.org).

## Compreensão dos predicados
  Os predicados de prologs, sendo eles constantes ou variáveis (variáveis tem sua terminologia iniciada por maiúscula), são divididos em fatos e regras para a realização de uma consulta definida por meio deles. É válido ressaltar que todas as respectivas cláusulas são finalizadas com pontos finais. 

### Fato
  Expressam afirmações de um fato.
  
Frase: "Renata é estudante de programação"
Em prolog:
```Prolog
programming(renata).
```

### Regra
Cláusulas com condicionais.

Frase: "Todo estudante de programação é esforçado"
Em prolog: 
```Prolog
esforcado(x) :- programming(x).
```

## Programa movies.pl
  Primeira prática de prolog no menu Teams da disciplina na plataforma Repl.it. A realização dessa atividade proporciou a aprendizagem da modelagem de dados através do uso de predicados, a realização de consultas e aprimoramento do raciocínio lógico.

### Predicados da prática

![PROGRAMA MOVIES PL](https://github.com/isabelaacr/Paradigma-Prolog/assets/118640598/6cfd5cfc-f90d-45a8-98f4-34f803ca4d14)

### Banco de dados disponibilizado pela professora
![image](https://github.com/isabelaacr/Paradigma-Prolog/assets/118640598/56cf815b-5c1c-4868-ab3c-45912c0b201f)


### Consultas básicas 
Exemplo de consultas realizadas no programa movies.pl.

![CONSULTAS BÁSICAS](https://github.com/isabelaacr/Paradigma-Prolog/assets/118640598/341bdf26-b5dd-44b4-bfed-f4303d6cda22)

## Comandos no Swipl
  Para abrir o programa main.pl no interpretador de comandos utiliza-se o comando swipl main.pl no Shell.

![COMANDOS NO SWIPL](https://github.com/isabelaacr/Paradigma-Prolog/assets/118640598/8fe76030-469d-4eb8-a122-be97315591d7)

## Operador =

![OPERADOR =](https://github.com/isabelaacr/Paradigma-Prolog/assets/118640598/fef52c58-9e9b-49dc-8db4-e064153730f8)

## Variável anônima 

![VARIÁVEL ANÔNIMA](https://github.com/isabelaacr/Paradigma-Prolog/assets/118640598/bf4e8993-3671-44f3-9a99-923dfb3f874c)

## Listas e predicados

![LISTAS](https://github.com/isabelaacr/Paradigma-Prolog/assets/118640598/eca6607a-dc00-40a0-934d-cdca21de9515)

## Referências:
[1] Material disponibilizado pela professora
[2] https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjKpLK96aGCAxWBjZUCHYoaC3QQFnoECDgQAw&url=https%3A%2F%2Fwww.facom.ufu.br%2F~marcelo%2FPL%2Fapostila-prolog.pdf&usg=AOvVaw1cI4k7nAnULARYyeNpGHTc&opi=89978449

