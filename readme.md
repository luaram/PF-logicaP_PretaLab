# [Ciclo Formativo Básico em Tecnologia] Projeto final do módulo de JavaScript:


Bem vindas ao repositório do projeto final do módulo de JavaScript.

  1. Faça um fork desse repositório.
  2. Abra o arquivo `calculadora.js` e siga as instruções para para que as operações básicas passem a ser funcionais.
  3. Abra o arquivo `media.js` e siga as instruções para para que a soma passe a ser funcional.  
  4. [obrigatório] Por fim, publique no Netlify!
  
  # Calculadora

Este projeto é uma simples calculadora construída em JavaScript.

## Racional por Trás da Lógica da Calculadora

### Objetivo
O objetivo desta calculadora é fornecer operações básicas de aritmética, como adição, subtração, multiplicação,  divisão e média. A ideia principal foi criar uma interface simples e intuitiva para realizar cálculos de maneira eficiente.
### Estrutura do Projeto

1. **Interface do Usuário (UI)**
   - A interface foi projetada usando HTML e CSS .
   - Inclui caixa de entrada para usuário digitar números infinitos, para operações báicas (+, -, *, /, =).

2. **Lógica da Calculadora**
   - A lógica da calculadora foi implementada em Javascript.
   - A calculadora mantém um estado atual que inclui o número atual, o operador selecionado e o número anterior.

### Implementação

1. **Inicialização**
   - Quando a calculadora é iniciada, todos os valores são definidos para zero.

2. **Entrada do Usuário**
   - Quando um número é digitado, ele é adicionado ao número atual.
   - Quando um operador é clicado, o número atual é armazenado como o número anterior e o operador é salvo.

3. **Operações**
   - Ao clicar no operador selecionado, a operação é realizada usando o número anterior, o operador armazenado e o número atual.
   - O resultado é então exibido e usado como o número atual para operações subsequentes.

