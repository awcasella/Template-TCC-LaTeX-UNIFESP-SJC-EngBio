# Template TCC LaTex

Template LaTeX de TCC Engenharia Biomédica da UNIFESP-SJC, pode ser utilizado como base para TCC's de outros cursos e de outras universidades.

# Sobre esse projeto

O objetivo deste repositório é prover um template para TCC que faça uso da linguagem LaTeX, que possa ser adaptado para qualquer relatório, tese, ou dissertação academica e que esteja em português.

# Começando

**Pre-requisitos**

Para gerar .pdf a partir de .tex é necessário instalar o Texlive.

    $ sudo apt-get install texlive-full

**Instalações**

Cloning the Repository

    $ git clone https://github.com/awcasella/Template-TCC-LaTex.git

    $ cd Template-TCC-LaTex
  
Compilando o projeto (necessário compilar 2x ou 3x algumas vezes):

    $ pdflatex TCC

Compilando arquivo .bib com referências bibliográficas:
    
    $ bibtex TCC

Fazendo aparecer a lista de abreviações (Deve ser rodado toda vez que incluir uma nova abreviação, ou depois de incluir todas):
    
    $ makeindex TCC.nlo -s nomencl.ist -o TCC.nls

# Feito com
- [LaTeX](https://www.latex-project.org): A document preparation system.
