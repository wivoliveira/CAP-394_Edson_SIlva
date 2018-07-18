# CAP-394_Edson_SIlva
Repositório do Projeto da discplina CAP-394

Capacidade do Sentinel 2, Sentinel 3 e Landsat 8 em Detectar Diferentes Tipos Ópticos de Água nas Planícies de Inundação na Amazônia
 
Edson Filisbino Freire da Silva 
 
Instituto Nacional de Pesquisas Espaciais - INPE
Caixa Postal 515 - 12227-010 - São José dos Campos - SP, Brasil
edson.freirefs@gmail.com.br

1.	Introdução

A delimitação em diferentes classes de água tem sido utilizada para viabilizar ou otimizar modelos empíricos de sensoriamento remoto para propriedades biofísicas da água. Isso ocorre, porque a relação matemática entre a propriedade biofísica e a reflectância de sensoriamento remoto (Rrs) são diferentes para cada tipo de água. Por exemplo, utilizando banda 1 (645 nm) do sensor MODIS para estimar a turbidez (T), Petus et al. (2010) desenvolveu o modelo empírico de T = 26,110x² + 604,5x + 0,24 para a pluma do rio Adour na França, enquanto Chen et al. (2007), utilizando a mesma banda, desenvolveu o modelo empírico T = 1,203x1087 para Baía de Tampa no Estados Unidos. Portanto, para a mesma propriedade biofísica e comprimento de onda, suas relações – ou modelos – podem ser diferentes, o que não permite utilizar um modelo de uma região em outra.
Além disso, diferentes classes de água podem ocorrer na mesma região e não permitir utilizar um único modelo. Para solucionar essa questão, diferentes técnicas têm sido utilizadas para classificar em diferentes tipos de água de acordo com o comportamento espectral. Duas técnicas são utilizadas para a classificação, através de espectroradiometria in situ e através de sensores orbitais. Espectroradiometria in situ tem maior capacidade de distinguir classes de água do que sensores orbitais, pois, possuem alta resolução espectral. Porém, sensores orbitais podem cobrir áreas mais extensas e com maior frequência, tendo maiores chances de detectar classes de águas diferentes.
Nas planícies de inundação da Amazônia, ocorrem diferentes cores de água que, consequentemente, podem ser diferentes classes. Para essa região, combinar a capacidade de se distinguir classes de água com espectroradiometria in situ com a capacidade espacial e temporal de sensores orbitais seria ideal para o monitoramento das propriedades biofísica da água, o que surge como motivação para este trabalho. 

2.	Objetivo

Este estudo, tem como objetivo investigar a capacidade dos sensores Sentinel-2 (A e B), Sentinel-3 e Landsat OLI em discretear classes de águas distintas na Amazônia. Primeiro, será obtido diferentes classes de água de utilizando a Rrs em todos comprimentos de ondas. Segundo, serão simuladas as bandas dos sensores com a Rrs in situ. Por último, será aplicado uma técnica de detecção de novidade para classificar diferentes amostras (dados de validação) em tipos de água, utilizando todo o espectro e as banda simuladas, e, então, comparados os tipos de águas detectadas por cada um.


3.	Dados Disponíveis

Os dados disponíveis in situ foram medidos pelo sensor Trios, já pré-processados e em Rrs de acordo com a metodologia descrita por Mobley (1999). Os dados estão organizados da seguinte forma: Pasta raiz com nome do projeto (BNDES), subpastas com os nomes de cada campanha de campo, em cada campanha estão outros subpastas com o ponto de cada coleta (localização de cada medida do Trios). Em cada ponto, há uma subpasta chamada reflectância, onde está localizado um arquivo xlsx da Rrs in situ. A estrutura desse arquivo está organizada da seguinte forma, há uma folha com nome “Rrs”, e, em cada folha há o índice que corresponde ao comprimento de onda, e as colunas que correspondem a profundidade da medida.

4.	Resultados Esperados

Eu espero obter diferentes classes de água nas águas interiores da Amazônia, que possam futuramente otimizar o desempenho de algoritmos para qualidade da água, como turbidez, material particulado em suspensão e clorofila-a. E, descobrir qual o melhor método e qual capacidade de se detectar essas classes de água pelo sensor Sentinel-2,  3 e Landsat OLI.
