# Polars (versão 0.16.2)

Repositório com um tutorial simples e claro de Polars, biblioteca de análise de dados no Python, uma alternativa ao Pandas.

O notebook se encontra em: [01-polars_notebook.ipynb](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb). 

## Pontos abordados:

- [X] [**0. Setup e considerações iniciais**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header0)
- [X] [**1. Carregando os dados**: CSV e Excel](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header1)
- [X] [**2. Informações iniciais do dataframe:** head, info, shape e etc](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header2)
- [X] [**3. Selecionando colunas específicas**: por nome e por index](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header3)
- [X] [**4. Operações entre colunas**: soma, multiplicação e etc](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header4)
- [X] [**5. Renomeando colunas**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header5)
- [X] [**6. Filtrando as linhas:** igual, diferente, maior que, menor que, está dentro de uma lista](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header6)
- [X] [**7. Funções de agregação**: value_counts, média, mínimo, máximo e etc](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header7)
- [X] [**8. Funções de agregação + group by**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header8)
- [X] [**9. Ordenando as linhas**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header9)
- [X] [**10. Trabalhar com duplicatas**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header10)
- [X] [**11. Lidando com valores nulos:** fillna(), dropna(), filtros e etc](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header11)
- [X] [**12. Joins**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header12)
- [X] [**13. Pivot table e Melt**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header13)
- [X] [**14. Operações com datas**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header14)
- [X] [**15. Exportando os dados**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header15)
- [X] [**16. Criando e aplicando funções personalizadas**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header16)
- [X] [**17. Trabalhando com JSON**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header17)
- [X] [**18. Window functions:** row number e rank](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header18)
- [X] [**19. Um pouco de teoria:** breve descrição e referências](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header19)
- [X] [**20. Bônus e referências**](https://nbviewer.org/github/barbosarafael/polars_python_test/blob/main/01-notebook/01-polars_notebook.ipynb#header20)
- [X] Adicionar um passo a passo de instalação do Polars + VirtualEnv no README

## Instalação (Ubuntu/Debian/Mint):

Criando uma virtual environment (venv) antes de tudo:

```bash
python3 -m venv venv
```

Ative a venv:

```bash
. venv/bin/activate
```

Instale todas as libs necessárias que estão no `requirements.txt`:

```bash
pip3 install -r requirements.txt
```

Enjoy! 

<p align="center">
  <img src="https://media.giphy.com/media/5p8QuXUTk1rIk/giphy.gif" alt="animated" />
</p>
