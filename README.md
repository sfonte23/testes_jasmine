# Jasmine Test Suite - Calculadora e Validação de Maioridade

Este projeto contém um conjunto de testes para validar funções JavaScript utilizando o framework [Jasmine](https://jasmine.github.io/). O projeto implementa duas funcionalidades principais: operações de calculadora (soma, subtração, multiplicação e divisão) e verificação de maioridade.

## Estrutura do Projeto

A estrutura do projeto segue a organização comum para testes com Jasmine:

```
├── lib/                   # Arquivos do framework Jasmine
│   └── jasmine-4.5.0/     
├── src/                   # Arquivos com o código-fonte
│   ├── calculadora.js      # Funções de cálculo (soma, subtração, etc.)
│   └── maioridade.js       # Função de verificação de maioridade
├── spec/                  # Arquivos de teste (specs)
│   ├── calculadora.spec.js # Testes para a calculadora
│   └── maioridade.spec.js  # Testes para a função de maioridade
└── specRunner.html        # Página HTML para execução dos testes
```

### Arquivos de código

- `src/calculadora.js`: Implementa funções para as operações básicas de uma calculadora.
  - **Funções**: `soma`, `subtracaoo`, `multiplicacao`, `divisao`
  
- `src/maioridade.js`: Implementa uma função que verifica se a idade fornecida é de maioridade ou não.
  - **Função**: `maioridade`

### Arquivos de teste

- `spec/calculadora.spec.js`: Testes unitários para validar as operações de cálculo.
- `spec/maioridade.spec.js`: Testes unitários para validar o resultado da verificação de maioridade.

## Executando os testes

Para rodar os testes, basta abrir o arquivo `specRunner.html` em um navegador. Este arquivo irá carregar automaticamente os scripts de código e de teste e exibirá os resultados dos testes diretamente na página.

### Exemplo de execução

1. Clone o repositório.
2. Abra o arquivo `specRunner.html` no seu navegador preferido.
3. Veja os resultados dos testes diretamente na interface gerada pelo Jasmine.

## Ferramentas utilizadas

- [Jasmine 4.5.0](https://jasmine.github.io/): Framework de teste para JavaScript.
- JavaScript (ES6)