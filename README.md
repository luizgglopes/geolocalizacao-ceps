# geolocalizacao-ceps
Construção de base de dados de CEP, logradouros e locais com georreferenciamento, por pontos e polígonos, a partir de fontes abertas.

O intuito deste projeto, apresentado na BB DataCon Week (https://bbdataconweek.com.br/geolocalizacao-e-dados-abertos-uma-jornada-inesperada), foi encorajar a exploração e demonstrar que é possível se desenvolver uma base de dados robusta a partir de dados disponíveis na web.
Até mesmo pela forma de apresentação, priorizou-se mais a didática do que a utilização de técnicas possivelmente mais atuais e performáticas. De qualquer forma, o objetivo foi cumprido, alcançando-se uma base de 425 mil CEPs distintos, com seus dados e polígonos correspondentes, além de 211 mil pontos de interesse.

Fontes utilizadas:
- OpenStreetMap: www.openstreetmap.org (© contribuidores do OpenStreetMap) e https://download.geofabrik.de/south-america/brazil.html - dados estão disponíveis sob a Open Database License (ODbL)
- IBGE: https://www.ibge.gov.br/geociencias/downloads-geociencias.html > organizacao_do_territorio > analises_do_territorio > divisao_regional > divisao_regional_do_brasil > divisao_regional_do_brasil_em_regioes_geograficas_2017 > shp > RG2017_regioesgeograficas2017_20180911.zip e https://www.ibge.gov.br/geociencias/downloads-geociencias.html > estrutura_territorial > localidades > Shapefile_SHP
- CENSO 2010: ftp://ftp.ibge.gov.br/Censos/Censo_Demografico_2010/Cadastro_Nacional_de_Enderecos_Fins_Estatisticos
