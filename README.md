# Modelo de Mestrado PROCC/UFS

Template LaTeX baseado em abnTeX2 para dissertacao de mestrado do Programa de
Pos-Graduacao em Ciencia da Computacao da Universidade Federal de Sergipe.

## Overleaf

Use `Modelo-Mestrado-PROCC.tex` como arquivo principal.

Configuracao recomendada:

- Compiler: `pdfLaTeX`
- Bibliography tool: `BibTeX`

## Estrutura

- `Modelo-Mestrado-PROCC.tex`: arquivo principal, dados do trabalho e ordem dos elementos.
- `dcomp-abntex2.cls`: classe customizada do modelo.
- `Mestrado.sty`: capa, folha de rosto, ficha catalografica e folha de aprovacao.
- `Pre_Textual/`: resumo, abstract, agradecimentos e listas.
- `Conteudo/`: capitulos da dissertacao.
- `Pos_Textual/`: apendices e anexos.
- `Bibliografia.bib`: referencias bibliograficas.
- `Imagens/`: logos usados no modelo.

## Compilacao local

```sh
pdflatex Modelo-Mestrado-PROCC.tex
bibtex Modelo-Mestrado-PROCC
pdflatex Modelo-Mestrado-PROCC.tex
pdflatex Modelo-Mestrado-PROCC.tex
```
