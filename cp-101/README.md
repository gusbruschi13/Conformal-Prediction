# Conformal Prediction 101 - Reduzindo incertezas dos modelos de ML com Conformal Prediction

Repositório dedicado a ensinar o básico sobre Conformal Prediction.

## Lista de Notebooks nesse Repositório:

- `01-cp-for-multiclass.ipynb`
    Notebook com exemplos de CP para classificação multiclasse.

- `02-cp-for-regression.ipynb`
    Notebook com exemplos de CP para regressão.

- `03-cp-for-binary-class.ipynb`
    Notebook com exemplos de CP para classificação binária.

## Instalando o ambiente para o notebook (para garantir resultados reproduzíveis)

Uma vez dentro da pasta do notebook desejado, você pode instalar as bibliotecas que estou usando com `poetry` da seguinte maneira.
```console
poetry install
```

Depois, basta lançar o `jupyter notebook`:
```console
poetry run jupyter notebook
```

Ou você pode criar um virtual env, e instalar o arquivo `requirements.txt`. Basta seguir os seguintes passos:
- No Windows:
    Use Git-Bash como shell para terminal no Windows.
    Crie um ambiente virtual python (`python -m venv venv`)
    Ative o ambiente virtual (`source venv/Scripts/activate`)
    Tente executar qualquer comando (por exemplo, `ls`)
    Instale o `requirements.txt` (`python.exe -m pip install -r requirements.txt --use-deprecated=legacy-resolver`)

- No Linux:
    Use o terminal do Linux.
    Crie um ambiente virtual python (`python -m venv venv`)
    Ative o ambiente virtual (`source bin/activate`)
    Tente executar qualquer comando (por exemplo, `ls`)
    Instale o `requirements.txt` (`python3 -m pip -r install requirements.txt --use-deprecated=legacy-resolver`)


## 💪🏾 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`