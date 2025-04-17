# Criação de uma VM na Azure

Ao criar uma máquina virtual (VM) na Azure, é possível configurar diversas opções importantes:

- **Zona de disponibilidade**  
  Define a região física onde a VM será provisionada. Isso influencia diretamente na resiliência e disponibilidade da aplicação.

- **Nível de SLA (Service Level Agreement)**  
  O nível de SLA está relacionado à alta disponibilidade da VM, podendo ser elevado com a utilização de múltiplas zonas de disponibilidade.

- **Redundância dos dados**  
  A Azure oferece diferentes opções de replicação de dados, como:
  - LRS (Locally Redundant Storage)
  - ZRS (Zone-Redundant Storage)
  - GRS (Geo-Redundant Storage)  
  Isso garante proteção contra falhas locais ou regionais.

- **Imagem do sistema operacional**  
  É possível escolher entre imagens do Windows, Linux ou até mesmo imagens personalizadas, conforme a necessidade da aplicação.

- **Arquitetura da máquina**  
  A escolha do tipo de VM define a quantidade de CPU, memória, armazenamento e rede. Pode-se selecionar configurações otimizadas para computação, memória ou armazenamento intensivo.

- **Desligamento automático**  
  Recurso útil para ambientes de desenvolvimento e testes. Permite configurar o desligamento da VM em horários específicos, ajudando a reduzir custos com recursos não utilizados.

---

> ⚙️ Essas configurações tornam a criação de VMs na Azure flexível e adaptável para diferentes cenários de negócio.
