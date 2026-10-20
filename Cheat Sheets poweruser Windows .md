#  Cheatsheet & Cours : OS, Histoire de Windows & Outils Power User

---

##  1. Cours : Systèmes d'Exploitation (OS) & Histoire de Windows

### 1.1 Définition et Fonctionnement Général d'un OS
- **OS (Operating System / Système d'Exploitation) :** Ensemble de programmes qui gère les ressources matérielles d'un ordinateur et fournit des services aux logiciels d'application.
- **Composants fondamentaux :** Au niveau matériel le plus basique, un processeur (CPU) et de la mémoire vive (RAM) suffisent pour exécuter des instructions.

#### Couches d'Abstraction & Démarrage
- **HAL (Hardware Abstraction Layer) / Firmware :** Couche intermédiaire entre le matériel et l'OS (ex. BIOS ou UEFI moderne).
- **Séquence de démarrage (Bootstrapping) :**
  1. **POST (Power-On Self-Test) :** Test matériel initial exécuté par le BIOS/UEFI dès la mise sous tension.
  2. **BIOS / UEFI :** Initialisation des périphériques de base et recherche du secteur de démarrage.
  3. **Bootloader (Chargeur d'amorçage) :** Programme (ex. GRUB, Windows Boot Manager) chargé d'amorcer le noyau de l'OS en mémoire.
  4. **OS, Pilotes (Drivers) & Applications :** Chargement du noyau, activation des pilotes matériels dédiés, puis lancement de l'interface utilisateur.

---

---

##  2. Raccourcis Clavier Windows

| Raccourci | Fonction / Description | Catégorie |
| :--- | :--- | :--- |
| `Win` | Ouvrir ou fermer le menu Démarrer | Système & Bureau |
| `Win + E` | Ouvrir l'Explorateur de fichiers | Navigation & Fichiers |
| `Win + R` | Ouvrir la boîte de dialogue "Exécuter" | Système & Bureau |
| `Win + Pause` | Afficher les Propriétés système | Système & Bureau |
| `Win + L` | Verrouiller la session / l'ordinateur | Sécurité |
| `Win + D` | Afficher ou masquer le bureau | Fenêtres & Bureau |
| `Win + M` | Réduire toutes les fenêtres (`Shift` pour restaurer) | Fenêtres & Bureau |
| `Win + ← / →` | Ancrer la fenêtre à gauche ou à droite | Fenêtres & Bureau |
| `Win + ↑ / ↓` | Agrandir / Réduire la fenêtre active | Fenêtres & Bureau |
| `Win + 1 à 9` | Activer le programme correspondant de la barre des tâches | Barre des tâches |
| `Win + T` | Parcourir les applications de la barre des tâches | Barre des tâches |
| `Win + B` | Focus sur la zone de notification (Systray) | Barre des tâches |
| `Win + +` / `Win + Esc` | Activer / Désactiver la Loupe | Accessibilité |
| `Alt` | Activer la barre de menu du programme actif | Navigation |
| `Alt + [lettre]` | Exécuter le menu correspondant à la lettre soulignée | Navigation |
| `Alt + Tab` | Basculer entre les applications ouvertes | Navigation |
| `Alt + Esc` | Parcourir directement les fenêtres ouvertes | Navigation |
| `Ctrl + C` / `Ctrl + X` / `Ctrl + V` | Copier / Couper / Coller | Édition |
| `Ctrl + A` | Tout sélectionner | Édition |
| `Ctrl + Z` / `Ctrl + Y` | Annuler / Rétablir la dernière action | Édition |
| `Ctrl + Home` / `Ctrl + End` | Aller tout en haut / tout en bas d'un document | Navigation & Texte |
| `Ctrl + Shift + Home/End` | Sélectionner du texte jusqu'au haut / bas | Navigation & Texte |
| `Ctrl + S` / `F12` | Enregistrer / Enregistrer sous | Fichiers |
| `Ctrl + N` / `Ctrl + O` / `Ctrl + P` | Nouveau document / Ouvrir / Imprimer | Fichiers |
| `Ctrl + T` / `Ctrl + W` | Nouvel onglet / Fermer l'onglet ou la fenêtre | Navigation Web |
| `Ctrl + F` | Rechercher dans la page ou le document | Navigation Web |
| `Ctrl + Alt + V` | Collage spécial (options d'affichage) | Édition |
| `Ctrl + Molette` | Modifier le zoom (agrandir/réduire) | Affichage |
| `Ctrl + ← / →` | Déplacer le curseur mot par mot | Navigation & Texte |
| `Ctrl + ↑ / ↓` | Déplacer le curseur paragraphe par paragraphe | Navigation & Texte |
| `Ctrl + Shift + Flèches` | Sélectionner du texte mot par mot / ligne par ligne | Navigation & Texte |
| `Ctrl + Tab` | Changer d'onglet dans une application | Navigation Web |
| `Ctrl + F4` / `Alt + F4` | Fermer le document actif / Quitter le programme | Système |
| `Shift + F10` | Menu contextuel (équivalent clic droit) | Système |
| `Esc` / `Espace` | Annuler / Cocher une case ou valider | Système |
| `F1` / `F5` | Aide / Actualiser | Système |
| `F2` | Renommer le fichier ou modifier une cellule | Fichiers |
| `F10` / `F11` | Activer le menu / Basculer en Plein écran | Affichage |
| `Ctrl + Shift + Esc` | Ouvrir le Gestionnaire des tâches | Système |
| `Alt + Impr. Écran` | Capture d'écran de la fenêtre active | Captures |
| `Impr. Écran` | Capture d'écran de tout l'écran | Captures |
| `Alt + Entrée` | Afficher les Propriétés de l'élément sélectionné | Explorateur |
| `← / →` (Explorateur) | Réduire / Développer un dossier dans l'arborescence | Explorateur |
| `Ctrl + Shift + N` | Créer un nouveau dossier | Explorateur |
| `Alt + ↑` / `Entrée` | Remonter / Descendre d'un niveau de dossier | Explorateur |
| `Alt + ← / →` | Dossier précédent / suivant (Historique) | Explorateur |
| `Shift + Suppr` | Suppression définitive (sans passer par la Corbeille) | Explorateur |

---

##  3. Commandes Exécuter (`Win + R`)

### 🔹 1. Panneau de Configuration (`.cpl`)
- `ncpa.cpl` : Connexions réseau (cartes Wi-Fi, Ethernet, adresses IP).
- `firewall.cpl` : Pare-feu Windows classique.
- `appwiz.cpl` : Ajouter / Supprimer des programmes (Désinstallation).
- `mmsys.cpl` : Réglages du son, haut-parleurs et microphones.
- `powercfg.cpl` : Options d'alimentation et gestion de la mise en veille.
- `sysdm.cpl` : Propriétés système, nom de l'ordinateur, variables d'environnement.
- `main.cpl` : Paramètres et propriétés de la souris.

### 🔹 2. Consoles de Gestion Microsoft (`.msc`)
- `gpedit.msc` : Éditeur de stratégie de groupe locale (GPO local).
- `devmgmt.msc` : Gestionnaire de périphériques et pilotes matériels.
- `diskmgmt.msc` : Gestion des disques, partitions et volumes.
- `lusrmgr.msc` : Gestion des utilisateurs et groupes locaux.
- `eventvwr.msc` : Observateur d'événements (journaux d'erreurs et système).
- `services.msc` : Gestion des services Windows en arrière-plan.
- `compmgmt.msc` : Console de gestion globale de l'ordinateur.
- `wf.msc` : Pare-feu Windows avec fonctions avancées de sécurité.

### 🔹 3. Utilitaires Système & Autres
- `control` : Panneau de configuration classique.
- `regedit` : Éditeur du Registre Windows.
- `mstsc` : Client de connexion bureau à distance (RDP).
- `mmc` : Console de gestion Microsoft vierge pour créer des consoles sur mesure.
- `%temp%` : Dossier des fichiers temporaires (utile pour le nettoyage).
- `cmd` : Invite de commandes classique.
- `cleanmgr` : Outil de nettoyage de disque Windows.
- `mrt` : Outil de suppression des logiciels malveillants Microsoft.
- `msinfo32` : Informations système détaillées (RAM, BIOS, matériel).
- `wsl` : Lancer le sous-système Windows pour Linux.

---

##  4. CLI : Shell Windows, PowerShell & Linux pour TSSR

###  4.1 Réseau & Diagnostic (Indispensables TSSR)
- **`ipconfig /all`** : Affiche la configuration IP complète de toutes les cartes réseau (adresses IPv4/IPv6, masques, passerelle, serveurs DNS, adresse MAC).
- **`ipconfig /flushdns`** : Vide le cache DNS local (très utile en cas de problème de résolution de nom ou de site inaccessible).
- **`ping <IP ou nom>`** : Teste la connectivité réseau et la latence avec une machine distante via le protocole ICMP.
- **`tracert <IP ou nom>`** : Trace le chemin (les routeurs/sauts) pris par les paquets réseau pour atteindre une destination.
- **`nslookup <domaine>`** : Interroge un serveur DNS pour résoudre un nom de domaine en adresse IP (et inversement).
- **`netstat -ano`** : Affiche toutes les connexions réseau actives et les ports d'écoute, ainsi que le PID (ID du processus) associé pour identifier quel programme utilise quel port.
- **`arp -a`** : Affiche la table ARP locale (correspondance entre les adresses IP et les adresses MAC des machines sur le même réseau local).

###  4.2 Gestion des Utilisateurs & Système (Windows / PowerShell)
- **`Get-LocalUser`** : Liste l'ensemble des comptes utilisateurs locaux sur la machine.
- **`Get-NetAdapter`** : Affiche l'état, la vitesse et les détails des cartes réseau (Ethernet, Wi-Fi).
- **`Get-Service`** / **`Restart-Service`** : Permet de lister ou de redémarrer un service Windows directement en PowerShell.
- **`Get-Process`** / **`Stop-Process`** : Permet de lister les processus en cours ou d'en stopper un de force via son nom ou son PID.
- **`sfc /scannow`** : Analyse l'intégrité de tous les fichiers système protégés et répare les fichiers corrompus.
- **`dism /online /cleanup-image /restorehealth`** : Répare l'image du système d'exploitation Windows via Windows Update ou une source externe.

###  4.3 Commandes de Base Linux (Essentielles pour TSSR / WSL)
- **`ip a`** ou **`ifconfig`** : Affiche les interfaces réseau et les adresses IP sous Linux.
- **`systemctl status <service>`** : Vérifie l'état d'un service (démon) sous Linux (ex: `systemctl restart ssh`).
- **`df -h`** : Affiche l'espace disque disponible et utilisé sur les différentes partitions (au format lisible).
- **`free -h`** : Affiche l'utilisation de la mémoire RAM et du swap.
- **`top`** ou **`htop`** : Gestionnaire de tâches en temps réel pour surveiller l'utilisation du processeur et de la mémoire par les processus.
- **`tail -f /var/log/...`** : Permet de suivre en direct les fichiers de journaux (logs) système ou applicatifs.

###  4.4 Gestionnaire de Paquets `winget` (Déploiement logiciel)
- **`winget search <nom>`** : Rechercher un logiciel dans le dépôt officiel.
- **`winget install <nom>`** : Installer un programme silencieusement et directement en ligne de commande.
- **`winget upgrade --all`** : Mettre à jour l'ensemble des applications installées sur le poste.

---

##  5. Microsoft PowerToys (Outils Power User)

Ensemble d'outils officiels Microsoft pour booster la productivité :

- **PowerToys Run (`Alt + Espace`) :** Lanceur rapide et puissant pour chercher des fichiers, lancer des applications ou faire des calculs.
- **FancyZones :** Gestionnaire d'ancrage avancé pour organiser ses fenêtres sur mesure.
- **Text Extractor (`Win + Shift + T`) :** OCR rapide permettant de copier du texte à partir de n'importe quelle image ou vidéo.
- **Always on Top (`Win + Ctrl + T`) :** Épingle une fenêtre active au premier plan.
- **Color Picker (`Win + Shift + C`) :** Pipette pour récupérer instantanément le code couleur (HEX, RGB) de n'importe quel pixel à l'écran.
- **Paste As Plain Text (`Win + Ctrl + Alt + V`) :** Colle du texte brut sans aucune mise en forme.
- **Image Resizer :** Redimensionne rapidement des images depuis le menu contextuel du clic droit.
- **Keyboard Manager :** Permet de réaffecter des touches ou de créer de nouveaux raccourcis système.
- **Awake :** Maintient le PC éveillé à la demande sans modifier le plan d'alimentation Windows.