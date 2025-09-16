# Desafio_Indicium_IMDB

Desafio Indicium sobre dados de avaliação de filmes pelo IMDB

Passos para carregar o Jupyter Notebook a partir do repositório
> Clicar na guia lateral e abrir o arquivo "Desafio_indicium_imdb.ipynb"

Passos para carregar o arquivo localmente
> Faça o download do arquivo, salvando numa pasta a sua escolha
> Abrir o arquivo a partir de um Jupyter IDE

Para carregar o modelo, após ter sido aberto o arquivo "Desafio_indicium_imdb.ipynb":
> Faça o download do "imdb_rating_model.pkl"
> Dentro do notebook, digitar o comando:
with open("imdb_rating_model.pkl", "wb") as f:
    pickle.dump(model, f)
