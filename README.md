Trabalho sobre o uso do método de Runge-Kutta de ordem 4 para a análise numérica do modelo SIR (Suscetível - Infectado - Removido) para epidemias, feito com a ferramenta [Quarto](https://quarto.org/).

Criado para a disciplina de Introdução à Física Computacional, lecionada por André Asevedo Nepomuceno no semestre 2025.2 na Universidade Federal Fluminense de Rio das Ostras.

A formatação dos commits é inspirada na proposta em [Padrões de commits, de Iuri Silva](https://github.com/iuricode/padroes-de-commits).

# Instruções para utlizar e modificar este projeto

**Instale no seu computador:**
- [Python](https://www.python.org/)
- [Quarto](https://quarto.org/)

**Crie um ambiente virtual de Python.**
- `python3 -m venv .venv`

**Entre no ambiente virtual.**
- **Linux:** `source .venv/bin/activate`
- **Windows:** `.venv\Scripts\Activate.ps1`

**Instale as dependências necessárias.**
- `pip install jupyter numpy matplotlib`
- `quarto install tinytex`

**Para renderizar o projeto em PDF e em Jupyter Notebook, entre na pasta do projeto e use:**
- `quarto render`
