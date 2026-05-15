# Sistema de Recomendação de Filmes

Projeto desenvolvido em Python com o objetivo de recomendar filmes semelhantes com base nos gêneros escolhidos pelo usuário.

O sistema utiliza conceitos simples de Inteligência Artificial e Machine Learning, aplicando Similaridade do Cosseno para comparar os filmes da base de dados.

---

# Objetivo

O objetivo do projeto é ajudar usuários a encontrar filmes parecidos com seus gostos pessoais, utilizando análise de similaridade entre gêneros.

---

# Tecnologias Utilizadas

- Python
- NumPy
- Pandas
- Scikit-Learn
- Ipywidgets
- Google Colab

---

# Como Funciona

Cada filme possui características representadas por gêneros:

- Ação
- Romance
- Ficção
- Comédia
- Terror
- Infantil

Esses gêneros são transformados em vetores numéricos, permitindo calcular a similaridade entre os filmes.

O sistema utiliza:

```python
cosine_similarity()
