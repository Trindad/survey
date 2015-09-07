## Resumo

"A natureza rígida de redes de multiplexação por divisão de comprimentos de onda (WDM)
provoca exploração ineficiente de capacidade espectral. Dessa forma, redes flexíveis são um
possível avanço para a tecnologia óptica por viabilizarem melhor aproveitamento dos
recursos espectrais disponíveis. Com o intuito de aferir a possível aplicabilidade de redes
flexíveis, este trabalho propõe uma estratégia de avaliação de desempenho baseada em
simulações e comparações entre resultados obtidos. Para tanto, várias simulações a tempo
discreto foram implementadas em dois simuladores desenvolvidos em Matlab a fim de
analisar diferentes políticas de alocação de espectro (First-Fit, Smallest-Fit, Exact-Fit e
Random-Fit) em três algoritmos de roteamento por caminhos ópticos não híbridos: o
roteamento por fragmentação externa (FA), por caminhos mais curtos com máxima
eficiência de reuso espectral (SPSR) e por balanceamento de cargas (BLSA). Duas
topologias de rede foram utilizadas: um pequeno subconjunto de 6 nós da Cost239 e uma
topologia aleatória de 7 nós. Admitindo-se que efeitos de camada física não foram
configurados como restrições, foram realizadas comparações entre as diversas técnicas
estudadas, objetivando-se apontar, baseado nas especificidades dos cenários propostos, qual
o método mais adequado de alocação espectral em termos de frequência de bloqueio entre as
quatro políticas de alocação de espectro consideradas.
"


## Anotações

O autor trás o conceito de redes elásticas, WDM, DWDM. Além disso descreve resumidamente os três problemas de redes ópticas elásticas no ambito do nó e da rede (pg 25). O autor apresenta esquemas/imagens que representam as redes elásticas. Existem muitas restrições observadas em problemas referente ao roteamento e alocação do espectro em redes SLICE: * As demandas da origem-destino devem ser exatamente adicionadas a fonte e entregues ao destino, * Um slot em um fibra deve ser usado no máximo para servir um caminho espectral, * Cada caminho óptico deve utilizar o mesmos slots ao longo do percurso, *  Caminhos adjacentes devem ser separados por banda de guarda, especificada por um número inteiro de slots, * Os slots empregados no cmainho óptico devem ser consecutivos no dominio da frequência. O autor faz comparações com algoritmos de alocação de espectro.
