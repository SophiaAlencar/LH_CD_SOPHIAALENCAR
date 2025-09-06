# LH_CD_SOPHIAALENCAR
Este projeto prevê a nota do IMDB de filmes.
---
1. Clique no notebook (.ipynb) de sua escolha

2. Clique em open Colab e faça um clone do mesmo
3. Com sua cópia, execute as células e gere o modelo
4. Faça a predição dessa forma em uma nova célula:

filme = {
    'Released_Year':
    'Runtime': 
    'Meta_score': 
    'No_of_Votes': 
    'Gross': 
    'Certificate': ''
    'Genre': ''
    'Overview': ''
}

nota_prevista = predict_imdb_simple(filme)
print(f"Nota: {nota_prevista}/10")
