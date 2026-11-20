# Quiz Interativo — Programação Orientada a Objetos em Python

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Linguagem-Python-3776AB?style=flat-square" />
  <img alt="POO" src="https://img.shields.io/badge/Paradigma-Orientação%20a%20Objetos-374151?style=flat-square" />
  <img alt="Projeto de estudos" src="https://img.shields.io/badge/Tipo-Projeto%20de%20estudos-16A34A?style=flat-square" />
</p>

Projeto de **quiz de perguntas e respostas**, desenvolvido para praticar **programação orientada a objetos (POO) em Python**. A aplicação apresenta perguntas de múltipla escolha, recebe as respostas e contabiliza os acertos do participante.

## Objetivo

Aplicar classes, objetos, atributos e métodos na construção de um programa interativo, separando a representação das perguntas do gerenciamento do quiz.

## Funcionalidades

- Apresentação de perguntas com alternativas de múltipla escolha.
- Leitura das respostas no terminal.
- Verificação das alternativas escolhidas.
- Controle de pontuação durante a atividade.
- Exibição do resultado final.

## Estrutura orientada a objetos

Na versão desenvolvida durante os estudos, o exercício utiliza duas classes principais:

| Classe | Responsabilidade | Métodos trabalhados |
| --- | --- | --- |
| `Pergunta` | Representar uma questão e sua resposta | `__init__`, `mostrar`, `checar_resposta` |
| `Quiz` | Organizar as perguntas e conduzir a execução | `__init__`, `adicionar_pergunta`, `iniciar` |

O conjunto de questões usado como exemplo aborda conceitos básicos de desenvolvimento web e programação.

## Tecnologias e conceitos

- **Python 3**.
- Programação orientada a objetos.
- Criação de classes e instâncias.
- Construtores, atributos e métodos.
- Listas, condicionais, repetição e entrada de dados.

## Como executar

**Requisito:** Python 3 instalado.

1. Clone o repositório:

   ```bash
   git clone https://github.com/adolfo-araujo/Python-Orientado-ao-Objeto.git
   cd Python-Orientado-ao-Objeto
   ```

2. Encontre o arquivo Python que inicia o quiz e execute-o. Exemplo, **substituindo `arquivo_principal.py` pelo nome real**:

   ```bash
   python arquivo_principal.py
   ```

   Em sistemas nos quais o executável do Python 3 se chama `python3`, use:

   ```bash
   python3 arquivo_principal.py
   ```

## Fluxo de execução

```text
Criar perguntas
      ↓
Adicionar ao quiz
      ↓
Exibir uma pergunta e suas alternativas
      ↓
Receber e conferir a resposta
      ↓
Atualizar pontuação
      ↓
Próxima pergunta (até encerrar)
      ↓
Mostrar resultado final
```

## Aprendizados

Este exercício demonstra como a orientação a objetos ajuda a distribuir responsabilidades, reutilizar comportamentos e tornar o código mais legível e organizado.

## Autor

Desenvolvido por [João Adolfo](https://github.com/adolfo-araujo), estudante de Engenharia de Software.
