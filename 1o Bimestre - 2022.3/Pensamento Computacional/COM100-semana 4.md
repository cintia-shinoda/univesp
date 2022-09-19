# SEMANA 4 - RACIOCÍNIO LÓGICO, ANÁLISE E RESOLUÇÃO DE PROBLEMAS: ESTRATÉGIAS DE ORDENAÇÃO

## Objetivos da semana:


## Videoaula 10 - Tarefas de busca e estratégias de solução: busca sequencial
https://youtu.be/3t5p308k7g8

- CPU acessa somente uma posição de cada vez
- Notação de diagrama de fluxo
- busca sequencial: do primeiro ao último
- elemento a ser buscado -> chave de busca

## Quiz: videoaula 10
Assim como a CPU só acessa uma posição de memória de cada vez, o algoritmo de busca sequencial também acessa um a um os elementos disponíveis e, a cada acesso, compara o valor do elemento acessado com o elemento a ser buscado (este último também chamado de chave de busca). O diagrama de fluxo do algoritmo de busca sequencial está ilustrado na figura.

Escolha a alternativa que completa, correta e respectivamente de cima para baixo, as lacunas.

|   |    |
|:---|:---|
| &check; | primeiro; último; próximo elemento |
|  | primeiro; último; primeiro elemento |
|  | primeiro; último; elemento anterior |
|  | último; primeiro; próximo elemento |
|  | primeiro; primeiro; próximo elemento |


## Videoaula 11 - Tarefas de busca e estratégias de solução: qual o maior e qual é o custo?
https://youtu.be/25Q6fMvjXXw

### identificar o maior/menor elemento
- comparações

### custo computacional


## Quiz: videoaula 11
Nesta aula discutimos o algoritmo de busca pelo maior elemento de uma lista. O diagrama de fluxo do algoritmo está ilustrado na figura.
Escolha a alternativa que completa, correta e respectivamente de cima para baixo, as lacunas.

|   |    |
|:---|:---|
|  | primeiro, primeiro, último, primeiro, maior |
| &check; | primeiro, primeiro, último, próximo, maior |
|  | primeiro, último, último, próximo, maior |
|  | primeiro, primeiro, primeiro, próximo, maior |
|  | primeiro, primeiro, último, próximo, menor |


## Videoaula 12 - Tarefas de busca e estratégias de solução: busca binária
https://youtu.be/5b7TgOhLNcw

### Busca binária
- dividir em 2
- número de comparações em lista com n elementos: log de n na base 2

## Quiz: videoaula 12
Nesta aula discutimos o algoritmo de busca binária. O diagrama de fluxo do algoritmo está ilustrado na figura.
Escolha a alternativa que completa, correta e respectivamente, de acordo com a numeração, as lacunas.

|   |    |
|:---|:---|
|  | dir; esq; esq; meio |
|  | esq; dir; meio; dir |
|  | esq; dir; dir; esq |
|  | dir; esq; esq; dir |
| &check; | esq; dir; esq; dir |