# FCSC 2023 May the Fifth


Un utilisateur de ```zForth``` a, pour des raisons de performances, désactivé ASAN ainsi que ```ZF_ENABLE_BOUNDARY_CHECKS```, car selon lui “setjmp/longjmp est désactivé et c’est bien suffisant”. Saurez-vous le détromper en lisant le contenu du fichier contenant le flag ?

**Note :** Une variante plus simple de cette épreuve est disponible ici : May The Forth.





Fichiers:
- [may-the-fifth](may-the-fifth)
- [may-the-fifth-public.tar.xz](may-the-fifth-public.tar.xz)




Auteurs : cde et [Cryptanalyse](https://x.com/Cryptanalyse)


Origine : [May the Fifth](https://hackropole.fr/fr/challenges/pwn/fcsc2023-pwn-may-the-fifth/)



-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc may-the-fifth.cyrhades.fr 4000

-----------

## Ou directement avec netcat
> nc localhost 4000


-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2023-pwn-may-the-fifth.git

> cd fcsc2023-pwn-may-the-fifth


-----------


## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2023-pwn-may-the-fifth/