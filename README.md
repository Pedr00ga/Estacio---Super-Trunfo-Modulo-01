# 🃏 Super Trunfo de Cidades (em C)

Este projeto simula uma versão do jogo **Super Trunfo**, onde duas cartas, representando cidades brasileiras, são comparadas com base em diferentes atributos como população, área, PIB, pontos turísticos, entre outros. O jogo determina qual cidade ganha em cada categoria e calcula a cidade vencedora geral.

## 📌 Objetivo

O programa permite ao usuário criar duas cartas com dados de cidades, e, em seguida, compara vários atributos dessas cidades, como população, área, pontos turísticos, densidade, PIB, PIB per capita, e uma **pontuação média** calculada a partir desses atributos.

## 🚀 Funcionalidades

* **Entrada de dados:** O usuário insere informações sobre duas cidades, incluindo nome, estado, população, área, pontos turísticos e PIB.
* **Cálculos automáticos:**

  * Densidade populacional
  * PIB per capita
  * Super Pontuação (SP): média dos atributos calculados
* **Comparação das cartas:** O programa compara os atributos entre as duas cidades e decide qual cidade ganha em cada categoria.
* **Exibição das cartas:** As cartas de cada cidade são exibidas com seus atributos.
* **Resultado final:** Após a comparação de todos os atributos, o programa mostra o vencedor da rodada.

## 🧮 Atributos comparados

O jogo compara as cidades com base nos seguintes atributos:

1. População
2. Área
3. Número de pontos turísticos
4. Densidade populacional
5. PIB
6. PIB per capita
7. Super Pontuação (SP): média dos atributos

## 🧑‍💻 Como funciona o código

1. **Entrada de Dados:**
   O usuário insere as informações de duas cidades, uma por vez, para criar duas cartas com dados de cidades brasileiras.

2. **Cálculos:**

   * Para cada cidade, são calculados a densidade populacional e o PIB per capita.
   * A **Super Pontuação (SP)** é calculada como a média de todos os atributos.

3. **Comparação:**
   O programa compara os atributos das duas cartas e atribui pontos para a cidade que tem o valor mais alto em cada categoria. Caso os atributos sejam iguais, nenhum ponto é atribuído.

4. **Resultado Final:**
   Ao final da comparação, o programa exibe o total de pontos de cada carta e anuncia o vencedor.

## 🧠 Aprendizados

Este projeto reforça conceitos de programação em C, como:

* Declaração de variáveis e tipos de dados (`char`, `int`, `float`, `unsigned long`)
* Leitura de dados do usuário (`scanf`)
* Cálculos matemáticos com variáveis do tipo `float` e `int`
* Estruturas de controle de fluxo (`if`, `else`)
* Exibição de resultados com `printf`

## 🏗️ Estrutura do Código

1. **Declaração das variáveis:** O código começa declarando as variáveis para as duas cartas, onde cada uma armazena informações sobre a cidade (nome, população, área, etc.).
2. **Entrada de dados:** O usuário é solicitado a fornecer as informações de cada cidade (duas cartas).
3. **Cálculos automáticos:** A densidade populacional e o PIB per capita são calculados.
4. **Comparação dos atributos:** Para cada atributo, o programa compara os valores e atribui pontos à carta vencedora.
5. **Resultado final:** O programa exibe o vencedor com base na pontuação total.

## 🧑‍💻 Como compilar e executar

Para compilar e executar o código, siga os seguintes passos:

1. **Compilar o código:**
   Abra o terminal e use um compilador C, como o `gcc`, para compilar o arquivo. No caso de um arquivo chamado `super_trunfo_cidades.c`, o comando seria:

   ```bash
   gcc super_trunfo_cidades.c -o super_trunfo
   ```

2. **Executar o programa:**
   Após a compilação, execute o programa com o seguinte comando:

   ```bash
   ./super_trunfo
   ```

## 🖥️ Exemplo de Saída

Após executar o programa, o usuário verá algo semelhante a isto:

```
Vamos desenvolver a primeira carta do jogo Super Trunfo!
Digite o nome do estado: SP
Digite o nome da cidade: Americana
Digite a populacao da cidade: 237240
Digite a area da cidade (m2): 133.9
Digite o numero de pontos turisticos da cidade: 20
Digite o PIB da cidade: 10000000

Vamos desenvolver a segunda carta
Digite o nome do estado: SP
Digite o nome da cidade: Sorocaba
Digite a populacao da cidade: 650000
Digite a area da cidade (m2): 450.5
Digite o numero de pontos turisticos da cidade: 15
Digite o PIB da cidade: 5000000

Carta 01
Estado: SP
Codigo: S01
Nome da Cidade: Americana
Populacao: 237240
Area: 133.90
Numero de Pontos Turisticos: 20
Densidade: 1775.91
PIB: 10000000.00
PIB per capita: 42.18

Carta 02
Estado: SP
Codigo: S02
Nome da Cidade: Sorocaba
Populacao: 650000
Area: 450.50
Numero de Pontos Turisticos: 15
Densidade: 1441.63
PIB: 5000000.00
PIB per capita: 7.69

Resultado Final:
Carta 1: 4 pontos
Carta 2: 2 pontos
A carta 1 ganhou!
```

---
