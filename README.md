# Desafio Controle-Fluxo

## Descrição do Projeto
Este projeto é uma aplicação Java que demonstra o uso de controle de fluxo e tratamento de exceções personalizadas. Ele solicita dois números inteiros do usuário e imprime uma série de mensagens incrementais com base na diferença entre esses números. Se o primeiro número for maior que o segundo, uma exceção personalizada é lançada.

## Estrutura do Projeto

1. **Classe `ParametrosInvalidosException`**:
   - **Descrição**: Exceção personalizada que estende `Exception`.
   - **Função**: Representa uma exceção de negócio que é lançada quando o primeiro parâmetro é maior que o segundo.
   - **Mensagem de Erro**: "O segundo parâmetro deve ser maior que o primeiro".

2. **Classe `Contador`**:
   - **Função `main`**:
     - Lê dois números inteiros do usuário via terminal.
     - Chama o método `contar` e captura possíveis exceções `ParametrosInvalidosException`.
     - Exibe a mensagem de erro caso a exceção seja lançada.
   - **Função `contar`**:
     - Valida se o primeiro parâmetro é maior que o segundo e lança a exceção `ParametrosInvalidosException` se necessário.
     - Calcula a diferença entre os dois números.
     - Usa um laço `for` para imprimir mensagens incrementais com base na diferença calculada.

## Aprendizado
- **Controle de Fluxo**: Utilização de laços de repetição (`for`) para executar ações repetitivas.
- **Tratamento de Exceções**: Criação e lançamento de exceções personalizadas para gerenciar condições de erro específicas.
- **Interação com o Usuário**: Uso da classe `Scanner` para ler entradas do terminal.
- **Estruturação de Projetos**: Organização do código em diferentes classes para melhorar a modularidade e a manutenção.

## Pré-requisitos
- Java Development Kit (JDK) 8 ou superior
- IDE ou editor de texto de sua escolha (recomendo IntelliJ IDEA, Eclipse ou VSCode)

## Instalação
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/DesafioControleFluxo.git
