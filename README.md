# Proposta de Dissertacao

Proposta de dissertacao em LaTeX baseada no modelo de mestrado do Programa de
Pos-Graduacao em Ciencia da Computacao da Universidade Federal de Sergipe.

## Overleaf

Use `Proposta.tex` como arquivo principal.

Configuracao recomendada:

- Compiler: `pdfLaTeX`
- Bibliography tool: `BibTeX`

## Estrutura

- `Proposta.tex`: arquivo principal, dados do trabalho e ordem dos elementos.
- `Proposta_Jose_Bruno.pdf`: versao final em PDF da proposta.
- `dcomp-abntex2.cls`: classe customizada do modelo.
- `Mestrado.sty`: capa, folha de rosto, ficha catalografica e folha de aprovacao.
- `Pre_Textual/`: resumo, abstract, agradecimentos e listas.
- `Conteudo/`: capitulos da dissertacao.
- `Pos_Textual/`: apendices e anexos.
- `Bibliografia.bib`: referencias bibliograficas.
- `Imagens/`: logos usados no modelo.

## Compilacao local

```sh
pdflatex Proposta.tex
bibtex Proposta
pdflatex Proposta.tex
pdflatex Proposta.tex
```
