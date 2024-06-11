# Projeto_ULA
Projeto da Cadeira de Sistemas Digitais do Curso de Engenharia da Computação

## Descrição
O projeto consisite em uma ULA no nível de abistração de Portas Lógicas.
Utilizamos o programa Intel Quartus Prime na versão 20.1 para desenvolver os diagramas de Portas Lógicas.
Para executar, usamos a placa de Prototipação Altera DE2-115 com o processador da série CycloneIV E.

## Grupo
* Antonio Lins Gomes de Mattos (algm)
* Henrique Alves Passos (hap)

## Projeto
O projeto da ULA precisa ser acoplado a um decodificador binário para display de sete
segmentos que também será desenvolvido. Este projeto da primeira unidade deve ser
desenvolvido totalmente baseado em portas lógicas.
O projeto deve estar pronto para baixar na placa de prototipação DE2-115, inclusive
com as pinagens configuradas. As respectivas pinagens (associação de um sinal
entrada/saída com um pino do FPGA)

A unidade lógica e aritmética deverá ser capaz de executar as seguintes operações,
que serão selecionadas a partir dos códigos da tabela abaixo:

| $S_2$ | $S_1$ | $S_0$| Função |
| --- | --- | --- | --- |
| 0 | 0 | 0 | A + B |
| 0 | 0 | 1 | A - B |
| 0 | 1 | 0 | Complemento a 2 de B |
| 0 | 1 | 1 | A = B |
| 1 | 0 | 0 | A > B |
| 1 | 0 | 1 | A < B |
| 1 | 1 | 0 | A AND B |
| 1 | 1 | 1 | A XOR B |

#### Entradas
1. Dois vetores A e B de 5 bits (1 para o sinal e 4 para o módulo). Se o número for
negativo, o bit mais significativo deve ser 1 caso contrário 0.
2. Um vetor de 3 bits para as entrdada de Seleção

#### Saidas
1. Um vetor F de 5 bits (todos representam o módulo) para o resultado das operações
   que retornam vetor. Tem que ser representados por 5 LEDs na forma binária
2. Um bit representando o sinal (1 negativo, 0 positivo). Representado por 1 LED
3. Um bit para o resultado das funções booleanas (comparador). Representado por 1 LED
4. Displays de 7 segmentos para representar as entradas A e B e a saída F no formato decimal


## Imagens

Diagrama do Projeto:

![Diagrama do projeto](https://github.com/Henrique-apassos/Projeto_ULA/assets/149020511/3e3db5ec-6524-4906-8df5-f1c221b56c88)

Placa:
![Plaquinha](https://github.com/Henrique-apassos/Projeto_ULA/assets/149020511/0df7ce12-0c60-4fd6-bc1a-c063f551499c)

