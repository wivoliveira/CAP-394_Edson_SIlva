Capacidade do Sentinel 2, Sentinel 3 e Landsat 8 em Detectar Diferentes Tipos �pticos de �gua nas Plan�cies de Inunda��o na Amaz�nia
�
Edson Filisbino Freire da Silva 1
�
1 Instituto Nacional de Pesquisas Espaciais - INPE
Caixa Postal 515 - 12227-010 - S�o Jos� dos Campos - SP, Brasil
edson.freirefs@gmail.com.br
�
1.����� Introdu��o
A delimita��o em diferentes classes de �gua tem sido utilizada para viabilizar ou otimizar modelos emp�ricos de sensoriamento remoto para propriedades biof�sicas da �gua. Isso ocorre, porque a rela��o matem�tica entre a propriedade biof�sica e a reflect�ncia de sensoriamento remoto (Rrs) s�o diferentes para cada tipo de �gua. Por exemplo, utilizando banda 1 (645 nm) do sensor MODIS para estimar a turbidez (T), Petus et al. (2010) desenvolveu o modelo emp�rico de T = 26,110x� + 604,5x + 0,24 para a pluma do rio Adour na Fran�a, enquanto Chen et al. (2007), utilizando a mesma banda, desenvolveu o modelo emp�rico T = 1,203x1087 para Ba�a de Tampa no Estados Unidos. Portanto, para a mesma propriedade biof�sica e comprimento de onda, suas rela��es � ou modelos � podem ser diferentes, o que n�o permite utilizar um modelo de uma regi�o em outra.
Al�m disso, diferentes classes de �gua podem ocorrer na mesma regi�o e n�o permitir utilizar um �nico modelo. Para solucionar essa quest�o, diferentes t�cnicas t�m sido utilizadas para classificar em diferentes tipos de �gua de acordo com o comportamento espectral. Duas t�cnicas s�o utilizadas para a classifica��o, atrav�s de espectroradiometria in situ e atrav�s de sensores orbitais. Espectroradiometria in situ tem maior capacidade de distinguir classes de �gua do que sensores orbitais, pois, possuem alta resolu��o espectral. Por�m, sensores orbitais podem cobrir �reas mais extensas e com maior frequ�ncia, tendo maiores chances de detectar classes de �guas diferentes.
Nas plan�cies de inunda��o da Amaz�nia, ocorrem diferentes cores de �gua que, consequentemente, podem ser diferentes classes. Para essa regi�o, combinar a capacidade de se distinguir classes de �gua com espectroradiometria in situ com a capacidade espacial e temporal de sensores orbitais seria ideal para o monitoramento das propriedades biof�sica da �gua, o que surge como motiva��o para este trabalho. 
�
2.����� Objetivo
Este estudo, tem como objetivo investigar a capacidade dos sensores Sentinel-2 (A e B), Sentinel-3 e Landsat OLI em discretear classes de �guas distintas na Amaz�nia. Primeiro, ser� obtido diferentes classes de �gua de utilizando a Rrs em todos comprimentos de ondas. Segundo, ser�o simuladas as bandas dos sensores com a Rrs in situ. Por �ltimo, ser� aplicado uma t�cnica de detec��o de novidade para classificar diferentes amostras (dados de valida��o) em tipos de �gua, utilizando todo o espectro e as banda simuladas, e, ent�o, comparados os tipos de �guas detectadas por cada um.
�
�
3.������ Dados Dispon�veis
Os dados dispon�veis in situ foram medidos pelo sensor Trios, j� pr�-processados e em Rrs de acordo com a metodologia descrita por Mobley (1999). Os dados est�o organizados da seguinte forma: Pasta raiz com nome do projeto (BNDES), subpastas com os nomes de cada campanha de campo, em cada campanha est�o outros subpastas com o ponto de cada coleta (localiza��o de cada medida do Trios). Em cada ponto, h� uma subpasta chamada reflect�ncia, onde est� localizado um arquivo xlsx da Rrs in situ. A estrutura desse arquivo est� organizada da seguinte forma, h� uma folha com nome �Rrs�, e, em cada folha h� o �ndice que corresponde ao comprimento de onda, e as colunas que correspondem a profundidade da medida.
�
4.������ Resultados Esperados
Eu espero obter diferentes classes de �gua nas �guas interiores da Amaz�nia, que possam futuramente otimizar o desempenho de algoritmos para qualidade da �gua, como turbidez, material particulado em suspens�o e clorofila-a. E, descobrir qual o melhor m�todo e qual capacidade de se detectar essas classes de �gua pelo sensor Sentinel-2, �3 e Landsat OLI.
