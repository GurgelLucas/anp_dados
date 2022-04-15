# Projeto com datasets abertos da ANP

## O que é ANP?
Agência Nacional do Petróleo, Gás Natural e Biocombustíveis

Os datasets explorados consistem em:
O Levantamento de Preços de Combustíveis (LPC), que abrange gasolina C, etanol hidratado, óleo diesel B, GNV e GLP P13 pesquisados em 459 localidades, segundo procedimentos estabelecidos pela Portaria ANP nº 202/2000.

O LPC é a mais abrangente pesquisa de preços de combustíveis automotivos e de GLP do País, que oferece referências para o mercado, órgãos de governo e a sociedade civil em geral. Políticas públicas como o auxílio ‘Gás dos Brasileiros’, recentemente criado pela Lei nº 14.237/2021, utilizam-se dos dados de preços gerados pelo LPC.

Fonte: https://www.gov.br/anp/pt-br/assuntos/precos-e-defesa-da-concorrencia/precos/precos-revenda-e-de-distribuicao-combustiveis/levantamento-de-precos-de-combustiveis

## Objetivo deste Projeto

* Realizar um pipeline de ETL e organizar os dados em camadas do Datalake.
* Explorar diferenças de preço nos combustíveis por métricas de:
    * Tempo
    * Localidade (Estado e Municipio)
    * Empresa Fornecedora 
    * Posto de Revenda

## Etapas do Projeto

1. Coletar dados do Portal gov.br aonde estão os conjuntos de dados de Série Histórica de Preços de Combustíveis
2. 