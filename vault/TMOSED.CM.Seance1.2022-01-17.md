---
id: XM2Gh3jx0pW5r7tHuFAT2
title: TMOSED CM Seance 1 du 2022/01/17
desc: ''
updated: 1642940875013
created: 1642589144556
---

| UE | Ref. | Format | Seance | Date | Heure |
|:---:|:---:|:---:|:---:|:---:|:---:|
| EMEAT2A1 | TMOSED | CM | 1 | 2022/01/17 | 07:45-09:45 |

## Vocabulaires

- **Application** : Technique de modélisation pour l'obtention d'un modèle définie par le cahier des charges (CdC)

- **Vérification** : Conformité par rapport au CdC sans **TRAHISION**
    - Proverbe italien : traduction = trahision

- **Retour sur modèle** : adjustement de la représentation pour respecter CdC

- **Mise en oeuvre** : réalité pratique (ex. commande)

## Notions Importantes

- **Mise sous forme algébrique** :
    - "Décrire le modèle par un ensemble d'équation"
    - Situations représentées par un codage binaire noté Ei
    - **Modèle FMG** :
    ![](/assets/images/TMOSED.CM.Seance1.ModeleFMG-1.png)
    ![](/assets/images/TMOSED.CM.Seance1.ModeleFNG-2.png)
    
- **Bascule synchrone** :
    - Table de vérité
    ![](/assets/images/TMOSED.CM.Seance1.BasculeSynchrone-TableVerite.png)
    - Exemple
    ![](/assets/images/TMOSED.CM.Seance1.BasculeSynchrone-Exemple.png)

- **Bascule D**
    - Table de vérité
    ![](/assets/images/TMOSED.CM.Seance1.BasculeD-TableVerite.png)
    - Exemple
    ![](/assets/images/TMOSED.CM.Seance1.BasculeD-Exemple.png)

- **Sorties**
![](/assets/images/TMOSED.CM.Seance1.Sorties.png)

## Remarques

- Modèle obtenu du SED est **fini** (malgré que toutes les situations possibles soient considéré) du coup sa mise en oeuvre est envisageable !

- Même les **pannes rares** doivent être considérées dans le modèle !

- Précautions
    - Init: Ej tous à faux sauf l'**état de départ**
    - Sync: La transmission des résultats n'est faite qu'une fois les équations stabilisées et de façon **simultanée**
    - Conditions d'évolutions: constructeur est le seul garant de l'exclusion des conditions (**indéterminisme interdit**)

## Structure

- Chap 0 - Intro
- Chap 1 - Mise sous forme algébrique d'un SED
    - 1-1. Automate à états finis : **codage 1 parmi N**
        - 1-1.a) Contexte
        - 1-1.b) Bascule synchrone
        - 1-1.c) Bascule D
        - 1-1.d) Les Sorties
        - 1-1.e) Precautions

## Bibliothèques

- [TMOSED.Modalites.NotesRKA.2022.01.17.pdf](https://www.dropbox.com/s/b5u7uekl9kyv4du/TMOSED.Modalites.NotesRKA.2022.01.17.pdf?dl=0)
- [TMOSED.CM.Seance1.Chap0.Intro.NotesRKA.2022.01.17.pdf](https://www.dropbox.com/preview/UT3.RODECO.2021.2022.S8.Shared/EMEAT2A1..TMOSED-TechniquesMiseOeuvreSystemesEvenementsDiscrets/TMOSED.CM/TMOSED.CM.Seance1.Chap0.Intro.NotesRKA.2022.01.17.pdf?context=browse&role=personal)
- [TMOSED.CM.Seance1.Chap1.MiseSousFormeAlg.NotesRKA.2022.01.17.pdf](https://www.dropbox.com/preview/UT3.RODECO.2021.2022.S8.Shared/EMEAT2A1..TMOSED-TechniquesMiseOeuvreSystemesEvenementsDiscrets/TMOSED.CM/TMOSED.CM.Seance1.Chap1.MiseSousFormeAlg.NotesRKA.2022.01.17.pdf?context=browse&role=personal)
