# LEI-DE-MORGAN-UFPA-IA

Repositorio preparado para uso no Google Colab com uma apresentacao em formato de notebook sobre a Lei de Morgan, focada em algebra booleana, tabelas-verdade, portas logicas e exemplos em Python.

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/UFPAJoaoVictorIA/LEI-DE-MORGAN-UFPA-IA/blob/main/LEI_DE_MORGAN_UFPA_IA_Colab.ipynb)

## Links diretos

- GitHub: `https://github.com/UFPAJoaoVictorIA/LEI-DE-MORGAN-UFPA-IA`
- Google Colab: `https://colab.research.google.com/github/UFPAJoaoVictorIA/LEI-DE-MORGAN-UFPA-IA/blob/main/LEI_DE_MORGAN_UFPA_IA_Colab.ipynb`

## Objetivo

Apresentar a Lei de Morgan em 10 slides/secoes com:

- explicacao teorica em linguagem clara
- formulas em LaTeX
- exemplos de codigo em Python
- instrucoes de execucao para Google Colab

## Arquivos do projeto

- `LEI_DE_MORGAN_UFPA_IA_Colab.ipynb`: notebook principal da apresentacao
- `README.md`: guia rapido para GitHub e Google Colab
- `COMANDOS_GIT_GH.md`: comandos explicados para publicar ou atualizar o projeto com `git`
- `.gitignore`: arquivos ignorados para notebooks Python

## Repositorio no GitHub

O repositorio publicado para este projeto e:

- `UFPAJoaoVictorIA/LEI-DE-MORGAN-UFPA-IA`

## Como enviar ou atualizar os arquivos

### Opcao 1: pelo navegador

1. Abra o repositorio no GitHub.
2. Clique em `Add file` e depois em `Upload files`.
3. Envie estes arquivos:
   - `LEI_DE_MORGAN_UFPA_IA_Colab.ipynb`
   - `README.md`
   - `COMANDOS_GIT_GH.md`
   - `.gitignore`
4. Clique em `Commit changes`.

### Opcao 2: com Git e GitHub CLI

Os comandos completos e comentados estao em `COMANDOS_GIT_GH.md`. O fluxo resumido e:

```bash
git init
git add .
git commit -m "Adiciona apresentacao da Lei de Morgan para Google Colab"
git branch -M main
git remote add origin https://github.com/UFPAJoaoVictorIA/LEI-DE-MORGAN-UFPA-IA.git
git push -u origin main
```

## Como abrir no Google Colab

### Pelo proprio Colab

1. Acesse [Google Colab](https://colab.research.google.com/).
2. Abra a aba `GitHub`.
3. Procure por `LEI-DE-MORGAN-UFPA-IA`.
4. Selecione `LEI_DE_MORGAN_UFPA_IA_Colab.ipynb`.

### Pela URL direta

```text
https://colab.research.google.com/github/UFPAJoaoVictorIA/LEI-DE-MORGAN-UFPA-IA/blob/main/LEI_DE_MORGAN_UFPA_IA_Colab.ipynb
```

## Como apresentar no Colab

1. Abra o notebook.
2. Execute as celulas na ordem.
3. Use o sumario lateral para navegar entre `Slide 1` e `Slide 10`.
4. Leia primeiro cada bloco de instrucao em Markdown e depois rode a celula de codigo correspondente.
5. Para apresentar, deixe o navegador em tela cheia e avance secao por secao.

## Estrutura dos 10 slides

1. titulo, objetivo, contexto e uso no Colab
2. revisao de logica booleana
3. primeira equivalencia da Lei de Morgan
4. segunda equivalencia da Lei de Morgan
5. tabela-verdade da primeira equivalencia
6. tabela-verdade da segunda equivalencia
7. aplicacao em portas logicas
8. simplificacao de expressoes booleanas
9. aplicacao pratica em Python
10. conclusao e exercicio final

## Observacao

O notebook foi montado para funcionar no ambiente padrao do Google Colab, sem depender de bibliotecas externas.
