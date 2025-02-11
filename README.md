# docker-for-noobs

## O que são containers
É um empacotador de codigo e dependencias que permite a execução de forma rapida e conscistente em qualquer ambiente

## Principais pontos
- Imutabilidade: Toda vez que um container é executado ele é identico
- Isolado: É totalmente separado da maquina principal (processos, redes, recursos computacionais como memoria cpu)
- Leve: É um processo do sistema operacional, sobe e morre rapidamente
- Kernel do SO: Dentro do container são criados volumes, de forma que o container se comunique com o SO
- Rapido: Inisiar, parar, remover
- Imagem imutavéis: Pacote fechado (snapshot)
- Linux é REI
- "Em todas as máquinas funciona"

## Container VS Máquina virtual
- Maquina virtual: Executa um SO completo, utiliza hypervisor para gerencias varias VMs, consome muitos recursos da máquina principal. (Hypervisor: instala varios SO em um SO principal)
  - Maior tempo de inicialização, menor eficiencia em uso de memoria e cpu
  - Escalabilidade devagar
- Containers: Compartilha kernal do SO, é isolado, inicializa rapidamente, economia de recurso
