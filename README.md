# Cálculo da Raiz Digital

## Contextualização

O objetivo deste projeto é desenvolver uma função que calcula a raiz digital de um número. Esta é uma operação onde os dígitos de um número são somados repetidamente até que apenas um dígito permaneça.

**Exemplo**:

- Raiz digital de 942: 9 + 4 + 2 = 15 -> 1 + 5 = 6.

## Pré-requisitos

- JDK 8+ instalado
- Maven instalado

## Estrutura do Projeto

O projeto segue a convenção padrão do Maven:

- `src/main/java/`: Contém a implementação da função `calculateDigitalRoot`.
- `src/test/java/`: Contém os testes unitários para a função `calculateDigitalRoot`.

## Como Executar os Testes

1. Clone o repositório.
2. Abra um terminal ou prompt de comando.
3. Navegue até a pasta raiz do projeto relacionado ao cálculo da raiz digital.
4. Execute o seguinte comando para rodar os testes:
```bash
mvn clean test
