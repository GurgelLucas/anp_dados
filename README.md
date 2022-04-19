# Projeto com datasets abertos da ANP

## O que é ANP?
Agência Nacional do Petróleo, Gás Natural e Biocombustíveis

Os datasets explorados consistem em:
O Levantamento de Preços de Combustíveis (LPC), que abrange gasolina C, etanol hidratado, óleo diesel B, GNV e GLP P13 pesquisados em 459 localidades, segundo procedimentos estabelecidos pela Portaria ANP nº 202/2000.

O LPC é a mais abrangente pesquisa de preços de combustíveis automotivos e de GLP do País, que oferece referências para o mercado, órgãos de governo e a sociedade civil em geral. Políticas públicas como o auxílio ‘Gás dos Brasileiros’, recentemente criado pela Lei nº 14.237/2021, utilizam-se dos dados de preços gerados pelo LPC.

Fonte: https://www.gov.br/anp/pt-br/assuntos/precos-e-defesa-da-concorrencia/precos/precos-revenda-e-de-distribuicao-combustiveis/levantamento-de-precos-de-combustiveis

## Tecnologias usadas

<img src="https://community.cloud.databricks.com/media/databricks_community_edition.2359b37e.png" height=50 width=160 hspace="20"/><img src="https://databricks.com/wp-content/uploads/2018/12/PySpark-1024x164.png" height=50 width=260 />

# Etapas do Projeto

## Extração

1. Coletar dados do portal gov.br aonde estão os conjuntos de dados de [Série Histórica de Preços de Combustíveis](https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/serie-historica-de-precos-de-combustiveis)

2. Realizar o Download da tabela de códigos de municípios dados do portal IBGE > [Códigos dos municípios IBGE](https://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/divisao_territorial/2021/DTB_2021.zip), onde tem cada código de UF e munícipio.

3. Para os registros mais atualizados iremos coletar por WebScraping diretamente do [SLP - Sistema de Levantamento de Preço](https://preco.anp.gov.br/include/Resumo_Semanal_Index.asp)

4. 

## Transformação
Em andamento

## Load
Em andamento

# Objetivo deste Projeto

* Realizar um pipeline de ETL e organizar os dados em camadas do Datalake.
* Explorar diferenças de preço nos combustíveis por métricas de:
    * Tempo
    * Localidade (Estado e Município)
    * Empresa Fornecedora 
    * Posto de Revenda

* Identificar o preço médio de cada combustível no período atual por:
    * Região
    * Estado
    * Cidade
    * Município

* Onde estão os preços mais baixos e mais altos
