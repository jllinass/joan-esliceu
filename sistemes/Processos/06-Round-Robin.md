# Què és el Round Robin?

L'algoritme Round Robin és més equitatiu i assegura que cada procés tingui una oportunitat d'execució regular. Cada procés és assignat un temps fix d'execució, anomenat quàntum de temps. Quan un procés utilitza tot el seu quàntum, és posat al final de la cua i el següent procés en la cua obté el control de la CPU. Aquest procés continua fins que tots els processos hagin finalitzat.

Avantatges:

Equitat: Cada procés rep una part justa de temps de CPU.
Prevenció d'inanició: Tots els processos tenen l'oportunitat d'execució.
Desavantatges:

Overhead de canvi de context: Si el quàntum de temps és molt petit, es pot produir un overhead significatiu en el canvi de context.
Temps d'espera potencial: Alguns processos poden esperar més temps del que seria òptim en comparació amb altres algoritmes.