# ASCON128

# Introduction
Le but de est d'utiliser le language de description matérielle Systemverilog pour concevoir un circuit 
permettant de chiffrer un message sur 256 bits à l'aide de l'algorithme ASCON128.
Le projet est exhaustif et présente aussi l'ensemble des test qui ont été réalisés sur chaque composant.

Pour une description plus detaillée veuillez lire le rapport joint au projet.


# Structure
Les fichiers liés aux architectures Systemverilog sont situés dans le répertoire "/SRC",
pour ce projet deux bibliothèques associées ont été mises en place pour faciliter la compilation
et l'exécution : "LIB_RTL" et "LIB_BENCH".

Les fichiers de testbench se trouvent dans le répertoire "SRC/BENCH". Ceux cisont facilement identifiables grâce à leur nom du type xxx_tb.sv.
De plus, il existe un répertoire (SRC/RTL) qui contient les fichiers décrivant l'architecture
du circuit des différents composants.

Enfin le projet comprend le pakcage "ascon_pack". Ce dernier englobe les définitions de
types couramment utilisés, tels que la structure type_state.
