# exploracao_analise_dados_covid19_brasil
No seguinte projeto eu apliquei uma exploração e análise de dados do covid 19 no Brasil, o código em si é replicavel para todos os outros paises dentro do dataset, pois as funções aplicam os dados levando em conta o pais passado como parametro, que tambem esta descrito no projeto.

O projeto se inicia indicando a fonte dos dados, uma analise superficial das estruturas do conjunto de dados e remoção dos valores 'NA' presentes. Em sequência temos uma análise gráfica do comportamento dos casos dentro do periodo de tempo analisado.
![analise do crescimento do covid no brasil](src/casos_confirmados_brasil.png)

Seguido pela visualização do crescimento dos casos dia a dia.
![casos novos dia a dia de covid no brasil](src/casos_novos_dia.png)

Após isso temos a união dos datasets, seguido da criação de uma funão e faço a análise da letalidade do covid no Brasil, que pode ser replicado para outros paises e em outras datas, o que permite a análise em diferentes regiões e paises que estão dentro do nosso conjunto de dados (em sequencia ja tenho uma comparação visual dentro dos 10 paises que emais confirmaram casos em '10/10/2021').
![casos confirmados por pais](src/confirmado_por_pais.png)

Na sequencia tenho o calculo de taxa de incidência do Covid.
<b>Taxa de incidência:</b> Qual a chance de alguém adquirir a doença nesse periodo analisado para essa população.

Por fim temos o gráfico de letalidade do covid 19 do nosso conjunto de dados.
![taxa de letalidade em porcentagem](src/taxa_de_letalidade.png)
