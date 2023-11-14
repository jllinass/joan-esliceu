# Què és el FCFS o FIFO?

El FCFS és un dels algoritmes més senzills de planificació de processos. Segueix el principi de "qui arriba primer, és atès primer". En altres paraules, els processos s'executen en l'ordre en què arriben a la cua de planificació. Aquesta cua és una estructura de dades que manté un seguiment de tots els processos pendents d'execució. Quan un procés finalitza, el següent procés en la cua FCFS és seleccionat per ser executat.

Avantatges:

Simplicitat: És fàcil d'implementar i comprendre.
No hi ha inanició (starvation): Tots els processos eventualment seran executats.
Desavantatges:

Manca d'optimització: No sempre és l'opció més eficient en termes de temps d'espera.
Problemes d'injustícia: Processos llargs poden bloquejar processos més curts que arribin.

## Més informació:
- [Introducció](01%CC%A3-Introduccio.md)
- [Què són els processos?](02-Que-son-els-processos.md)
- [Components dels processos](03-Components-processos.md)
- [Planificació de processos](04-Planificacio-de-processos.md)
- [Round Robin](06-Round-Robin.md)
- [Estats dels processos](07-Estats-processos.md)
- [Execució de processos](08-Execucio-processos.md)