
| UE | Ref. | Format | Seance | Date | Heure |
|:---:|:---:|:---:|:---:|:---:|:---:|
| EMEAT2BM | OCSP | CM | 1 | 2022/01/18 | 10:05 - 12:05 |

## Vocabulaires
- **Processus/Tâches** : ensemble d'activités séquentielles
- **Activité** : déterminées par un **évènement caractérisé** et par sa **date d'occurence**
- **Évènement (a)synchrone** : date d'arrivée (in)connue
- **..**


## Notions Importantes

- **Pseudo Parallélisme** (_temps partagé_) :
    - Plusieurs **processus indépendants** géré par un processeur communs

- **Compétition** (_ressources partagées_) :
    - Plusieurs **processus interdépendant** partage une même mémoire/ressource
    - Implique une gestion de **zone critique** pour garantir une **exclusion mutuelle**
    ![](/assets/images/OCSP.CM.Seance1.Competition.png)

- **Synchronisation** (_séquencement interdépendant_) :
    - Plusieurs **processus interdépendants** où le séquencement d'un processus dépend de l'état d'un autre processus (pas nécessaire mutuel -> **synchronisation unilatérale**)
    ![](/assets/images/OCSP.CM.Seance1.RdP-Synchronisation.png)

- **Attente active** (à éviter) :

## Remarques
- Les évènenments sont discret et instantanés (**sans durée**) !
- La compétition (avec sa gestion de zone critique) peut être vu comme une synchronisation (?)
- Une zone critique peut être vu comme une ressource partagée.

## Structure

- Notion de Processus
- ...

## Bibliothèques

- [OCSP.CM.Seance1.ProcessusSemaphores.NotesRKA.2022.01.18.pdf](https://www.dropbox.com/home/UT3.RODECO.2021.2022.S8.Shared/EMEAT2B1..OCSP-OutilsConceptionSystemesParalleles/OCSP.Cours?preview=OCSP.CM.Seance1.ProcessusSemaphores.NotesRKA.2022.01.18.pdf)
