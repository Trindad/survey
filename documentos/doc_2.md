## Resumo

"Este artigo descreve um método mais flexível de alocação de
espectro para redes ópticas. O método mostra que uma alocação de espectro
com espaçamentos diferentes entre as frequências, ou seja, Gridless, é mais
eficiente que o método tradicional que usa espaçamentos iguais, Grid. Esta
nova proposta, que é baseada no sistema de transmissão OFDM, é conhecida
como Spectrum-Sliced Elastic Optical Path Network (SLICE) ou simplesmente
Redes Ópticas Elásticas. Neste novo tipo de arquitetura de rede, a largura de
banda de um caminho óptico pode ser elástica (a largura de banda varia de
acordo com a demanda), para assim se adaptar à demanda de tráfego da
camada superior. Neste artigo alguns critérios de otimização são validados e
propostos para distribuir o tráfego adequadamente (com grooming e sem
grooming) nesta nova arquitetura. Simulações foram realizadas para uma
rede de 6 nós e redes de grande dimensão. Os resultados sugerem a vantagem,
em termos de economia de espectro, do grooming em redes óptica elásticas e
economia de espectro em relação a redes ópticas tradicionais."


## Anotações

Artigo descreve um método mais flexivel de alocação de espectro. O trafego é roteado inteiramente no dominio óptico mediante o uso  de multiplexação por divisão de comprimento de onda (WDM), em que a largura de banda de uma fibra é loteado em diferentes raias espectrais com espaçamentos uniformes, chamadas de comprimento de onda. Um caminho óptico é formado pela concatenação nos nós roteadores de comprimentos de onda em diferentes fibras sem que saia do dominio fotônico. Com WDM vários caminhos ópticos podem ser estabelecidos simultaneamente em uma fibra óptica, o que permite uma ampla utilização da largura de banda.  Gridless - arquitetura de rede óptica sem a grade fixa, permite através do gerenciamento e seus elementos que compõe que o caminho óptico seja flexível, se expandindo e contraindo, conforme a demanda do cliente, as redes de caminhos ópticos elásticos - SLICE ou redes ópticas elásticas. Nessas redes o espectro é tratado como recurso continuo, o que possibilita uma maior compactação e uso do mesmo. O caminho óptico pode ser alocado em qualquer continuo de frequência e devem ser separados dos outros caminhos por uma banda de guarda, Filter Guard Band (FGB). Comutadores de comprimento  de onda seletivo (WSS ) e filtros ópticos de largura de banda variavel são utilizados para a comutação e a filtragem de largura de banda flexível (VER REFERÊNCIA). Nos transcepetores, o sistema de transmissão O-OFDM permite que os dados sejam enviados em subportadoras ortogonais e os sinais de cada subportadora estendam-se para a adjacente tal que o espectro seja bastante compactado .    O autor cita uma referência onde pode se encontrar novos conceitos (VER REFERÊNCIA). Além disso, trás uma imagem que mostra o comportamente de WDM e SLICE. Em seguida o autor explica o funcionamento de O-OFDM, que divide a largura do canal em várias subportadoras enviando os dados de forma independente. As subportadoras compactam bastante o domínio da frequência, assim, os sinais de cada portadora se estendem para as adjacentes. Contudo, a resposta em frequência de cada subportadora é projetada de modo que seja zero no centro das subportadoras adjacentes. As subportadoras podem, portanto, ser amostradas em suas frequências centrais sem interferências de seus vizinhos.  Autor fala sobre traffic grooming, o autor propõe formulações matemáticas para roteamento em SLICE com e sem grooming. "Pode-se verificar em [Takara et. al 2010] que levando em conta os impairments (restrições da camada física), aeconomia de espectro em redes ópticas elásticas pode chegar a 66% quando comparada as redes ópticas WDM tradicionais.". A estrategia com grooming ajudou no balanceamento de carga.
