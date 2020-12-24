--------------------------------------------------------------------------------------------------------------------------
                                                        READ ME
--------------------------------------------------------------------------------------------------------------------------
Regle de Format pour la trame pris en INPUT:
- Nous suposons que le premier offset après un début de trame (OxOOOO) est toujours correct 
- Pas de ligne de commentaire dans la trame commençant pas un nombre Hexa égal à 0 en décimal (exemple: 0x0000,00 ect...).
- Pour un bon fonctionnement la trame doit ne doit pas etre en une seul ligne (minimum en 2 ligne avec offset)
- Une trame avec une ligne incomplète ou avec des informations erronées soulevera une erreur 

Si un fichier .txt contient une trame qui ne respecte pas ce format alors le logciel affichera un avertissement indiquant qu'il désactive le OffsetChecker
et vous fait confiance et tentera de lire celle-ci .