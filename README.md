# Consultas-por-similaridade

A Pesquisa Game Brasil 2022 apontou que 74,5% dos brasileiros jogam
videogame, o que equivale a 3 em cada 4 pessoas do país. As entrevistas
realizadas em 26 estados e no Distrito Federal evidenciam um crescimento de
2,5 pontos percentuais em relação a 2021.
Ainda segundo a Forbes o mercado de games ultrapassará a marca de
U$$ 200 bilhões até 2023, contando com jogos para consoles, PC e com um
destaque para os jogos mobile.
Considerando esta relevância dos jogos eletrônicos no cotidiano, foi
idealizado o presente projeto para explorar as vendas de jogos eletrônicos
através dos anos. A ideia é manter informações sobre 100 jogos em um Data
Warehouse (DW) visando consultas referentes a venda dos jogos em relação a
gênero, plataforma, ano, localidade, entre outros aspectos. Os dados originais
foram obtidos via Kaggle e se referem a jogos lançados entre 1985 e 2020.
Além disso, ampliando o modelo do DW original apresentado no módulo
II, foi adicionada uma dimensão que conta com vetores de características para
que seja possível fazer consultas por similaridade. Com isso o usuário poderá
saber quais jogos possuem maior semelhança com um título de sua preferência,
podendo inclusive utilizar este fator como critério para escolher o que jogar em
seu tempo livre. Os dados de característica foram obtidos em um dataset do
corgis.
