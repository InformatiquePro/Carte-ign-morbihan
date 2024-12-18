**Bonjour !**
*Sorry for the English, I speak French*

Voila des scriptes qui permettent de télécharger les cartes IGN du Morbihan (56) et de Paris (75).
*Note : Le scripte de pour Ubuntu/Debian n'est plus **maintenut**, il ne recevra plus les nouveautés et je ne vous recommande pas de l'utiliser.*

## Avertissement !!!

**
Ce script utilise QGIS, un logiciel open-source de donner cartographique, p7zip-full (p7zip pour le srcipt compatible Arch Linux) un équivalent de 7zip pour linux open-source pour décompresser les fichiers 7z. La carte est récupérer sur les serveurs IGN-FRANCE. Cela implique donc dès l'utilisation de ces cartes l'acceptation immédiate de toutes les conditions d'utilisation de IGN-FRANCE. Pour plus d’information, consulter : https://geoservices.ign.fr/cgu-licences .
De plus, même si cela fonctionne aussi avec Windows, ce script fonctionne **UNIQUEMENT** sur les distributions Linux basé sur **Debian/Ubuntu** *et* **Arch Linux**. Ce script peut être adapté à d'autre distribution linux, voir même sur Windows, mais actuellement il ne le fait pas.

*Note 1 : le script pour Arch Linux détecte si vous êtes sur arch linux (ou dérivée) en vérifiant la présence de ce fichier : `/etc/arch-release` et si votre distribution basée sur Arch Linux à retirer ce fichier, le scripte lancera la version debian/ubuntu. Noter que ce scripte est encore perfectible.**


## Département compatible : 

| Département        |Numéro du département | Taille | Suporté ?  |
| ------------------ | -------------------- | -----  | ---------- |
| Morbihan           | 56                   | 3.2Go  | ✅         |
| Paris              | 75                   | 1.5Go  | ✅         |
| Ain                | 01                   | 2.5GB  | ✅         |

*Les autres départements deviendront compatible à un moment donné*

## Pour l'utiliser, c'est simple :

*Note : ce script est en développement, je l'ai uniquement testé sur Manjaro Linux et Ubuntu, donc il est possible de rencontrer des erreurs. Un minimum de connaissance en Linux de manière générale est très fortement recommander avant de lancer le scripte. InformatiquePro n'est en aucun cas responsable de tous problème futur causé par mon scripte.*

**
Lancer dans votre terminal, après avoir récupéré le fichier correspondant à votre distribution Linux, et être positionner dans le dossier ou il est télécharger : `chmod +X le-nom-du-script-choisi.sh` puis `./le-nom-du-script_choisi.sh`
**ET voila !!**
