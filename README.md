murilo.krominski@fgv.edu.br

Analisador de DNA X Doenças e Predisposições Genéticas - Por Murilo Krominski
Idealizado e criado por Murilo Krominski, este é provavelmente, no mundo, o primeiro Analisador de DNA X Doenças e Predisposições Genéticas, gratúito e feito para qualquer pessoa que possua os dados Brutos do seu DNA (Raw Data), feito por qualquer laboratório. Qualquer um poderá conhecer as suas predisposições genéticas, isto é, os seus riscos de desenvolver determinadas doenças genéticas. Por hora analisa apenas 18 variantes genéticas associadas ao desenvolvimentos de doenças, mas irá aumentar em futuras atualizações que eu realizar, e trata de descobrir problemas como:

Doença de Wilson
Deficiência de Alfa-1 Antitripsina (variante PI*Z)
Deficiência de Alfa-1 Antitripsina (variante PI*S)
Deficiência de fator XII
Trombofilia (Fator II - Protrombina)
Trombofilia (Fator V de Leiden)
Hemocromatose tipo 1 (variante H63D)
Hemocromatose tipo 1 (variante C282Y)
Hemocromatose tipo 1 (variante S65C)
Infarto do miocárdio
Doenças mieloproliferativas
Amiloidose hereditária (variante V122I)
Amiloidose hereditária (variante V50M)
Amiloidose hereditária (variante T80A)
Polipose associada ao gene MUTYH (variante G396D)
Doença de Parkinson e Doença de Gaucher (gene GBA)
Doença de Parkinson (gene LRRK2)
Câncer
Com os resultados, você poderá se planejar melhor para o futuro, sempre com o auxílio de um profissional especializado. É importante recordar que há outros fatores, além dos genéticos, que influenciam no surgimento de doenças.

O arquivo de origem deve estar no formato .csv, se chamar "origem.csv" e possuir os dados dispostos da seguinte forma:

1ª Coluna: RSID: string Se disponível, carrega a variante rsID, que identifica o ramo dentro do banco de dados genético público dbSNP(SNP, sigla em inglês para Polimorfismo de Nucleotídeo Único, é uma variação do DNA em uma única base nucleotídica que nos permite traçar propensões e características..)

2ª Coluna: CHROMOSOME: string Indica o número do cromossomo onde se situa a variante genética. Existem 22 pares de cromossomos autossômicos que são indicados com um número e os cromossomos sexuais que são nomeados como X e Y. Há também marcadores no DNA mitocondrial que aparecem listados como “MT”.

3ª Coluna: POSITION: string É a posição variante no cromossomo, a posição do marcador genético de acordo com o conjunto genético humano GRCh37 (http://grch37.ensembl.org/index.html).

4ª Coluna: RESULT: string • O par de valores observados (alelo 1 e alelo 2 - representando os lados paterno e materno, não necessariamente nessa ordem), contém resultados de genotipagem para os marcadores genéticos.
