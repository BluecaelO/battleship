# Jeux de la bataille navale en C

Bnv1 version 1 : connexion entre 1 client et 1 serveur  
Bnv2 versions 2 : Taille de la grille de jeux variables (taille max 20 x 20)  
Bnv3 versions 3 : connexion entre plusieurs clients et 1 serveur  

/!\ IP à modifier avant la compilation si on souhaite un changement d'ip/!\  
==> battleshipV1.1/bnv3.1/src/client.c (ligne 37)  
Par défaut le client se connecte au loopback  

```
addrClient.sin_addr.s_addr=inet_addr("127.0.0.1");
```

Noublier pas de compiler avec cmake dans le répertoire battleship:

```
>> cmake.
>> make
```

Je vous recommande d'utiliser Linux.

L'utilisation de windows peut possiblement causé des bugs.L'utilisation de Windows peut possiblement causer des bugs.
