# Projet_6502

## Description du projet

Le but du projet est d'afficher "Hello, World !" sur un écran LCD à l'aide d'un microprocesseur 6502.

## Origine du projet

Le projet provient du tutoriel de Bean Eater et utilise le kit acheté sur son site.
[Lien vers le tutoriel](https://youtube.com/playlist?list=PLowKtXNTBypFbtuVMUVXNR0z1mu7dp7eH&feature=shared)

## Motivation du projet

La motivation pour ce projet vient d'une envie d'explorer plus en détail comment un ordinateur fonctionne au niveau de l'hardware.

## Problèmes rencontrés

1. Tout le matériel n'était pas fourni dans le kit, j'ai donc dû acheter de l'équipement, un programmeur EEPROM, sur Alibaba ainsi qu'une alimentation 5V. Cela m'a fait perdre quasiment 2 à 3 semaines en attendant leur arrivée.
2. Le câblage était problématique. Comme chaque vidéo ajoutait des connexions, j'ai dû recommencer le câblage plusieurs fois et regarder toute la série en entier plusieurs fois pour organiser comment j'allais brancher les puces.
3. Comme je pensais qu'il fallait rédiger un document, j'ai consulté plusieurs sites pour mieux comprendre le fonctionnement de l'assembleur, de chaque composant ainsi que leur utilité, avantages et inconvénients.

## Documentation

Pour ce projet, il y a deux fichiers qui le font fonctionner. "Hello_world.6502.s" est le fichier en assembleur qui permet d'afficher "Hello, World !" sur l'écran. Cependant, l'ordinateur ne peut pas lire directement de l'assembleur, c'est pourquoi il a fallu créer "hello_world.bin", un fichier binaire que j'ai ensuite flashé sur mon EEPROM.

Si vous voulez voir le contenu de "hello_world.bin", vous pouvez utiliser la commande :

`hexdump -X hello_world.bin`

Elle affichera le contenu du fichier binaire.

## Temps

  J'ai passé environ 20 à 30 heures sur ce projet, entre la partie théorique et la partie pratique.

### Pratique

1. Environ 10 heures pour couper des câbles, mettre en place les puces et effectuer le câblage.
2. 2 à 3 heures à essayer de faire fonctionner la technologie, que ce soit le programmeur, la conversion de fichiers en binaire ou le codage des fichiers.

### Théorie

1. 5 à 6 heures pour faire des recherches sur les aspects techniques du projet, comme le fonctionnement d'une porte NAND, de la RAM, etc.
2. 5 heures à regarder les vidéos du tutoriel et à organiser le projet.
3. 2 à 3 heures à lire la théorie, comme l'assembleur, le fonctionnement d'un EEPROM et la lecture du binaire. Ce sont surtout des sujets liés au domaine de l'informatique.