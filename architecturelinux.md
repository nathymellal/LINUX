# Linux

## Architecture_Linux :small_red_triangle:

```
\
├── bin
|   ├── cd
|   ├── nano
|   ├── mv
|   └── ...      //contient les commandes de LINUX
|
├── home
|   ├── lost+found     // ne peut pas être ouvert
|   └── osboxes        // nom de l'utilisateur
|       ├── Desktop
|       ├── Documents
|       └── ...        // contient fichiers perso du user
|
├── root  // répertoire admin système
|
├── sys   // fonctionnalité système
|   ├── block
|   ├── bus
|   ├── class
|   ├── dev
|   ├── device
|   ├── firmware
|   ├── fs
|   ├── hypervisor
|   ├── kernel
|   ├── module
|   └── power
|
├── boot   // système pour le lancement
|   ├── grub
|   └── ... -amd64
|
├── mnt
|
├── run    // fichiers pour l'execution
|   ├── alsa
|   ├── cup
|   └── ...
|
├── tmp
|   └── ...  // Fichiers temporaires
|
├── dev      //périphériques
|   ├── stdin
|   ├── stdout
|   ├── cdrom
|   └── ...
|
├── usr
|   ├── bin
|   ├── games
|   ├── include
|   ├── lib
|   ├── lib32
|   ├── lib64
|   ├── libexec
|   ├── libx32
|   ├── local
|   ├── sbin
|   ├── share
|   └── src
|
├── etc   //configuration système
|   ├── sudoers
|   ├── sudoers.d
|   └── ...
|
├── proc
|   └── ... // tous les fichiers temp de processus
|
└── var // données variables

```



























Accèdons à notre terminal et on effectue un **ls -a** : 

- Vidéos : Répertoire qui stocke les vidéos.
- Public : Répertoire qui stocke tout types de fichiers qui seront lisibles par tous les utilisateurs.
- .mozilla : Répertoire qui permet de stocker des fichiers propres à cette application.
- Images : Répertoire qui stocke les images.
- Documents : Répertoire qui contient les documents, les fichiers de l'utilisateur.
- Bureau : Répertoire où l'on peut stocker n'importe quelles types de fichiers, et ainsi de les avoir sur notre bureau pour accès rapide.
- Téléchargements : Répertoire qui contient les téléchargements venant d'internet.
- Musique : Répertoire qui stocke la musique.
- .cache : Est une zone de mémoire vive (RAM) utilisé comme un magasin temporaire pour les fichiers. Il est utilisé par le noyau.
- .ssh : Est à la fois un programme informatique et un protocole de communication sécurisé.
- .local : Contient des logiciels compilés sur place à partir des sources.
- .gnupg : GNU Privacy Guard permet le chiffrement et la signature de données. (Comme le courriel & la messagerie instantanée...).
- .config : Ce sont les fichiers de configation, comme les réglages d'affichages, la langue, la vitesse de transmission....
