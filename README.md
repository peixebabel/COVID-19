# COVID-19
Dados e plots sobre as informações do Corona Virus levantadas pelo Peixe Babel.

## Brasil 

### Óbitos por Data do Óbito
O script ```Obitos_BR_por_data.ipynb```replica o gif produzido pelo [Observatório COVID19](https://covid19br.github.io/%E2%80%9D#fig1%22) para fins didáticos. O plot animado imprime os reportes quase diários de óbitos por data de ocorrência do óbito, permitindo perceber que os reportes mais recentes são uma janela para o passado, tratando de óbitos ocorridos há dias ou semanas.

![Óbitos no Brasil](https://github.com/peixebabel/COVID-19/blob/master/imagens/obitos-br-por-data.gif)

O arquivo ```data/casos-br-total.csv``` até o momento trás o número total de casos suspeitos, confirmados e mortes no Brasil. Suas informações foram compiladas no script ```COVID-19_Brasil.ipynb```. Como foi interrompido o reporte de casos suspeitos, traremos aqui apenas os casos confirmados e as projeçoes.

![Casos Confirmados no Brasil](https://github.com/peixebabel/COVID-19/blob/master/imagens/Confirmados-Total.png)

## Mundo 
O notebook ```Crescimento_Mundial.ipynb``` traz análises comparativas de números e casos e óbitos dos 10 países mais afetados. O resultado desse script são as seguintes imagens (referentes a 02 de Maio):

![Casos Confirmados no Brasil](https://github.com/peixebabel/COVID-19/blob/master/imagens/casos-02-05.jpg)

![Casos Confirmados no Brasil](https://github.com/peixebabel/COVID-19/blob/master/imagens/obitos-02-05.jpg)


O notebook ```COVID-19_Mundial.ipynb``` compila as informações do mundo inteiro, divididas por região. As informações foram retiradas do repositório: https://github.com/CSSEGISandData/COVID-19 <br>
O resultado do notebook mundial é um gif animado com o avanço dos casos **confirmados** ao redor do mundo.

![Casos confirmados ao redor do mundo](https://github.com/peixebabel/COVID-19/blob/master/imagens/mundial-covid19.gif)

#### Situação Mundial (17/03/2020)
![Situação mundial (17/03/2020)](https://github.com/peixebabel/COVID-19/blob/master/imagens/mundial-valores-17-03.png)

## China

O notebook ```COVID-19_China.ipynb``` produz o gráfico apresentado na ![live do Átila Iamarino](https://www.youtube.com/watch?v=7jHgS4yxS0A), doutor em virologia. 
> Note que as medidas preventivas da China que pararam o país, tiveram início em 23/01/2020. Ainda assim, depois dessa data, foram registrados dezenas de milhares de casos, principalmente daqueles que já haviam sido infectados antes do lockdown.

![Casos por dia, China](https://github.com/peixebabel/COVID-19/blob/master/imagens/data-covid19-china.gif)

## Comparação dos dados entre Itália e Brasil

Casos confirmados na Itália e projeção baseado na média de crescimento de 10 dias. Em azul os casos confirmados, em vermelho a projeção.

![Casos confirmados na Itália e projeção baseado na média de crescimento de 10 dias. Em azul os casos confirmados, em vermelho a projeção.](https://github.com/peixebabel/COVID-19/blob/master/imagens/covid-italia-projecao.png)

Taxas de crescimento da Itália.

![Taxas de crescimento da Itália](https://github.com/peixebabel/COVID-19/blob/master/imagens/crescimento-italia.png)

Casos confirmados no Brasil e projeção baseado na média de crescimento de 10 dias. Em azul os casos confirmados, em vermelho a projeção.

![Casos confirmados no Brasil e projeção baseado na média de crescimento de 10 dias. Em azul os casos confirmados, em vermelho a projeção.](https://github.com/peixebabel/COVID-19/blob/master/imagens/covid-brasil-projecao.png)

Taxas de crescimento do Brasil.

![Taxas de crescimento do Brasil](https://github.com/peixebabel/COVID-19/blob/master/imagens/crescimento-brasil.png)

Comparação entre as taxas de crescimento da Itália (em azul) e do Brasil (em vermelho).

![Comparação entre as taxas de crescimento da Itália (em azul) e do Brasil (em vermelho)](https://github.com/peixebabel/COVID-19/blob/master/imagens/crescimento-comparativo.png)

Os dados foram retirados do Ministério da Saúde do Brasil e do https://www.worldometers.info/coronavirus/
