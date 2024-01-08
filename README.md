<p align="center">
  <br>
  <img alt="TerraQ logo" width="150" src="https://sigma01.nyc3.digitaloceanspaces.com/terraq/assets/images/logo/logo.png"/>
  <br>
</p>

# Atenção e nescesario ter o python instalado na sua maquina
## Todo o código se encontra na branch Samuel-Lucas-Data-Scientist-test.
```
git clone git@github.com:saniodev/data-scientist-test-jan-2024.git
```
## Depois de clonar o projeto, mude para a branch desejada.

```
git checkout Samuel-Lucas-Data-Scientist-test
```
## verifique se esta na branch Samuel-Lucas-Data-Scientist-test
```
git branch
```
## Instale as dependências do projeto:

```
pip install -r requirements.txt
```
# Descrição e objetivos

Este teste foi criado para avaliar suas habilidades e criatividade no manejo de dados geoespaciais, na aplicação de técnicas de ciência de dados e na produção de visualizações que possam gerar insights valiosos.

# Avaliação
## Todos os requisitos Foram cumpridos
- [v] Faça um script que baixa o dataset de municípios do estado de Minas Gerais (usando este [LINK](https://raw.githubusercontent.com/tbrugz/geodata-br/master/geojson/geojs-31-mun.json), transforme-o em um GeoJSON na projeção EPSG:31983 e salve-o no diretório `dados/` com o nome `municipios-mg.geojson`. Em seguida, neste mesmo script, adicione uma coluna a este vetor contendo a área de cada município em km² e salve o resultado no mesmo arquivo.
- [v] Procure uma fonte confiável na internet de dados de população e PIB dos municípios brasileiros e salve os dados de população e PIB dos municípios de Minas Gerais em um arquivo CSV com o nome `dados/populacao-pib-municipios-mg.csv`.
- [v]  Utilize os dois arquivos de focos de desmatamento como base (`dados/desmatamento_ago22.gpkg` e `dados/desmatamento_set_22.gpkg`), junte-os em um único dataset, transforme-o em um GeoJSON na projeção EPSG:31983 e salve-o em `dados/focos-desmatamento-mg.geojson`.
- [v]  No notebook `02_analise.ipynb`, faça uma análise exploratória dos dados, respondendo às seguintes perguntas:
  - [v]  Qual a área total desmatada em hectares no estado de Minas Gerais em cada um dos meses de agosto e setembro de 2022?
  - [v]  Qual a área total desmatada em km² no estado de Minas Gerais em todo o período fornecido (ago/set de 2022) por bioma?
  - [v]  Qual a área total desmatada em km² no estado de Minas Gerais em cada um dos meses de agosto e setembro de 2022, por município?
- [v] No notebook `02_analise.ipynb` faça uma análise de correlação entre as variáveis de população e PIB dos municípios de Minas Gerais e a área desmatada em hectares. Apresente os resultados da forma que achar mais adequada.
- [v] No notebook `03_visualizacao.ipynb` faça 5 visualizações que possam ser úteis para o gestor público tomar decisões sobre onde alocar recursos para fiscalização, elencando os municípios/biomas que mais necessitam de atenção. As visualizações podem ser feitas com qualquer biblioteca de visualização de dados que você preferir (matplotlib, seaborn, plotly, bokeh, folium, etc) e podem ser estáticas ou interativas. Seja criativo e tente fazer visualizações que sejam claras, esteticamente agradáveis (PS: Pense que o gestor público não é um cientista de dados e que não tem conhecimento de programação ou de ciência de dados e vai apresentar os resultados que você plotar neste notebook para o governador do estado alocar mais recursos no combate ao desmatamento ilegal).
