# BakkesMod-BodySwap
Self exlpanatory

How to install BakkesMod with body swap:
Replace dll at : %AppData%\bakkesmod\bakkesmod\dll\bakkesmod.dll

Patch list to do it yourself to do it yourself if you don't trust the dll
--- Patchs à faire -----
///// ARRIVE A FULL STQBLE ET FONCTIONNEL DANS LE MENU
---------------------------------
2 jmp dans la gui + nop padding
Fonction: sub_18008ABC0 
Addresse 18008B4BA et 000000018008C4E5
Effet : Rend la selection des voitures possible via le dropdown menu
----------------------------------
180121E20 mov al, 1 et rtn
Effet: Has minimum toujours a 1
----------------------
1801176EB : nop le call à FC0
effet : Garde la selection de la gui en mémoire
-----------------------
180117997 : nop le jump
180117773 : nop le jump
effet: Kill le filtre qui equipe rien si c'est l'id 0
-----------------------
//PATCH POUR INGAME 
-----------------------
180113124: Nop le jump
18011318F: nop le jump
18011326E : nop le jump
1801132CF : nop le jump
Effet: Empeche le flag Shouldskip, ingame pour les 2 équipes
-------------------------

Second DLL is alpha console with custom cars working in online mode and patrons features unlocked (tho some are unstable and im too lazy to fix), but custom cars working without problem

