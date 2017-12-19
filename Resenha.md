# OAC - Resenha

Tom Oliveira Souza - 201520140

Arquitetura Von Neumann vs Arquitetura Harvard

  A construção de um computador é caracterizada pela arquitetura utilizada no mesmo, por isso é importante que se conheçam suas estruturas. Cada arquitetura tem uma forma de funcionamento distinta que define suas capacidades e limitações. Como exemplo se tem a arquitetura Von Neumann e a arquitetura Havard.

  A arquitetura Von Neumann tem seu nome derivado de seu criador John Von Neumann, que é considerado como um dos melhores matemáticos do século passado. John foi o primeiro a redigir uma descrição praticamente completa de um computador, sendo o pilar para as estruturas aplicadas nos dias atuais.

  A estrutura proposta por John se divide essencialmente em quatro partes, são elas: Memória Principal, Unidade Central de Processamento (CPU), Unidade Lógica e Aritmética (ULA) e Unidade de Controle (CU). Essas partes são interligadas, cada uma com função fundamental no funcionamento da maquina.

  A Memória Principal é responsável por armazenar os dados e instruções da máquina, cada informação possui um endereço para localizar os dados, possibilitando que a CPU os encontre. A conexão entre CPU e Memória é feita através de barramentos que são os caminhos que interligam as estruturas da máquina. 

  A CPU é a parte motora, responsável por gerenciar a máquina, executar processos, buscar e armazenar dados na Memória. A CPU ainda engloba três unidades integradas a ela que são: ULA, Unidade de Controle e Registradores.

  A ULA é formada por circuitos, responsáveis na realização de operações com os dados, seja uma soma, subtração ou deslocamento de bits. A Unidade de Controle é formada também por circuitos, responsáveis por gerenciar a CPU, realizar busca de dados e instruções na Memória Principal e controlar o fluxo de dados entre os Registradores e a ULA.

  Os Registradores são as posições de memória construídas dentro da CPU, que pela proximidade, tem seus dados mais rapidamente acessados do que os dados armazenados na Memória Principal. Apesar da velocidade, os Registradores tem espaço limitado, reservando seu espaço a dados que estejam sendo utilizados com frequência.

  Além dessas quatro partes principais, existe também a Entrada e Saída que são a forma de interação entre a máquina e o meio externo (usuário). A exemplo temos o teclado ou mouse como dispositivos de Entrada e monitor ou impressora como dispositivos de saída.

  O ciclo de instruções da arquitetura de Von Neumann se divide em três partes que são: busca, decodificação e execução. Seguindo o ciclo, a máquina busca e pega o código da ação a ser realizada, o código é então interpretado (decodificado) na Unidade de Controle e a ação é realizada, fazendo o ciclo se repetir.

  Com passar dos anos os processadores evoluíram, se tornando mais rápidos, a Memória aumentou sua capacidade de armazenamento. Essas mudanças tornaram evidente a diferença de velocidade na leitura de dados da Memória e no processamento desses dados pela CPU, sendo uma tarefa mais lenta que a outra. Esse problema foi chamado de gargalo de Von Neumann, sendo um limitante nesse tipo de arquitetura.

  A arquitetura Havard tem seu nome derivado de sua origem na Universidade de Havard nos Estados Unidos, ela foi idealizada pelo pesquisador Howard Aiken com intuito de criar uma máquina que processasse de forma mais rápida.

  A arquitetura Harvard possui basicamente as mesmas partes da arquitetura de Von Neumann, tendo também Unidade Central de Processamento (CPU), Unidade Lógica e Aritmética (ULA), Unidade de Controle (CU) e Registradores. A diferença é que nessa arquitetura não se utiliza uma única Memória Principal, e sim duas Memórias independentes, que são ligadas a CPU por diferentes barramentos.

  Uma Memória fica responsável por armazenar os dados e a outra Memória fica responsável por armazenar as instruções, dessa forma a CPU consegue acessar ambas de maneira simultânea, permitindo a leitura de uma instrução ao mesmo tempo em que acessa os dados de memória, tornando o desempenho melhor otimizado. A arquitetura Havard também possui suporte a pipeline, que consiste na busca de mais de uma instrução por ciclo, o que a torna mais eficiente.
	
  O foco de cada arquitetura ao decorrer do tempo foi aplicado em áreas diferentes, visando às necessidades de cada mercado. A arquitetura de Von Neumann se direcionou aos computadores pessoais, com formato de instruções mais complexo, visto até hoje, apesar de sofrer mudanças e adição de componentes. A arquitetura Havard foi levada a área de microcontroladores por sua alta velocidade e desempenho para sistemas mais específicos e de instruções mais simples.
