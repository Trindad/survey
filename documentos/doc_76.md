## Resumo

"Elastic Optical Networks has drawn a lot of attention in the past few
years because of its ability to transmit different data rates increasing ou decre-
asing the optical spectrum according to the necessary demand, ensuring a high
spectral efficiency. However, establishing and tearing down different connec-
tions ends up segmenting the spectrum in several small fragments, making it
impossible for new requests to be attended. Besides, another recurrent problem
in elastic optical networks, called routing and spectrum assignment (RSA), aims
to fing a path and assign to it a contiguous number of spectrum slots using the
smallest possible amount of spectral resources. The main purpose of this paper
is to propose an algorithm to minimize the spectrum fragmentation problem in
Elastic Optical Networks by using RSA algorithms. Results obtained through
simulations indicates that the proposed algorithm outperforms in terms of bloc-
king probability and spectrum fragmentation ratio the other existing ones.
"


## Anotações

Artigo propõe uma variação do RSA (Routing Spectrum Assignement), para a a alocação de recursos, ou seja, seu objetivo é encontrar um caminho e alocar a menor quantidade de slots de forma a otimizar a capacidade do espectro. Além disso, o artigo explica inicialmente o conceito de redes elásticas, e a difere das demais existentes. Apresenta a diferença entre SLICE (Spectrum-Sliced Elastic Optical Path Network) , FWDM (Flexible Optical Wavelength Division Multiplexing), e redes com taxas de dados flexível. Explica o que se utiliza para a divisão do spectrum (OFDM - Orthogonal Frequency-Division Multiplexing ), que permite o formato variável de modulação, taxa de dados e espectro de tamanho variado (Para estes conceitos sugere indice 82 da planilha).  O autor cita que as redes FWDM são uma evolução das WDM e que as redes flexíveis possuem uma grande flexibilidade quanto a taxa de dados, mas com relação ao espectro não é permitido tamanho variável. O objetivo de redes SLICE é alocar uma demanda de largura de banda fim-a-fim que seja apropriada, sendo que a diferença de FWDM está na possibilidade de contração e expanção de acordo com a necessidade. O artigo também cita as principais tecnologias que compõe a rede SLICE. O BVT (Bandwidth Variable Transceivers) resposável pela granularidade fléxivel do dominio espectral, permitindo o ajuste do recurso de acordo com a demanda. O BV-WXCs (Brandwidth Variable Wavelength Cross-Connects ) , tem a reponsabilidade de estabeler um caminho fim-a-fim com largura de banda exata para acomodar os recursos espectrais (Apresenta esquema da arquitetura igual ao artigo do Jinno). Onde as BVTs ficam nas bordas da rede e BV-WXCs ficam no núcleo da rede.  Tabela com esquema de modulações e referência para Dahlfort 2012 e a representação de caminhos ópticos elásticos e rigidos (imagem igual a do Jinno). Cita também a alta capacidade das redes ópticas elásticas frente a restauração adaptativa, citando artigo que fala sobre alocação adaptativa. Faz em seguida a descrição do problema do RSA (Bibliografia a ser buscada), apresenta um resumo breve de RSA online e RSA offline. O autor apresenta os algoritmos do RSA existentes até então, MSP (Menor caminho modificado), SCPVS(Spectrum Constraint Path Vector Searching - utiliza busca em largura ), k-menores caminhos, DF(Degree Fragmentation) e AP(Acceptance Prone) que são propostos em um mesmo artigo . Em seguida é apresentado o problema de fragmentação do espectro,  o autor apresenta equações para calcular a fragmentação. Por fim o autor propõe um algoritmo para minimizar a fragmentação, através da escolha dos caminhos (RSA-MF), provando a eficiencia do algoritmo quando a analise do estado atual do espectro.Este artigo possui muitas referências para artigos de ordem mais relevante.
