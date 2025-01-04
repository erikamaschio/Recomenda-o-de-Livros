# Sistema de Recomendação de Livros 📚

Este é um sistema de recomendação de livros baseado em descrições dos livros. Ele utiliza técnicas de Processamento de Linguagem Natural (PLN) para recomendar livros semelhantes com base nas descrições fornecidas. O sistema foi desenvolvido em Python, utilizando bibliotecas como **pandas**, **sklearn** e **Flask**.

## Tecnologias Utilizadas

- **Python** (versão 3.x)
- **Flask**: Framework web para construir a aplicação.
- **Scikit-learn**: Para implementação do modelo de recomendação com TF-IDF e similaridade de cosseno.
- **Pandas**: Manipulação de dados.
- **Numpy**: Para operações numéricas.
- **NLTK**: Para processamento de linguagem natural.

## Dataset Utilizado

O sistema utiliza o dataset [**Books Dataset**](https://www.kaggle.com/datasets/victorstein/livros-skoob), que contém informações sobre livros, como título, autor, ano de publicação, número de páginas, idioma, avaliação e descrição. Este dataset foi utilizado para criar o modelo de recomendação baseado nas descrições dos livros.

## Funcionalidades

- **Recomendação de livros**: O sistema sugere livros com base na descrição fornecida por um usuário.
- **Interface simples**: O usuário insere o nome de um livro e o sistema retorna livros semelhantes.
- **Pré-processamento de texto**: O sistema realiza a limpeza e transformação das descrições dos livros para otimizar as recomendações.

## Documentação
A documentação completa do projeto está disponível em [https://drive.google.com/file/d/1ciAShS0I6meRn5c_z2vTQ-CRCAuP7K-4/view?usp=drive_link], onde você pode encontrar detalhes sobre a arquitetura, fluxo de dados e explicações sobre as técnicas utilizadas para implementar o sistema de recomendação.

