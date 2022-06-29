# Analíse de dados e Geoprocessamento - Safra_RN

## Observações:
1. Os municípios sem informação para pelo menos um produto da lavoura temporária não aparecem nas listas;
2. A partir do ano de 2001 as quantidades produzidas dos produtos melancia e melão passam a ser expressas em toneladas. Nos anos anteriores eram expressas em mil frutos. O rendimento médio passa a ser expresso em Kg/ha. Nos anos anteriores era expresso em frutos/ha.
3. Veja o documento AlteracoesUnidadesMedidaFrutas.pdf com as alterações de unidades de medida das frutíferas ocorridas em 2001 e a tabela de conversão fruto x quilograma.
4. Os produtos girassol e triticale só apresentam informação a partir de 2005.
5. A quantidade produzida de abacaxi é expressa em mil frutos e o rendimento médio em frutos/ha.
6. Valores para a categoria Total indisponíveis para as variáveis Quantidade produzida e Rendimento médio, pois as unidades de medida diferem para determinados produtos.
7. Subentende a possibilidade de cultivos sucessivos ou simultâneos (simples, associados e/ou intercalados) no mesmo ano e no mesmo local, podendo, por isto, a área informada da cultura exceder a área geográfica do município.
8. As culturas de abacaxi, cana-de-açúcar, mamona e mandioca são consideradas culturas temporárias de longa duração. Elas costumam ter ciclo vegetativo que ultrapassa 12 meses e, por isso, as informações são computadas nas colheitas realizadas dentro de cada ano civil (12 meses). Nestas culturas a área plantada refere-se a área destinada à colheita no ano.
9. A diferença entre a área plantada e a área colhida na lavoura temporária é considerada como área perdida.
10. A variável Área plantada só passou a ser informada a partir de 1988.
11. Valor da produção: Variável derivada calculada pela média ponderada das informações de quantidade e preço médio corrente pago ao produtor, de acordo com os períodos de colheita e comercialização de cada produto. As despesas de frete, taxas e impostos não são incluídas no preço.
12. Os dados do último ano divulgado são RESULTADOS PRELIMINARES e podem sofrer alterações até a próxima divulgação.

## Legenda (Símbolo	Significado):
![image](https://user-images.githubusercontent.com/79233238/176464031-99817040-d66e-4b20-b3fb-3428b192c890.png)



## Inspiração:
* Patrícia de Siqueira Ramos - Professora da UNIFAL Varginha
    * Github da autora: https://github.com/patriciasiqueira
    * link do Site (Aulas e Explicações): https://www.patriciaramos.org/espacial 
    * link do canal do Youtube: https://www.youtube.com/channel/UCd8_GwocCAx0aIi9gwWA0rQ
    * link do Código: https://colab.research.google.com/drive/15gwWPF2MQNp3u1puFWp6ZPbz1mg9hVRU

## Fonte dos dados:
* SIDRA (Sistema IBGE de Recuperação Automática) - PAM (Produção Agrícola Municipal) 2020 - Tabela 1612 / Culturas Temporarias
    * link: https://sidra.ibge.gov.br/tabela/1612

## SHAPEFILE 
* É um formato de armazenamento de dados de vetor da Esri para armazenar a posição, a forma e os atributos de feições geográficas. É armazenado como um conjunto de arquivos relacionados e contém uma classe de feição.
    * link: https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html?=&t=downloads
    
