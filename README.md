# Análise Geoespacial - Filiação Partidária Por Município no Rio de Janeiro

Este notebook é parte de um **Projeto de Uso de Dados Públicos Eleitorais e Partidários** que participei como Assistente de Pesquisa. Como o mesmo ainda não foi divulgado, pedi permissão para o Professor responsável para utilizar este pequeno pedaço como Portfólio.

#### Sobre os dadoos:

O arquivo *dados_filia_rj.csv* foi construido exclusivamento com arquivos baixados do portal do [TSE - Tribunal Superior Eleitoral](http://www.tse.jus.br/partidos/filiacao-partidaria/relacao-de-filiados). Como não é possível baixar os dados de filiação de todos os partidos ao mesmo tempo foi utilizado um script para aquisição dos dados, este script foi baseado no arquivo *filiacao_download.py* do [Github do Álvaro Justen](https://github.com/turicas/eleicoes-brasil).

# Limpeza e Organização dos Dados

- Remoção de Colunas
- Criação de colunas
- Transformação do Tipo dos dados
- Remoção de Dados de baixa qualidade
 
# Visualização com Geopandas - Quantidade de Filiados por Municipio
Foram criadas visualizações para entender as filiações partidárias em cada municipio ao longo do tempo.

![texto](https://github.com/dtonetti/geospatial_pt/blob/master/filiados_mun.png)


# Análise de Correlação Espacial
Foram calculados índices de Correlação Espacial para compreender melhor o funcionamento das filiações partidárias no Estado do Rio de Janeiro.

![texto](https://github.com/dtonetti/geospatial_pt/blob/master/lisa.png)

# Code and Resources Used

- Python Version: 3.7
- Packages: pandas, numpy, geopandas, libpysal
