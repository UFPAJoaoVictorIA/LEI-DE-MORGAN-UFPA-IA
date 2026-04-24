# Comandos Git e GitHub CLI

Este arquivo deixa pronto o fluxo para atualizar o projeto `LEI-DE-MORGAN-UFPA-IA` no GitHub usando `git`.

## Repositorio publicado

- `https://github.com/UFPAJoaoVictorIA/LEI-DE-MORGAN-UFPA-IA`

## Antes de executar

Voce precisa ter:

- `git` instalado
- permissao para enviar alteracoes ao repositorio no GitHub

## Fluxo recomendado

Execute os comandos dentro da pasta do projeto.

```bash
git init
```

Inicializa o repositorio Git local.

```bash
git add .
```

Adiciona todos os arquivos do projeto para o primeiro commit.

```bash
git commit -m "Adiciona apresentacao da Lei de Morgan para Google Colab"
```

Cria o commit inicial com o material da apresentacao.

```bash
git branch -M main
```

Define `main` como branch principal.

```bash
git remote add origin https://github.com/UFPAJoaoVictorIA/LEI-DE-MORGAN-UFPA-IA.git
```

Conecta a pasta local ao repositorio ja publicado no GitHub.

```bash
git push -u origin main
```

Envia os arquivos para a branch `main`.

## Se preferir criar outro repositorio manualmente no site

Depois de criar outro repositorio no GitHub, use:

```bash
git init
git add .
git commit -m "Adiciona apresentacao da Lei de Morgan para Google Colab"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/LEI-DE-MORGAN-UFPA-IA.git
git push -u origin main
```

## Link direto no Google Colab

Depois do push, o notebook podera ser aberto por:

```text
https://colab.research.google.com/github/UFPAJoaoVictorIA/LEI-DE-MORGAN-UFPA-IA/blob/main/LEI_DE_MORGAN_UFPA_IA_Colab.ipynb
```

## Observacao importante

O notebook tambem pode ser atualizado diretamente pelo navegador no GitHub, sem depender do `git`, usando a opcao `Add file` > `Upload files`.
