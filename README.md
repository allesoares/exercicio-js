# Validação de cadastro com JavaScript

Neste exercício do módulo 27, implementei funções para validar o cadastro de um usuário. Trabalhei com comparações, operadores lógicos e objetos; depois usei essas mesmas regras nos [testes de unidade com Jest do módulo 28](https://github.com/allesoares/modulo-28-jest).

## Regras do exercício

O cadastro é válido quando as três condições são atendidas:

- O usuário tem 18 anos ou mais.
- O e-mail contém `@`.
- A propriedade `ativo` é exatamente o booleano `true`.

A verificação de e-mail é propositalmente simples e se limita à regra do exercício.

## Código

O arquivo [usuario.js](usuario.js) contém `verificarMaiorIdade`, `validarEmail`, `usuarioAtivo` e `validarCadastro`. A última função combina as três condições com `&&`.

## Como executar

Com Node.js instalado, execute na pasta do projeto:

```powershell
node usuario.js
```

Os exemplos fornecidos mostram um cadastro válido e outro inválido:

```text
Usuário 1 válido? true
Usuário 2 válido? false
```

Este repositório contém o exercício de implementação. A suíte automatizada está no projeto do módulo 28.

## Contexto

Exercício desenvolvido por Alexandre Soares durante o curso da EBAC, com a aplicação e os exemplos fornecidos nas aulas.

[Voltar ao portfólio](https://github.com/allesoares/qa-portfolio)
