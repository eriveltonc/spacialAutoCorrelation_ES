# Estudo de Auto Correlação Espacial de Municípios do Espírito Santo

Este projeto tem como objetivo estudar a auto correlação espacial de municípios do Espírito Santo. Para isso, utilizamos dados de população e PIB de cada município e aplicamos diversas técnicas estatísticas para identificar padrões de associação espacial.

## Arquivos

- spacial_auto_correlation_ES.ipynb: notebook contendo o código utilizado no projeto
- basemunicipal.geojson: arquivo contendo dados geográficos dos municípios do Espírito Santo

## Dependências

- pandas
- geopandas
- numpy
- pysal
- splot
- esda
- matplotlib
- folium

## Como usar

Para utilizar este projeto, basta clonar ou baixar o repositório e rodar o notebook spacial_auto_correlation_ES.ipynb. É necessário ter as dependências instaladas para que o projeto funcione corretamente.

## Metodologia

Para analisar a auto correlação espacial dos municípios do Espírito Santo, utilizamos as seguintes técnicas estatísticas:

- Criação de choropleth maps das variáveis de interesse (população e PIB) para visualização da distribuição espacial dos dados.
- Construção de objeto de pesos espaciais para capturar a estrutura de contiguidade entre os municípios.
- Cálculo do Lag Espacial para identificar se há associação espacial das variáveis de interesse.
- Cálculo da estatística de Moran I para medir o grau de auto correlação espacial das variáveis.
- Análise de Moran Local para identificar clusters de municípios com características semelhantes e padrões de associação espacial.
## Fonte dos Dados:
IJSN - Instituto Jhones do Santos Neves

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](http://license.md/) para detalhes.
