# Execució de processos: 

L'execució de processos és un procés complex que involucra la CPU, la memòria i altres recursos del sistema. Entendre com els processos es gestionen i executen és clau per a la gestió eficient del sistema.

## 6.1 Creació de Processos:

El cicle comença amb la creació d'un procés. Aquesta operació implica la reserva d'espai de memòria, la inicialització de les variables i altres configuracions necessàries.
El procés nou passa a l'estat "Nou" i espera ser programat pel sistema operatiu.

## 6.2 Planificació i Assignació de Recursos:

El sistema operatiu decideix quin procés serà programat i utilitzarà la CPU en un moment determinat. Aquesta decisió es pren amb l'ajuda d'algorismes de planificació, com ara el Round Robin o el FCFS. El procés seleccionat passa a l'estat "En Execució" i utilitza la CPU per realitzar les seves tasques.

## 6.3 Accés a la Memòria:

El procés en execució té accés a la seva pròpia àrea de memòria, que conté el codi executable i les dades associades. La gestió de la memòria implica assegurar-se que els processos no es corrompin mútuament i que cada procés tingui prou espai per a la seva execució.

## 6.4 Entrada/Sortida:

Durant l'execució, un procés pot haver de realitzar operacions d'entrada/sortida, com llegir o escriure dades en un dispositiu. Quan això succeeix, el procés passa a l'estat "Bloquejat" fins que l'operació d'entrada/sortida s'ha completat.

## 6.5 Canvi d'Estats:

Els processos poden canviar d'estat, com ara de "En Execució" a "Bloquejat" quan esperen una operació d'entrada/sortida o de "Bloquejat" a "Llest" quan aquesta operació s'ha completat.
Aquests canvis d'estat es gestionen pel sistema operatiu mitjançant crides al sistema i planificació.

## 6.6 Finalització:

Quan un procés ha completat totes les seves tasques, passa a l'estat "Finalitzat". En aquest punt, el sistema operatiu allibera els recursos associats al procés, com ara memòria i handles d'arxius. Comprendre aquest cicle d'execució és essencial per als administradors de sistemes, ja que els permet gestionar eficientment els recursos del sistema i assegurar-se que els processos s'executen de manera coherent i sense problemes.

## Més informació:
- [Introducció](01%CC%A3-Introduccio.md)
- [Què són els processos?](02-Que-son-els-processos.md)
- [Components dels processos](03-Components-processos.md)
- [Planificació de processos](04-Planificacio-de-processos.md)
- [FIFO](05-FIFO.md)
- [Round Robin](06-Round-Robin.md)
- [Estats dels processos](07-Estats-processos.md)