# Unidade Central de Processamento (CPU)

A CPU de um computador é composta por vários elementos e pode ser dividida em duas categorias funcionais, a Unidade Funcional de Controle e Unidade Funcional de Processamento. Na Figura 2.2, pode-se observar o diagrama funcional básico da CPU, no qual a Unidade Funcional de Processamento é composta pelos registradores, ACC e ULA, e a Unidade Funcional de Controle é composta pelos elementos: RDM, REM, CI, RI, Decodificador de Instruções, UC e Clock (relógio) (FÁVERO, 2011).

Um ponto importante que merece ser destacado é a velocidade com que a CPU trabalha, medida por ciclos de clock. Ciclo de clock é o tempo gasto pelo processador para executar uma operação ou para transferir um dado entre ele e a memória e que define sua velocidade. Este tempo é medido em Hertz, ou seja, quantos ciclos são processados por segundo. Os processadores atuais trabalham com velocidades na casa dos Gigahertz (PATTERSON, 2014).

## Barramentos

Os componentes do processador são interligados pelos barramentos que permitem esta movimentação entre os dados (MONTEIRO, 2007). Ainda segundo Monteiro (2007), um barramento é o caminho por onde trafegam todas as informações de um computador. Existem três tipos principais de barramentos:

-   Barramento de dados.
-   Barramento de endereços.
-   Barramento de controle.

**Barramento de dados** - Este barramento interliga a CPU à memória, e vice-versa, para a transferência das informações que serão processadas. Ele determina diretamente o desempenho do sistema, pois quanto maior o número de vias de comunicação, maior o número de bits transferidos e, consequentemente, maior a rapidez com que estes dados serão processados. Os primeiros PCs possuíam barramento de 8 vias. Atualmente, dependendo do processador, este número de vias pode ser de 32, 64 e até de 128 vias (FÁVERO, 2011).

**Barramento de endereços** - Interliga a CPU à memória fazendo seu endereçamento e tem o número de vias correspondente à tecnologia de bits do processador, ou seja, nos computadores mais modernos, 32 bits ou 64 bits e conforme já visto por você, permitindo endereçar até 4 GB (Gigabytes) de memória em processadores 32 bits e cerca de 16 PB (Petabytes), no caso de processadores de 64 bits (SOUZA FILHO, 2014).

**Barramento de controle** - Interliga na CPU à Unidade de Controle aos componentes e dispositivos de um computador, componentes de entrada e saída, memórias auxiliares e de armazenamento, entre outros. Por trabalhar com componentes externos ao processador, pode ser chamado também de barramento externo (MONTEIRO, 2007).

## Projetos de Processadores

Segundo Monteiro (2007), o que define um projeto de um processador é a quantidade de instruções de máquina que se deseja que ele, processador, execute, quanto menor este conjunto de instruções, mais rápido se torna um processador. Partindo deste princípio, os processadores têm dois tipos de arquiteturas empregadas pelos seus fabricantes:

-   A arquitetura CISC (Complex Instruction Set Computers) – Sistema com um conjunto de instruções complexo, atualmente utilizado pelos processadores de computadores pessoais;
-   A arquitetura RISC (Reduced Instuction Set Computes) – Sistema com um conjunto de instruções reduzido, que é empregado nos processadores ARM utilizados pelos smartphones e tablets atuais (MONTEIRO, 2007).

**Processadores CISC (Complex Instruction Set Computers)** - Os processadores com tecnologia CISC são capazes de processar centenas de conjuntos complexos de instruções simples. Isto significa que cada instrução isoladamente é considerada simples, curta e pouco potente, porém várias destas instruções agrupadas formam um conjunto complexo que é executado pelo processador. Inicialmente, existia uma grande tendência a esta tecnologia de processadores, porém havia algumas desvantagens, como o desempenho reduzido justamente pelo excesso de instruções executadas pelo processador e pela velocidade de processamento ter que ser elevada para que o desempenho fosse melhorado. A ideia dos fabricantes era produzir processadores cada vez mais potentes baseados na complexidade destes conjuntos de instruções (BROOKSHEAR, 2013).

**Processadores RISC (Reduced Instuction Set Computes) -** Os processadores com tecnologia RISC têm um conjunto reduzido de instruções, e diferente da tecnologia CISC, estas instruções são consideradas complexas, pois cada uma delas executa várias tarefas conjuntas. Isto permite uma vantagem dos processadores RISC em relação aos processadores CISC, que por ter um número menor de instruções tem menos circuitos internos e assim podem trabalhar com frequências muito maiores sem ter problemas de superaquecimento dos processadores (BROOKSHEAR, 2013).

Os processadores podem ser de dois tipos de acordo com sua tecnologia: Processadores CISC, que processam centenas de conjuntos complexos de instruções simples. Isto significa que cada instrução isoladamente é considerada simples, curta e pouco potente, porém várias destas instruções agrupadas formam um conjunto complexo que é executado pelo processador.

Processadores RISC têm um conjunto reduzido de instruções, e diferente da tecnologia CISC, estas instruções são consideradas complexas, pois cada uma delas executa várias tarefas conjuntas.
