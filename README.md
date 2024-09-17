# **Projeto Análise de Filmes: Netflix, IMDb e Rotten Tomatoes**

## **Visão Geral do Projeto**
Este projeto realiza uma análise de dados utilizando informações de três plataformas populares de filmes: **Netflix**, **IMDb** e **Rotten Tomatoes**. A proposta principal é investigar padrões e relações entre a popularidade de gêneros, as avaliações de filmes e o desempenho de bilheteria. Para isso, utilizamos técnicas de análise de dados, visualização, regressão linear e testes de hipóteses.

## **Objetivos**
- Analisar o comportamento dos filmes nas três plataformas.
- Explorar correlações entre avaliações de críticos e do público.
- Avaliar a popularidade de diferentes gêneros e como isso influencia nas classificações e bilheteira.

## Estrutura do Projeto

1. **Carregamento dos Dados**  
   Os seguintes arquivos CSV foram carregados no ambiente para análise:
   - `netflix_titles.csv` (informações sobre filmes e séries da Netflix).
   - `rottentomatoes_critic_reviews.csv` (avaliações de críticos no Rotten Tomatoes).
   - `rottentomatoes_movies.csv` (informações detalhadas sobre filmes no Rotten Tomatoes).

2. **Exploração Inicial dos Dados**  
   Foram analisadas as colunas dos datasets para entender a estrutura dos dados. As principais colunas são:
   - **Netflix:** `show_id`, `type`, `title`, `director`, `cast`, `country`, `release_year`, `rating`.
   - **Rotten Tomatoes Critic Reviews:** `critic_name`, `review_score`, `review_type`, `review_date`.
   - **Rotten Tomatoes Movies:** `movie_title`, `genres`, `directors`, `tomatometer_rating`, `audience_rating`.

3. **Limpeza e Preparação dos Dados**  
   Alguns tratamentos de dados foram feitos para garantir a consistência das análises, como lidar com valores ausentes e padronizar formatos.

4. **Análises Realizadas**  
   As análises focaram em identificar:
   - A relação entre avaliações de críticos e público.
   - Gêneros de filmes mais populares e bem avaliados.
   - Diferenças entre os tipos de conteúdo (filmes e séries) em termos de avaliação e recepção.

5. **Visualizações**  
   Foram gerados gráficos para auxiliar na visualização dos dados, como:
   - Histogramas de distribuições de notas.
   - Gráficos de dispersão mostrando correlações entre as variáveis.

## Conclusão
A análise realizada trouxe insights importantes sobre a relação entre críticas especializadas e o público, além de identificar tendências na popularidade de gêneros cinematográficos. Essas informações podem ser úteis tanto para entender preferências de audiência quanto para estudos sobre o impacto de críticas no sucesso de bilheteria.

## Ferramentas Utilizadas
- Python
- Bibliotecas: `pandas`, `matplotlib`, `seaborn`, `numpy`

## **Contribuidores**
- **Gabriela Marsiglia - RM551237**
- **João Victor Soares Rodrigues - RM551410**
