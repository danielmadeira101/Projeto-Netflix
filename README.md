# Projeto-Netflix
Análise dos dados da Netflix disponibilizados no site kaggle.com. Trabalho realizado pelos estudantes Ana Rodrigues, Ana Ferreira, Beatriz Andrade e Daniel Madeira no âmbito da disciplina de Programação e Algoritmos II, do curso de Comunicação e Design Multimédia.

# Contexto
O objetivo deste trabalho passa pela análise de um pacote de dados da plataforma online Netflix. Este conjunto de dados consiste nos programas de TV e filmes disponíves na plataforma, juntamente com informações sobre os mesmos, como a data de lançamento, o país, etc. O CSV onde constam estes dados foi recolhido pelo Fixable, um mecanismo de pesquisa de terceiros da Netflix, e está disponibilizado no site kaggle.com.

# Bibliografia
Para a realização deste trabalho recorremos aos notebooks trabalhados em aula com o professor, e disponibilizados no Inforestudante, bem como à documentação do matplotlib (https://matplotlib.org/) e do pandas (https://pandas.pydata.org/docs/), e claro, ao pacote de dados da Netflix (https://www.kaggle.com/shivamb/netflix-shows).

# Estrutura
1. Análise dos dados do CSV.
2. Número de filas no dataframe.
3. Colunas presentes no dataframe.
4. Análise dos diferentes tipos de objetos.
5. Análise dos dados em falta em cada coluna.
6. Análise das colunas "type" e "release_year".
7. Análise dos dados referentes ao ano 2020.
8. Percentagem de filmes e TV shows disponíveis.
9. Países com mais produções.
10. Duração média dos filmes.

# Dicionário dos dados
Uma explicação do conteúdo em `netflix_data.csv`.

| Nome da coluna        | Significado             
| ------------- |:-------------: 
| `show_id` | ID do programa |
| `type` | Tipo de conteúdo: filme ou TV show 
| `title` | Título
| `director` | Realizador/a       
| `cast` | Elenco     
| `country` | País   
| `date_added` | Data em que ficou disponível na Netflix     
| `release_year` | Ano de lançamento    
| `rating` | Classificação  
| `duration` | Duração
| `listed_in` | Categorias em que está listado
| `description` | Descrição/sinopse
