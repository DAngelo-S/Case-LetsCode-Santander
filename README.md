# Quantas pastas dentais são vendidas no Brasil por mês?

Este é o case proposto pela Let's Code para concorrer à bolsa de estudos Santander - Data Science.

As fontes dos dados foram salvos através do WebArchive, assim não as perderemos com o passar do tempo!

Os calculos realizados podem ser consultados através do arquivo analises.ipynb

## Estimativa

Para solucionar esta questão, vamos começar comparando a quantidade recomendada de pasta para se utilizar por dia com a quantidade de pasta que vem por produto.

Para obter os dados sobre o creme dental que os brasileiros utilizam, montei uma tabela com os dados dos cremes dentais mais comprados através de uma das maiores lojas online operando no Brasil, a Amazon[1].

<p align=center>
<img src=Images/TOP-Toothpaste-Amazon.png width=90%>
</p>

A partir destes dados, podemos supor que uma pasta de dente tem, em média, 101,20 gramas e custa 9,03 reais.

A quantidade ideal de pasta de dente por escovação é aproximadamente 0,3 gramas[2][3] e se deve escovar os dentes de 2 a 3 vezes por dia[4].

Outra informação relevante é que, segundo o IBGE 2019[5], de 93,3% à 93,9% da população escovam os dentes pelo menos duas vezes ao dia.

<p align=center>
<img src=Images/IBGE-Escovam-Os-Dentes.png width=90%>
</p>

Sendo assim, podemos estimar que cada pessoa gasta de 18,0g à 27,0g de pasta por mês, sendo assim, considerando a população nacional de aproximadamente 213,36 milhões de habitantes[6], temos um gasto de **aproximadamente 45.025.000 tubos de pasta de dente compradas ao mês no Brasil**.

O problema com este valor é que a quantidade de matérias disponíveis na internet sobre os riscos do uso exagerado de creme dental por escovação indicam que este pode ser um problema comum na vida dos brasileiros. Uma escova com creme dental como a de comerciais possuí muito mais do que 0,3 gramas, sendo assim, um motivo para que esta estimativa esteja subestimada.

Outro motivo pelo qual a estimativa provavelmente foi subestimada é o uso de pasta de dente para usos diversos, como por exemplo, o tratamento de espinhas, que não foram levados em consideração.

<p align=center>
<img src="https://publicdomainvectors.org/photos/toothbrush-with-toothpaste-2-by-gustavorezende.png" height="30%">
</p>

Outro fato que colabora com a hipótese de subestimativa, é que em 2002 a A C Nielsen, uma empresa especialista em coleta e análise de dados globais, calculou que a média de consumo de creme dental por habitante no ano é igual a 400 gramas[7][8]. Ou seja, aproximadamente 1,096 gramas de creme dental usadas por dia por habitante.

Como neste caso o dado oferecido pela instituição já foi feito a partir da média calculada (total de pasta usado / nº de habitantes), para encontrarmos o valor total vamos multiplicá-lo pelo valor total da população. Sendo assim, temos aproximadamente mais de 71.264.000 pastas consumidas no mês, representando um gasto de, no mínimo, mais de 156 milhões de reais.

## Curiosidade

Devido à cultura de higiene no Brasil, o país é lider na compra de produtos de higiene. Mais de 60% da população escova os dentes três vezes ao dia, enquanto a média global é apenas 9% da população. A previsão é de que, até 2025, o mercado de higiene oral movimentará mais que 9 bilhões de dólares em 5 anos, sendo que boa parte do dinheiro passa pela América do Sul, principalmente pelo Brasil.[9]

## Fontes

[1] [Mais Vendidos em Cremes Dentais - Amazon](https://web.archive.org/web/20210721063520/https://www.amazon.com.br/gp/bestsellers/hpc/16769385011/ref=zg_bs_nav_hpc_3_16769386011) Acessado em 20/07/2021 às 22:38

[2] [Sorrisologia - Qual a quantidade certa de creme dentaç para escovar os dentes?](https://web.archive.org/web/20210721212506/https://www.sorrisologia.com.br/noticia/qual-a-quantidade-certa-de-creme-dental-para-escovar-os-dentes_a3705/1) Acessado em 21/07/2021 às 18:27

[3] [Orientações aos pais sobre cuidados com a saúde bucal do bebê e das crianças - Associação Brasileira de Odontopediatria](https://edisciplinas.usp.br/pluginfile.php/5385038/mod_resource/content/1/ABOPED%20Orienta%C3%A7%C3%B5es%20pais%20cuidados%20s%C3%A1ude%20bucal%20beb%C3%AA%20crian%C3%A7as.pdf) Acessado em 21/07/2021 às 05:34

[4] [Sorrisologia -  Colocar mais creme dental na escova quer dizer que a limpeza é mais eficiênte?](https://web.archive.org/web/20181024070346/http://www.sorrisologia.com.br/noticia/colocar-mais-creme-dental-na-escova-quer-dizer-que-a-limpeza-e-mais-eficiente_a7968/1) Acessado em 21/07/2021 às 05:44

[5] [IBGE - Pesquisa Nacional de Saúde](https://www.ibge.gov.br/estatisticas/sociais/saude/9160-pesquisa-nacional-de-saude.html?edicao=29270&t=downloads) Acessado em 21/07/2021 às 08:40

[6] [IBGE - Projeção da População do Brasil e das Unidades da Federação](https://web.archive.org/web/20210721090237/https://www.ibge.gov.br/apps/populacao/projecao/index.html) Módulo U. Acessado em 21/07/2010 às 07:23

[7] [Mordor Intelligence - South America Oral Care Market - Growth Trends, Covid-19 Impact and Forecasts (2021-2026)](https://web.archive.org/web/20210721134210/https://www.mordorintelligence.com/industry-reports/south-america-oral-care-market)

[8] [Exame - Consumo](https://web.archive.org/web/20210721135556/https://exame.com/economia/consumo-m0040048/) Acessado 21/07/2021 às 10:58

[9] [The History and global market of oral home-care products](https://web.archive.org/web/20210721135740/https://www.scielo.br/j/bor/a/NLF8R3RWvyCGJnZmbcvRtkk/?lang=en) Acessado 21/07/2021 às 10:57