# SEMANA 3 - DISPOSITIVOS COMPUTACIONAIS: INTERNET, WEB, EAD

## Objetivos da semana:


## Videoaula 07 - Dispositivos computacionais: histórico e aplicações
https://youtu.be/2pwUbRie__Q

Destaques da História relevantes para a área de Computação:
- contagem: pedra, madeira e ideias
- algoritmo para multiplicar dois números: 
    - John Napier e Joost Burgi
    - logaritmo = inverso da exponencial
- George Boole - álgebra booleana/binária
- Alan Turing - máquina de Turing (3+2) - unária
- primeiros computadores pessoais
- celulares, relógios, drones...


## Quiz: videoaula 07
Inúmeras personalidades contribuíram para e evolução da computação com a utilizamos hoje em dia. Reconheça algumas dessas personalidades e suas contribuições correlacionando adequadamente as afirmações abaixo. 

John Napier, nascido em 1550.  

Joost Bürgi, nascido em 1552. 

George Boole, nascido em 1815. 

Alan Turing, nascido em 1912. 

 
I. É reconhecido por ter criado o conceito de logaritmo como ferramenta para multiplicação e divisão de números grandes.  

II. É reconhecido por ter criado a álgebra que utilizamos em nossos programas para expressões condicionais. 

III. Sua Máquina Universal corresponde ao conceito de programa armazenado. 

IV. É considerado o pai da Ciência da Computação.  

Assinale a alternativa que correlaciona adequadamente os dois grupos de informação: 

|   |    |
|:---|:---|
|  | 1-III, 2-I, 3-IV, 4-III |
|  | 1-I, 2-II, 3-IV, 4-III |
|  | 1-I, 2-II, 3-III, 4-IV |
|  | 1-I, 2-I, 3-II, 4-III, 4-IV |
|  | 1-II, 2-I, 3-III, 4-IV |


## Videoaula 08 - Computador: Programas, CPU & Lógica Binária
https://youtu.be/L491uqFdzZA

### Programa
- é um conjunto de instruções
- sequência-repetição-condicional
- antes de ser executado, o programa deve ser
    - transformado em código binário
    - armazenado na memória

### Estrutura básica de um computador
- Processador (CPU)
- Memória (matriz-linhas e colunas)
- Entrada
- Saída

- 8 bits = 1 byte

- lógica binária

- computador precisa representar
    - instruções
    - endereços
    - dados
- usando apenas a lógica binário
    - V ou F
    - 0 ou 1

- 5 elementos 0 ou 1 -> 32 códigos
- cada código pode representar uma instrução/caractere


### Operadores Lógicos
- E
- OU
- NOT


## Quiz: videoaula 08
Tanto a representação de valores numéricos na base 2 quanto a lógica binária baseiam-se em dois únicos valores, 0 e 1.

Dadas as afirmações:

I. O valor 1010 na base 2 é calculado como 1x23 + 0x22 + 1x21 + 0x20.

II. O valor 0101 na base 2 é calculado como 0x24 + 1x23 + 0x22 + 1x21.

III. O valor 0101 na base 2 é calculado como 0x23 + 1x22 + 0x21 + 1x20.

IV. Se A=1 e B=0, a expressão (A e B) resulta no valor 1.

V. Se A=1 e B=0, a expressão (A ou B) resulta no valor 1.

VI. Se A=0 e B=1, a expressão (A ou B) resulta no valor 1.

VII. Se A=1 e B=0, as expressões (não A) e (não B) resultam, respectivamente, em 0 e 1.

Qual alternativa corresponde às afirmações corretas? 

|   |    |
|:---|:---|
|  | I, III, V, VI. |
|  | II, IV, VI, VII. |
|  | II, V, VI, VII. |
|  | I, III e VII. |
| &check; | I, III, V, VI, VII. |


## Videoaula 09 - Computador: circuitos binários
https://youtu.be/SyKYW1b0mUg

### Circuitos Lógicos Básicos
- esses circuitos
    - são implementados com semicondutores
    - são bem pequenos

- combinação
    - de alguns -> circuito somador de números binários
    - de bilhões -> um processador moderno

#### Circuito NÃO
X = A'

Tabela verdade

| A | X |
|:---:|:---:|
| 0 | 1 |
| 1 | 0 |

#### Circuito E
X = A * B

Tabela verdade
| A | B | X |
|:---:|:---:|:---:|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

#### Circuito OU
X = A + B

Tabela verdade
| A | B | X |
|:---:|:---:|:---:|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

#### OU-EXCLUSIVO


#### NÃO-E
X = (A * B)'


#### NÃO-OU
X = (A + B)'


## Quiz: videoaula 09
Tanto a representação de valores numéricos na base 2 quanto lógica binária baseiam-se em dois únicos valores, 0 e 1. Apesar de serem apenas dois os valores possíveis, é muito simples realizar operações lógicas básicas, baseadas na Álgebra de Boole, a partir das quais todas as operações mais complexas podem ser implementadas. Um exemplo é a operação indicada na figura. 

Escolha a alternativa que completa, correta e respectivamente, as lacunas. 

|   |    |
|:---|:---|
|  | 0, 1, 0, 1. |
|  | 0, 1, 1, 1. |
| &check; | 1, 1, 1, 0. |
|  | 1, 1, 0, 0. |
|  | 0, 1, 1, 1. |
