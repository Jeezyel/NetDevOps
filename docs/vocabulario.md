# Vocabulário de termos usado no porjeto

SDN: redes definida por softwere , uma arquitetura que separa o controle da rede do envio de dados basicamente e uma modelo de arquitetura onde tem como principal caracteristira a criação de novas redes atraves de um codigo escreto 

DOCKER; uma ferramenta de para-virtualização. o que nos vamos dar um foco a mais e a parte de network de docker, criação de uma Vlan onde colocaremos alguns conteiner 

VLAN: e uma forma de ter ou criar uma rede local sem ter que gastar com equipamento fisoco como switch e cabos RJ45 e etc.

VM: para o porturges maquina virtual isso e esatamente o que voçê acha que é. e uma maquina que roda dentro de outra maquina sera como uma boneca rusa onde a primeira e a maquina fisica

DMZ:Demilitarized Zone ou seja um zona onde todos que estão nela são confiaves oque não vão fazer coisas que poça prejudicar a infra como baixar um arquivo suspeito ou clicar em um link errado, geralmente e computadores/VMs de servidores com serviços. em poucas palavars e uma rede separada das demais 

linux: e o sistema operacional de codigo aberto onde messoas comun pode mexer nele e criar suas verçãos do mesmo

GIT: e um controde de vercionamento local ou remoto 

Mininet: e um aferramenta que permite fazer teste em uma rede, pode criar ou testar uma rede que exite 

Open vSwitch: tambem chamado de 'OVS' virtualizado de um Switch

DMZ-IA: muda um puco da DMZ normal inves de um rede ceparada ela faz todo trafego paçar pela DMZ para a IA poder analisar o trafego  ficaria tipo 

              INTERNET
                 |
             [ FIREWALL ]
                 |
              [ DMZ ]
                 |
       [ Servidor Web ]
                 |
        IA monitora tráfego
                 |
             [ FIREWALL ]
                 |
          REDE INTERNA

ou poder ser apenas uma IA na DMZ ai seria uma DMZ normal com um serviço de IA nela.
A DMZ-IA é uma abordagem que integra a zona demilitarizada com a inteligência artificial para aprimorar a
segurança em redes, utilizando algoritmos para monitoramento e resposta eficiente a ameaças.

Dockerfile: e um arquivo de configuração de um imagem do docker 

Compose: e um arquivo de configuração de um conteiner ou mais 

HTTP: protocolo de comunicação na web

API:Application Programming Interface, a um forama de aplicação converçar entre si de um formato padronizado e documentado


