## Resumo

"A fibra óptica vem sendo utilizada para atender a crescente demanda de tráfego de dados
em redes computacionais. As redes WDM flexíveis, recentemente propostas, oferecem capacidade
de alocação dinâmica de espectro para acomodação de diferentes taxas de transmissão. Nestas
redes, o problema fundamental, denominado como Routing and Spectrum Allocation (RSA), é
rotear e alocar o recurso espectral para acomodar as requisições de conexão. O RSA pode ser
dividido em dois subproblemas: roteamento e alocação de espectro. Na alocação de espectro, uma
conexão é atribuída a um ou mais slots de espectro, dependendo da capacidade de transmissão
requerida, e, se múltiplos slots são necessários, eles devem ser contíguos. Neste trabalho, estudase,
por meio de um modelo markoviano, o subproblema de alocação de espectro em um link de
uma rede WDM flexível. Uma heurística para acomodação das conexões que minimize a
fragmentação de espectro é proposta e comparada a outras da literatura.
PALAVARAS CHAVE. Redes Ópticas Elásticas, Alocação de "


## Anotações

"Uma arquitetura de rede óptica elástica, denominada rede WDM flexível (Flexible Optical WDM Network - FWDM), é proposta por Patel et al. (2010). Esta arquitetura baseia-se na tecnologia WDM e oferece capacidade de alocação dinâmica de seus recursos, em especial do espectro óptico, provisionamento dinâmico das conexões e controle automatizado da rede. Quando caminhos ópticos compartilham o mesmo link, eles devem ser separados um do outro no domínio de espectro por uma banda de guarda (guard band), que consiste em uma parte reservada e não utilizada do recurso espectral. O objetivo de se utilizar bandas de guarda é evitar a interferência entre as conexões sendo transmitidas simultaneamente. O problema RSA, assim como o RWA, pode ser estudado sob tráfegos estático e dinâmico. No caso estático (off-line), todo o conjunto de requisições de conexão é previamente conhecido, e, no caso dinâmico (on-line), as requisições de conexão chegam aleatoriamente e não há conhecimento sobre as requisições futuras. Devido à sua complexidade, o RSA comumente é dividido em dois subproblemas distintos: roteamento e alocação de espectro, que podem ser tratados separadamente. O autor cita referâncias dos primeiros algoritmos para tratar o problema. O artigo estuda a alocação de espectro em redes WDM flexíveis para cenários dinamicos. O sistema em estudo é modelado por um processo markoviano a tempo contínuo. Uma heurística para acomodação das requisições de conexão é proposta, e tem por objetivo minimizar a fragmentação de espectro.
Esta heurística é comparada a outras encontradas na literatura aplicáveis ao problema. Em redes ópticas elásticas, a dinâmica de alocação de recurso espectral para novas requisições e sua liberação ao término da transmissão provocam a criação de “buracos” entre os slots alocados para as transmissões correntes. Se esses “buracos” são pequenos e numerosos, eles podem não satisfazer futuras requisições que necessitam de blocos maiores que estes para sua alocação, provocando o aumento de rejeição de requisições de conexão. É importante que seja evitada ao máximo a criação desses blocos vazios entre os slots sendo utilizados para a transmissão das conexões. Este problema é conhecido como fragmentação e pode influenciar diretamente a eficiência destas redes (Wilson et al., 1995). TERMO:  taxa de processamento e transmissão de dados (throughput). "
