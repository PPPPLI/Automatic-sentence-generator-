Projet-TI301---Générateur-automatique-de-phrases

Lien Github: https://github.com/louart13/TP-projet-C.git

Mode d'emploi:

l'emplacement du fichier exécutable : ../ProjetC/cmake-build-debug/ProjetC.exe

NB:Avant démarrer le programme, changer le lien d'importation du dictionnaire dans le fichier importation.c  (Ligne 26)

if((fp = fopen(".._\\ProjetC\\dic.txt","r")) == NULL)

1.Demarrer le programme via un IDE comme Clion ou un terminal

2.Suivre les consignes pour avoir la phrase

par exemple:

Tapez 1 pour le modèle n°1 : nom – adjectif – verbe – nom

Tapez 2 pour le modèle n°2 : nom – ‘qui’ – verbe – verbe – nom – adjectif

Tapez 0 pour quitter

Choisissez un modèle de phrase:

Valeur inserée: 1

Résultat--> le schorre rhinopharyngien a fomentée l'hybridation (Base: schorre rhinopharyngien fomenter hybridation)

#end