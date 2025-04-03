# Modelo OSI
* Computador da IBM só conversavam com os computadores do IBM
* Assim como os outros computadores das outras empresas faziam o mesmo (Ex: DEC)
* Portanto, caso aconteça de uma empresa quiser aumentar sua capacidade, teria que comprar do mesmo modelo
* Então surgiu essa necessidade para que os computadores de outras empresas conversassem entre eles
* Para facilitar a comuicaçao a ISO desenvolveu o OSI para que os fabricantes pudessem criar protocolos a partir desse modelo

## Modelo OSI de Arquitetura
* Procuravam objetivos
  * Interoperabilidade
  * Interconectividade
  * Portavilidade da Aplicação
 
* Interoperabilidade
  * Capacidade que os sistemas abertos possuem de troca da informação entre eles, mesmo se forem de fabricantes diversos
  * Devido a isso, a tecnologia barateou. Porque outras empresas poderiam fazer peças, e não havia mais necessidade da própria produtora do computador fabricar as suas peças
 
* Interconectividade
  *
   
* Portabilidade da Aplicação
  * Capacidade de um software rodar em várias plataforma diferentes
  * Exemplo: Java, C++
  * Java criou uma marquina virtual, que instalava no computador,o programa conversava com a maquina virtual, a marquina virtual conversava com o sistema operacional e o sistema operacional conversava com o hardware

* Para atinges esses objetivos passou a se preocupar em criar um padrao de arquitetura aberta baseada em CAMADAS
* Foi então criado o MODELO DE REFERENCIA PARA INTERCONEXÃO DE SISTEMAS ABERTOS

* VANTAGENS DE UM AMBIENTE DE SISTEMA ABERTO
  * Liberdade de escolha entre soluções de diversos fabricantes;
  * Acesso mais rápido a novas tecnologias e a preços mais acessíveis, já qie é mais barato e rápido fabricar produtos baseados em uma plataforma padrão
  * Redução de investimentos em novas máquinas, já que os sistemas e os softwares de aplicação são portáveis para os vários tipos de máquinas

* A adoção de modelo baseado em camadas
  * Considerando que um rede de ocmpitadores como objetivos o processamento detarefas distrivuidas pela rede de forma harmonica (conversando com a maquina), e cooperativa entre varias processos de aplicação, o projeto desta deve levar em conta vários fatores

* FATORES NA ADOÇÃO DE UM MODELO BASEADOS EM CAMADAS
  * Considerar todos os eventos possíveis de acontecer durante a comunicação;
  * Conhecer todos os efeitos e causas destes eventos;
    * Se falhar, tenho que saber porque falhou e onde falhou
  * Especificar em detalhes todos os aspectos técnicos-operacionais dos meios físicos a serem utilizados como suporte à comunicação
   * Tem que saber como que a comunicação funciona, para como acontece e como resolver
  *  Detalhes das próprias aplicações a serem executadas

 * A ELABORAÇÃO DE UM SISTEMA ABERTO PASSA POR ALGUMAS ETAPAS OBRIGATÓRIAS
  *
  * 

* A ARQUITETURA OSI FOI DESENVOLVIDA A PARTIR DE TRES ELEMENTOS BÁSICO
 * Os processos de aplicação existentes no ambiente OSI
 * As conexões que ligam os processos de aplicação e que permitem trocar informações;
 * Os sistemas 
 * ORG → CODEC → MODEM → MEIO → MODEM → CODEC → DEST
  * Para todos esse sistema de comunicação funcionar, é necessário que todos os itens acima fossem entendindos

Modelo OSI
* HARDWARE
 * 
* GERENCIAMENTO DE DADOS
 * Cuida de tarefas como acesso, manipulação e troca de vários tipos de dados
 * Uma consistência nesta tarefa é um grande passo a portabilidade
* LINGUAGEM
 * Tem sido feitos esforços em relação à criação de uma linguagem com independência da plataforma, para prover portabilidade
* INTERFACE COM USUÁRIO
 * Um dos principais fatores de portabilidade, já provê a interace com o usuário da aplicação
 * Cada vez mais estão sendo desenvolvidas
* COMUNICAÇÃO (REDE)
 *  

* MODELO OSI POSSUI 7 CAMADAS
 * Cada camada é usuária dos serviços prestados pelo serviço inferios
  * A camada 2 usa o serviço da camada 1, a camada 1 presta serviço para a camada 2 e assim por diante
 * Esta troca de inforções entre as camadas adjacentes ocorre por meio da troca de primitivias de serviços nas interfaces entre as camadas
 * O usuario está na 7 camada
 * A comunicação de dados está na camada 1, 2, 3, 4
 * Como elas convesão?
  * Elas conversam por meio das **PRIMITIVAS DE SERVIÇO**
 * Apesar da divisão em sete níveis, pode-se considerar genericamente que três camadas mais baixas cuidam dos aspectos relacionados à transmissão de dados propriamente dita e a camada de transporte lida com a <ins>**comunicação fim-a-fim** (camada 4 - transporte)(PROVA)</ins>, enquanto que as três camadas superiores se preocupam cos os aspectos relacionados à aplicação, já a nível de usuário

## 7 - APLICAÇÃO
## 6 - APRESENTAÇÃO
## 5 - SEÇÃO
## 4 - TRANSPORTE
## 3 - REDE
## 2 - ENLACE
## 1 - FÍSICA
