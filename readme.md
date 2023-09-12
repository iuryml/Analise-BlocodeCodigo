# Campanhas de Marketing - Bloco de Código #

Construção de Dashboard analítico para a empresa Bloco de Código, a empresa que será desenvolvida para elaboração deste projeto.

| :placard: Alura | Challenge BI  |
| -------------  | --- |
| :label: Tecnologias | Excel, Power BI, Figma (tecnologias utilizadas)
| :derelict_house: Empresa         | Bloco de Código

![image](https://github.com/iuryml/Analise-BlocodeCodigo/assets/55949523/9833adf3-d208-4e4d-ac76-b4b91bac49cb)

Em todo o projeto resolvi formatar com as cores da empresa e a logo no fundo representando a sua marca. Toda a etapa de prototipagem foi realizada com Figma

## Objetivo ##
Monitorar a sua campanha de marketing durante o ano que a campanha foi realizada.

### Descrição do Dashboard ###
O projeto de análise de Campanhas de Marketing foi realizado para identificar possíveis pontos de melhorias e observação de pontos a serem preservados. Busca atender a necessidade de identificar as categorias menos rentáveis, com menos visualizações e com mais visualizações, que consequentemente são as mais rentáveis.

### Visão Geral do Dashboard ###
O dashboard possui no total 3 páginas de apresentações visuais dos gráficos e o Menu Principal, como alocado no início da página. Cada página fornece uma visão referente ao volume de artigos e quantidades de categorias. 

#### Página 2 – Bloco1 ####
<p>Na página do Bloco1, resolvi apresentar valores importantes da Campanha de Marketing referentes ao volume de vários aspectos, como, Total de Cliques, Visualizações, Tempo de Leitura, CTR (Click Through Rate) e o percentual referente a cada tipo de visitas ao artigo onde calculei o Percentual de Cliques Pagos, Cliques de Redes Sociais, Visitas Diretas e Vezes Pesquisados, fornecendo uma visão geral por categoria.<br>
Há o gráfico de colunas por categoria evoluindo com Tempo total de Visualizações e Tempo de Leitura por minutos.</p>

<p>Para chegar a essas métricas foram feitos algumas medidas em DAX para os cálculos. Realizei a junção da soma de Cliques de Redes Sociais e Pagos.<br> O cartão de Visualizações e Tempo de Leitura foi feita uma medida de Soma dos valores. Na métrica para cálculo do CTR é necessário obter <b>(Total de Cliques / Total de Visualizações) * 100</b>.<br> Para os cálculos de percentual, foi utilzada a medida DIVIDE e como esse cálculo retorna o valor bruto, foi utilizado o FORMAT para converter para o formato "0,00%" em Porcentagem.</p>

![image](https://github.com/iuryml/Analise-BlocodeCodigo/assets/55949523/0e122708-f657-402b-8ce1-60944d329505)

#### Página 3 – Bloco2 ####
<p>A página do Bloco2 fornece a visão sobre a quantidade média total de artigos e traçando a linha média de cor amarela com valor de 2,47 Mil visualizações. Essa linha serve para ter a visão de quais artigos estão acima ou abaixo da média.<br></p>
<p>Mais em baixo coloquei uma narrativa inteligente descrevendo que o artigo “<b>Melhores práticas para gerenciamento de dados</b>” teve o maior Média de Visualizações e foi <b>86.670,85%</b> maior do que “<b>Como usar o feedback para acelerar o crescimento da carreira</b>”, que teve a menor Média de Visualizações</p>

![image](https://github.com/iuryml/Analise-BlocodeCodigo/assets/55949523/a0cfeb3c-c193-4ca1-b8a5-6401052422db)

#### Página 4 – Bloco3 ####
<p>A página do Bloco3 fornece a visão de quantidade total e média de novos usuários únicos que foram adquiridos durante a campanha da empresa. Vejamos um volume temporal por data em Dia e Mês do ano de 2021.<br>
Os filtros de data são sempre os de quando se tornou novo usuário. Importante observar que a data começa a vigorar desde o 1º (Primeiro) dia do mês até o último dia.</p>
  
![image](https://github.com/iuryml/Analise-BlocodeCodigo/assets/55949523/958eef6b-cf6b-4897-aa6f-ea22f7745ea9)

#### Página 5 - Bloco4 ####
<p>A página do Bloco4 fornece a visão da soma de volume total de visualiações por artigo, determinando qual teve o maior número de visualizações para o menor.</p>

![image](https://github.com/iuryml/Analise-BlocodeCodigo/assets/55949523/dc806021-53f6-4d2a-8570-47145da238c3)

## Conclusão ##

<p>Com a finalização desse projeto, podemos perceber que houve um grande volume de leitura e visualização dos artigos em categorias da Gestão, Data Science (Ciência de Dados) e Tecnologia.<br>
O artigo "Escuta ativa e como isso mudará sua abordagem" teve o maior número de visualizações ao todo da categoria de Gestão e o <b>"Como usar o feedback para acelerar o crescimento da carreira"</b> teve o menor número de visualizações da categoria Gestão.<br>
Os dias 21, 23 e 10 foram os dias que mais teve números de Novos Usuários Únicos.</p>
