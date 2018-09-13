## Sentinel 2 MSI e Landsat 8 OLI Podem Detectar Classes Ópticas de Água Estabelecidas por Dados Hiperespectrais? Um Estudo de Caso nas Planícies de Inundação da Amazônia
 
Edson Filisbino Freire da Silva 
 
Instituto Nacional de Pesquisas Espaciais - INPE

Caixa Postal 515 - 12227-010 - São José dos Campos - SP, Brasil

edson.freirefs@gmail.com.br

### Introdução

A delimitação em diferentes classes ópticas de água tem sido utilizada para viabilizar ou otimizar modelos empíricos de sensoriamento remoto para propriedades biofísicas da água. Isso ocorre, porque a relação matemática entre a propriedade biofísica e a reflectância de sensoriamento remoto (Rrs) são diferentes para cada classe. Por exemplo, utilizando banda 1 (645 nm) do sensor MODIS para estimar a turbidez (T), Petus et al. (2010) desenvolveu o modelo empírico de T = 26,110x² + 604,5x + 0,24 para a pluma do rio Adour na França, enquanto Chen et al. (2007), utilizando a mesma banda, desenvolveu o modelo empírico T = 1,203 + 1087x para Baía de Tampa no Estados Unidos. Portanto, para a mesma propriedade biofísica e comprimento de onda, suas relações – ou modelos – podem ser diferentes, o que não permite utilizar um modelo de uma região em outra.

Além disso, diferentes classes de água podem ocorrer na mesma região e não permitir utilizar um único modelo. Para solucionar essa questão, diferentes técnicas têm sido utilizadas para classificar em diferentes tipos de água de acordo com o seu comportamento espectral. Duas técnicas são utilizadas para a classificação, através de espectroradiometria in situ e através de sensores orbitais. Espectroradiometria in situ tem maior capacidade de distinguir classes de água do que sensores orbitais, pois, possuem alta resolução espectral. Porém, sensores orbitais podem cobrir áreas mais extensas e com maior frequência, tendo maiores chances de detectar classes de águas diferentes.

Nas planícies de inundação da Amazônia, ocorrem diferentes cores de água que, consequentemente, podem ser diferentes classes. Para essa região, combinar a capacidade de se distinguir classes de água com espectroradiometria in situ com a capacidade espacial e temporal de sensores orbitais seria ideal para o monitoramento das propriedades biofísica da água, o que surge como motivação para este trabalho.

### 1. Objetivo

Este estudo, tem como objetivo investigar a capacidade dos sensores Sentinel-2 (A e B) MSI e Landsat OLI em discretizar classes ópticas de água na Amazônia, definidas por dados hiperespectrais. Primeiro, será obtido diferentes classes de água de utilizando a Rrs hiperespectral. Segundo, serão simuladas as bandas dos sensores com a Rrs in situ. Por último, será aplicado uma classificação em amostras de validação utilizando os dados hiperespectrais e as bandas simuladas, e, então, comparados a acurácia da classificação das banda simuladas em relação aos dados hiperespectrais.


### 2. Obtenção dos Dados

Os dados foram disponibilizados pelo labISA (INPE), os quais foram medidos por um sensor Trios, já pré-processados e em Rrs de acordo com a metodologia descrita por Mobley (1999). Os dados estão organizados da seguinte forma: Pasta raiz com nome do projeto (BNDES), subpastas com os nomes de cada campanha de campo, em cada campanha estão outros subpastas com o ponto de cada coleta (localização de cada medida do Trios). Em cada ponto, há uma subpasta chamada reflectância, onde está localizado um arquivo xlsx da Rrs in situ. A estrutura desse arquivo está organizada da seguinte forma, há uma folha com nome “Rrs”, e, em cada folha há o índice que corresponde ao comprimento de onda, e as colunas que correspondem a profundidade da medida.

### Referências

CHEN, Z.; HU, C.; MULLER-KARGER, F. Monitoring turbidity in Tampa Bay using MODIS/Aqua 250-m imagery. Remote Sensing of Environment, v. 109, p. 207–220, 2007.

MOBLEY, C. D. Estimation of the remote-sensing reflectance from above-surface measurements. Applied optics, v. 38, n. 36, p. 7442–7455, 1999.

PETUS, C.; CHUST, G.; GOHIN, F.; et al. Estimating turbidity and total suspended matter in the Adour River plume (South Bay of Biscay) using MODIS 250-m imagery. Continental Shelf Research, v. 30, n. 5, p. 379–392, 2010. Elsevier. Disponível em: <http://dx.doi.org/10.1016/j.csr.2009.12.007>.
