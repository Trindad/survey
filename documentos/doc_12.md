## Resumo

"Optical networks are undergoing significant
changes, fueled by the exponential growth of
traffic due to multimedia services and by the
increased uncertainty in predicting the sources
of this traffic due to the ever changing models of
content providers over the Internet. The change
has already begun: simple on-off modulation of
signals, which was adequate for bit rates up to 10
Gb/s, has given way to much more sophisticated
modulation schemes for 100 Gb/s and beyond.
The next bottleneck is the 10-year-old division of
the optical spectrum into a fixed “wavelength
grid,” which will no longer work for 400 Gb/s
and above, heralding the need for a more flexi-
ble grid. Once both transceivers and switches
become flexible, a whole new elastic optical net-
working paradigm is born. In this article we
describe the drivers, building blocks, architec-
ture, and enabling technologies for this new
paradigm, as well as early standardization efforts.
"


## Anotações

"International Telecommunication Union (ITU) .Este artigo basicamente consite em um survey sobre redes SLICE. O artigo apresenta uma figura que representa a diferença na alocação do espectro em uma rede com grade fixa e uma flexivel (SLICE - também neste artigo trata redes elásticas como EONs).  reconfigurable optical add-drop multiplexer (ROADM - A reconfigurable optical add-drop multiplexer (ROADM) is a device that can add, block, pass or redirect modulated infrared (IR) and visible light beams of various wavelengths in a fiber optic network. ROADMs are used in systems that employ wavelength division multiplexing - http://www.infonetics.com/whitepapers/infonetics-roadm-evolves-white-paper-february-2006.pdf). O termo elastic refere a duas propriedades chaves: 1º O espectro óptico pode ser flexivelmento todo dividido. 2º Os transcepetores podem gerar caminhos ópticos elásticos (EOPs), que são, caminhos com taxas de bits variadas.  Os novos transceptores são chamados de  bandwidth variable transceivers (BVTs). Principais paradigmas de EONs: *Suporte para 400 Gb/s, 1 Tb/s, e outras demandas de taxa de bits altas. Em redes com a grade fixa, estes valores conseguem ser transportados, fazendo a divisão em menores, no processo de demultiplexação, entretantanto este processo irá utilizar todo o espectro rapidamente que se utilizasse EOP. * Necessidades de bandas desiguais. Dividir o espectro em tamanhos proporcionais para cada demanda com base na taxa de bit e a distancia da transmissão , faz com que o seu uso seja otimizado (em vez de de forçar todas as demandas para usar mais espectro).  *Espaçamento de canal mais apertado. Permite que outras demandas para o espectro. * Trade-off entre eficiência espectral X alcance. Se um EOP é menor em distancia, o BVT pode ajustar para o formato de modulação ocupando menos espectro óptico, e a conexão ainda irá executar livre de erro devido a redução dos danos (exemplo: ruidos adicionados pelos amplificadores) em caminhos de curta distancia. * Redes dinamicas. A camada óptica pode agora responder diretamente por largura de banda variável  para a camada cliente (autor insere exemplo). Em seguida o autor apresenta uma tabela comparado fixed grid com EON com enlaces ponto a ponto, mostranto que há uma significante diferença entre elas e principalmente a vantagem da rede elástica. Na figura 2 pode ser visto a diferença e vantagem na alocação do espectro. ""One of the main challenges in an EON is how to determine the minimum necessary spectral resources and adaptively allocate them to an optical channel with minimum guard band assigned between channels."" A EON permite um mapeamento bem aproximado entre o cliente e a camada de transporte. * ""When the link requires more (or less) bandwidth, the EOP is extended (or contracted) hitlessly
in the most efficient way to accommodate the demand."" *""When a failure occurs, some client links will carry the load from the failed links. Their bandwidth should be extended automatically. Some of the failed links may be rerouted automatically
in the EON, by exploiting possibly different modulation, FEC and spectrum to overcome the longer reach of a protection path. "" * ""Periodically, there may be a need for the above described hitless spectrum reallocation process"". O artigo fala do problema do RSA que esta subdividido em dois, primeiro estágio é criar uma lista de rota com numero suficiente FSU (frequency slot) livres continuos da origem ao destino (corridor width), e determinar o formato da modução para cada par origem-destino dada sua taxa de bit (Fig. 4a do artigo tem mais detalhes). No segundo estágio ocorre as alocações contiguas  dos FSUs para uma taxa (Fig 4b).  O autor também refere-se a algoritmos como First Fit para minimizar a fragmentação do espectro. "
