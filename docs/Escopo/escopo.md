
# Escopo Geral do Compilador

O compilador deste projeto foi delimitado de forma clara, de modo a assegurar que sua implementação seja realizável dentro do tempo disponível. As funcionalidades selecionadas foram definidas levando em conta tanto a importância para a utilização prática da linguagem Python quanto a possibilidade de conversão adequada para a linguagem C.

## Tipos de Dados Suportados

O compilador oferece suporte aos seguintes tipos de dados:

* int;
* float;
* double;
* char;
* string;
* boolean.

## Operações e Expressões
As operações implementadas incluem:

* **Operações aritméticas básicas:** adição (+), subtração (-), multiplicação (*), divisão (/) e módulo (%)

* **Operadores relacionais:** ==, !=, <, <=, >, >=

* **Operadores lógicos:** and, or, not (traduzidos para &&, || e ! em C)

## Entrada e Saída
São suportadas as seguintes funções de entrada e saída:

```print``` — para exibir valores na saída padrão

```scan``` — para leitura de valores da entrada padrão

## Estruturas de Controle
O compilador reconhece e traduz as seguintes estruturas de controle de fluxo:

* **Condicionais:** if, elif, else

* **Laços de repetição:** for, while

## Funções
Por fim, também está incluído no escopo o suporte à definição e chamada de funções, permitindo reutilização de trechos lógicos.

<br>

-------
## Escopo do Primeiro Ponto de Controle




implementar no sintatico
- Condicionais (if, elif, else)
- Laços (while, for)
- Definição de funções
- Declaração e uso de listas
- Dicionários

- Condicionais (if, elif, else)
- Laços (while, for)
- Definição de funções
- Declaração e uso de listas

falta adicionar mais regras e estruturar a indentação pra implementar laços e condicionais

- Léxico (completo, reconhecendo variáveis, condicionais, loops, tipos, etc. )
- Sintático (parcialmente, ...)

regras de expressões matemáticas, atribuição de variáveis, chamada de funções e início de estrutura de indentação e de mensagens de erro