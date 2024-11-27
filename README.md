# Lista Sequencial Ordenada com Redimensionamento Dinâmico em C++

## Descrição

Este projeto implementa uma lista sequencial ordenada em C++ que suporta redimensionamento dinâmico. A lista é capaz de expandir ou reduzir seu tamanho automaticamente conforme o número de elementos inseridos ou removidos, garantindo eficiência na utilização de memória e manutenção da ordem dos elementos.

## Funcionalidades

1. **Capacidade Inicial**: A lista começa com uma capacidade inicial de 50 elementos.
2. **Expansão Dinâmica**: Quando a lista atinge a capacidade máxima, seu tamanho é duplicado usando alocação dinâmica de memória.
3. **Redução Dinâmica**: Para economizar memória, a capacidade da lista é reduzida pela metade quando o número de elementos cai para 25% da capacidade total.

## Operações Principais

- **Inserção de Elementos**: Elementos são inseridos de forma ordenada. Se a lista estiver cheia, a capacidade é expandida antes da inserção.
- **Remoção de Elementos**: Elementos podem ser removidos da lista. Se o número de elementos cair para 25% da capacidade atual, a capacidade é reduzida para economizar memória.
- **Exibição da Lista**: A lista pode ser exibida mostrando todos os elementos em ordem.

## Como Usar

1. **Compilação**: Compile o código utilizando um compilador C++ (por exemplo, g++).
    ```sh
    g++ -o ordered_list main.cpp
    ```
2. **Execução**: Execute o programa compilado.
    ```sh
    ./ordered_list
    ```

## Exemplos de Uso

Ao executar o programa, ele demonstrará a inserção de 55 elementos na lista, exibirá a lista e suas propriedades (tamanho e capacidade), removerá 50 elementos e exibirá novamente a lista e suas propriedades atualizadas.

## Considerações Finais

Este projeto mostra como gerenciar a memória dinamicamente em C++, garantindo que a lista permaneça eficiente tanto em termos de tempo quanto de espaço. A implementação foca em manter a lista ordenada e em ajustar a capacidade conforme necessário para otimizar o desempenho.
