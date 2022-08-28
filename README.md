# Panorama-do-COVID-19-no-Brasil
Neste notebook, iremos analisar os dados referentes à Covid-19 no Brasil e no Mundo.

**Este é um projeto proposto no curso Data Science Na Prática 3.0 do [Sigmoidal](https://sigmoidal.ai/).**

---
![](img/im01.jpg)

Em 31 de dezembro de 2019, a Organização Mundial da Saúde (OMS) foi alertada sobre vários casos de pneumonia na cidade de Wuhan, província de Hubei, na República Popular da China. Tratava-se de uma nova cepa (tipo) de coronavírus que não havia sido identificada antes em seres humanos.

Uma semana depois, em 7 de janeiro de 2020, as autoridades chinesas confirmaram que haviam identificado um novo tipo de coronavírus. Os coronavírus estão por toda parte. Eles são a segunda principal causa de resfriado comum (após rinovírus) e, até as últimas décadas, raramente causavam doenças mais graves em humanos do que o resfriado comum.

Ao todo, sete coronavírus humanos (HCoVs) já foram identificados: HCoV-229E, HCoV-OC43, HCoV-NL63, HCoV-HKU1, SARS-COV (que causa síndrome respiratória aguda grave), MERS-COV (que causa síndrome respiratória do Oriente Médio) e o, mais recente, novo coronavírus (que no início foi temporariamente nomeado 2019-nCoV e, em 11 de fevereiro de 2020, recebeu o nome de SARS-CoV-2). Esse novo coronavírus é responsável por causar a doença COVID-19.

Em 11 de março de 2020, a COVID-19 foi caracterizada pela OMS como uma pandemia. O termo “pandemia” se refere à distribuição geográfica de uma doença e não à sua gravidade. A designação reconhece que, no momento, existem surtos de COVID-19 em vários países e regiões do mundo.

Para mais informações acesse este [link](https://www.paho.org/pt/covid19/historico-da-pandemia-covid-19).

Fato é, estudos estão sendo realizados no mundo todo, porém os resultados ainda não são conclusivos e definitivos.

**Com o objetivo de elevar a consciência situacional a respeito do COVID-19 no Brasil, irei realizar uma análise sobre os dados públicos da doença.**

---

## Sobre os dados

Os dados utilizados neste projeto são mantidos pelo **Our World in Data (OWID)**. 

O [OWID](https://ourworldindata.org/) é uma publicação científica online que se concentra em grandes problemas globais, como pobreza, doenças, fome, mudanças climáticas, guerra, riscos existenciais e desigualdade. Seu objetivo é tornar o conhecimento sobre os grandes problemas acessível e compreensível.

**Como descrito bem no site do projeto, a missão do OWID é publicar a “pesquisa e dados para avançar contra os maiores problemas do mundo”.**

Os dados esão disponíveis [aqui](https://github.com/owid/covid-19-data/tree/master/public/data) e são atualizados diariamente, enquanto durar a pandemia.

A fonte principal dos dados utilizados pelo OWID é o **Centro de Ciência e Engenharia de Sistemas (CSSE) da Universidade Johns Hopkins**. O conjunto de dados dos casos registrados e óbitos é atualizado diariamente.

---
**Notas importantes:**

1 - Os dados referentes a esta aálise foram baixados no dia **16/08/2022**.

2 - Os dados de casos confirmados e óbitos são coletados pela Johns Hopkins University por data de relatório, em vez de data de teste/óbito. Portanto, o número que eles relatam em um determinado dia não representa necessariamente o número real naquela data, devido à longa cadeia de notificação que existe entre um novo caso/óbito e sua inclusão nas estatísticas. Isso também significa que as séries temporais podem mostrar mudanças repentinas (negativas ou positivas) quando um país corrige dados históricos, porque anteriormente havia sub ou superestimado o número de casos/óbitos.