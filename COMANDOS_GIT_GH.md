# Comandos Git e GitHub CLI

Este arquivo deixa pronto o fluxo para publicar o projeto `LEI-DE-MORGAN-UFPA-IA` no GitHub usando `git` e `gh`.

## Antes de executar

Voce precisa ter:

- `git` instalado
- `gh` (GitHub CLI) instalado
- login feito no GitHub CLI com `gh auth login`

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
gh auth login
```

Abre o processo de autenticacao da sua conta GitHub no terminal.

```bash
gh repo create LEI-DE-MORGAN-UFPA-IA --public --source . --remote origin --push
```

Cria o repositorio no GitHub com o nome pedido, conecta o remoto `origin` e envia os arquivos.

## Se voce quiser repositorio privado

Troque `--public` por `--private`:

```bash
gh repo create LEI-DE-MORGAN-UFPA-IA --private --source . --remote origin --push
```

## Se preferir criar o repositorio manualmente no site

Depois de criar o repositorio vazio no GitHub, use:

```bash
git init
git add .
git commit -m "Adiciona apresentacao da Lei de Morgan para Google Colab"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/LEI-DE-MORGAN-UFPA-IA.git
git push -u origin main
```

## Link esperado no Google Colab

Depois do push, o notebook podera ser aberto por:

```text
https://colab.research.google.com/github/SEU_USUARIO/LEI-DE-MORGAN-UFPA-IA/blob/main/LEI_DE_MORGAN_UFPA_IA_Colab.ipynb
```

## Observacao importante

Nesta sessao do Codex, o conector do GitHub nao estava autenticado e `git`/`gh` nao apareceram instalados no ambiente atual. Por isso, os comandos foram deixados prontos aqui para voce executar assim que estiver no seu ambiente com GitHub configurado.
