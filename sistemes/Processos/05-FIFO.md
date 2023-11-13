# Què és el FCFS o FIFO?

El FCFS és un dels algoritmes més senzills de planificació de processos. Segueix el principi de "qui arriba primer, és atès primer". En altres paraules, els processos s'executen en l'ordre en què arriben a la cua de planificació. Aquesta cua és una estructura de dades que manté un seguiment de tots els processos pendents d'execució. Quan un procés finalitza, el següent procés en la cua FCFS és seleccionat per ser executat.

Avantatges:

Simplicitat: És fàcil d'implementar i comprendre.
No hi ha inanició (starvation): Tots els processos eventualment seran executats.
Desavantatges:

Manca d'optimització: No sempre és l'opció més eficient en termes de temps d'espera.
Problemes d'injustícia: Processos llargs poden bloquejar processos més curts que arribin.