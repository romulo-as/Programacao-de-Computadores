Alunos:  
Rômulo Andrade de Santana  
Jean Salton  
Deivid Gomes Enéias  
Anderson Gomes dos Santos  
  
# Estrutas de Controle do fluxo de Execução
Essas são estruturas de programação que permitem definir a sequência de execução
dos comandos de um programa, em função das instruções do mesmo,
são classificadas em:  
  * Estruturas sequenciais  
  * Estruturas de decisão  
  * Estruturas de repetição  

## Seção 01 - Estrutura Sequencial  

Nesta estrutura de programação, os comandos de um algoritmo/
programa são executados numa sequência preestabelecida. Cada
comando é executado somente após o término do comando anterior, ou
seja, de forma sequencial, de cima para baixo e na ordem em que foram
definidos.

Exemplo prático em sequencial.py

## Seção 02 - Estruturas de Decisão

Nas estruturas de decisão o computador adquire um certo
ar de inteligência, não confundir esta metáfora com Inteligência
Artificial, pois ele passa a tomar decisões e executar determinadas
operações simplesmente em função de uma condição lógica, que
corresponde a uma expressão lógica. Neste tipo de estrutura, o fluxo
de execução das instruções de um programa pode ser escolhido, em
função do resultado da avaliação lógica de uma ou mais condições.

As condições lógicas consistem na avaliação do estado de
variáveis ou de expressões, avaliações estas que sempre terão como
resultado um valor lógico .V. (Verdadeiro) ou .F. (Falso).

As estruturas de decisão são classificadas de acordo com o número
de condições que devem ser avaliadas, resultando em dois tipos: Se,
Escolha.

### Estruturas de Decisão do tipo Se
Na estrutura de decisão do tipo Se, apenas uma expressão lógica
(condição) é avaliada. Quando o resultado da condição lógica for
Verdadeiro, então um determinado comando simples ou conjunto de
instruções (comando composto) é executado, caso contrário, quando falso,
um comando ou conjunto de instruções diferente é executado, podendo
ser um conjunto vazio, ou seja, não existir comando(s) para a condição de
falso e o programa prossegue a execução

Exemplo prático em decisao_idade.py

## Seção 03 - Estruturas de Repetição
São também chamadas de Laços ou Loops e correspondem a uma
modalidade de estrutura de programação em que o objetivo é repetir,
iterar, determinado trecho de um programa, certo número de vezes.

A repetição de partes de um programa é uma situação que além de
útil é muito comum em programação de computadores, pois facilita a
reutilização de códigos-fonte, trechos de programas. Por exemplo, um
programa que executa um cálculo financeiro em que a fórmula seja a
mesma, mas os valores podem ser diferentes e incrementados em razão
de uma situação temporal.

As estruturas de repetição possuem uma característica peculiar,
pelo fato de estarem diretamente ligadas às estruturas de decisão, pois,
conforme será visto, o controle das repetições e interrupções ocorre em
função de expressões lógicas e condições.

As estruturas de repetições são classificadas pelo conhecimento
prévio, ou não, do número de vezes em que um conjunto de comandos
compostos deverá ser executado, laços, dividindo-se em:
* Laços contados – quando se conhece, previamente, quantas
vezes o comando composto no interior do laço deverá ser
executado.
* Laços condicionais – quando não se conhece o número de vezes
que o comando composto no interior do laço será repetido, pelo
fato de que a interrupção está vinculada a uma condição sujeita
a modificações pelas instruções do interior do laço.

Laços Contados
São aqueles em que há um mecanismo para contar o número de
vezes que o corpo do laço, comando composto, em seu interior, deverá
ser executado. Os laços contados também são chamados de Para-passo.

Exemplo Prático em repeticao_for.py

Construção Enquanto
Tem como característica principal o fato de ser uma estrutura
que realiza o teste lógico, condição, no início do laço, verificando se é
permitido ou não executar o conjunto de comandos no interior do laço.
Sendo assim, é necessário que exista uma ou mais variáveis com valores
associados antes da execução da estrutura de repetição em si.

Com relação ao funcionamento da construção Enquanto, como a
condição é testada no início, se o resultado for falso, então o comando composto
no seu interior não é executado e a execução prossegue normalmente pela
instrução seguinte ao final da estrutura de repetição, Fim_enquanto.

Caso a condição seja verdadeira, o comando composto é executado
e, ao término, é realizado outro teste da condição, este processo se repete
enquanto a condição for verdadeira. Quando a condição for falsa, o
processo de repetição é interrompido e o fluxo de execução do algoritmo/
programa prossegue normalmente pela instrução seguinte ao final da
estrutura de repetição.

O programador sempre deve estar atento ao fato de que em algum
momento no comando composto, possa ocorrer em que a condição assuma
a condição de falso, caso contrário o programa permanecerá executando
indefinidamente o comando composto, laço infinito.

Exemplo prático em repeticao_while.py  

 
Este material se encontra no livro "Algoritmos e Programação I EBOOK.pdf:
* ESTRUTURAS DE CONTROLE DO FLUXO DE EXECUÇÃO (página 103)
* SEÇÃO 1- ESTRUTURA SEQUENCIAL (página 104)
* SEÇÃO 2- ESTRUTURAS DE DECISÃO (página 114)
* SEÇÃO 3- ESTRUTURAS DE REPETIÇÃO (página 135)