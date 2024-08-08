## Instruções gerais
- O presente repositório e seu conteúdo é de caráter pessoal e privado, não podendo ser compartilhado pelo candidato por quaisquer meios.
- A solução do exercício deverá ser elaborada única e exclusivamente pelo candidato, sem ajuda **pessoal** externa. Obviamente, não há problemas em caso de consultas em livros ou meios eletrônicos (não é permitida a submissão das questões deste teste em fóruns e comunidades online).
- O exercício em questão é fictício e não é parte de qualquer projeto real desenvolvido ou em desenvolvimento pela Kognita Lab.
- O exercício tem caráter classificatório, e não eliminatório. Portanto, caso tenha algum problema e não consiga resolver todo o exercício, envie a solução até onde conseguiu evoluir.
- A solução deverá ser entregue num repositório à parte, criado pelo candidato.
- Linguagem: Python.
- O prazo para entrega do exercício é de 1 semana. 

<br></br>
## Dados disponibilizados:

- "_data/footprint.parquet": dados anonimizados de eventos (coordenadas geográficas no tempo) associados a dispositivos móveis para o período de 1 semana.
- "_data/estabelecimentos.parquet": dataset contendo as unidades geolocalizadas.

Por meio da coluna "id_unidade" é possível associar ambas as bases de dados para as análises.


<br></br>
## Exercício

De maneira geral, "canibalização" no contexto de lojas de varejo físico refere-se à situação em que a abertura de uma nova loja de uma mesma rede ou marca leva a uma redução nas vendas de uma loja existente. Isso acontece porque ambas as lojas competem pelo mesmo grupo de clientes, o que resulta em uma redistribuição das vendas em vez de um aumento total no volume de vendas da empresa. Em outras palavras, as vendas que a nova loja gera são em parte retiradas das vendas da loja já estabelecida.

Estudar canibalização em um contexto real, não é tarefa trivial pois em muitas ocasiões os dados de operação são escassos. Com isso, é comum recorrermos à abordagens que empregam modelos fenomenológicos para tentarmos chegar a resultados razoáveis que podem ser empregados em escala.

Os dados disponibilizados compreendem eventos limitados à cidade de Campinsa-SP associados à dispositivos móveis (que, por simplificação, podemos aqui considerar como indivíduos) que foram capturados frequentando os estabelecimentos mapeados. Tomando como fato que são dados amostrais apenas, qual seria sua abordagem para ter uma medida aproximada de canibalização entre as unidades em questão? Desenvolva o raciocínio tanto conceitualmente (explicitando as premissas e hipóteses que sustentam a construção do seu modelo), quanto montando um toy model na prática, em Python.

Ps.: "modelo" no contexto do exercício não necessariamente significa modelo de aprendizado de máquina.

<br><br>
## Requisitos da entrega

- Repositório organizado com as melhores práticas que conhecer.
- Slides apresentando a construção conceitual do modelo e os resultados obtidos.
- Após a entrega, será agendada uma reunião para apresentação e discussão dos resultados.


