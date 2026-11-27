# Journal des échanges et suivi des projets

Ce document sert de mémoire collective pour nos points réguliers, nos décisions, nos spécifications et nos retours de tests.

---

## Mode d'emploi & Convention d'écriture

### 1. Règle d'or : on écrit toujours tout en haut !
Pour éviter de devoir faire défiler toute la page pour lire les dernières nouvelles, **chaque nouvelle intervention s'ajoute tout en haut de la section « Historique des échanges »** (juste sous la ligne de séparation `---`).

### 2. Comment ajouter une entrée sur GitHub (en 4 clics)
1. Cliquez sur l'icône **crayon** (*Edit this file*) en haut à droite de cette page.
2. Placez votre curseur **juste sous la ligne `---` de la section « Historique des échanges »** et créez quelques lignes vides.
3. Copiez-collez le bloc modèle ci-dessous et remplissez-le :

## AAAA-MM-JJ - Votre Prénom (Sujet ou Nom de l'appli)
* **Type :** Point d'avancement / Retour de test / Décision / Idée
* **Résumé :** Décrivez ici votre message, remarque ou résultat de test...
* **Suite à donner :** Action attendue ou question ouverte (facultatif)
    
---

## 2006-11-27 - PP
* **Type :** Décisions personnelles
* **Résumé :** Propositions par priorité
* **1. Développer un prototype pour visualiser les rapports SOFIA Briefing :**
* Ajout des fonctionnalités :
  - Chargement de plusieurs rapport SOFIA Briefing
  - Utiliser la dernière version de PXA Openair pour visualiser les contours réels des SUPAIP actifs
  - Principe : Utilisateur ne charge rien d'autre que les SOFIA Briefing (=> on inclut dans le code les aérodromes, les SUPAIP Openair de PXA)
  - Reflechir à ce que l'utilisateur souhaite conserver (uniquement le supaip ou avec des commentaires en plus)
  - Distribution sous contrôle pour ce prototype
* **Suivi :**
* [ ] **Zey** vérifie le point de countournement dans SOFIA Briefing : utiliser ou pas par l'algorithme de SOFIA Briefing / PP pense que non
* [ ] **Zey-Adel** Envoyer un SOFIA Briefing avec SUPAIP Trigger Notam quand vous en voyez un
* * **2. Mise en place d'un outil collaboratif pour la gestion des SUPAIP :**
* Etape 1 : Prototype pour vérifier le processus collaboratif
* - Utilisation de GitHub pour le travail collaboratif
  - Mise en Place de la solution minimaliste équivalente au suivi Excel
  - Enregistrement d'un fichier TXT Openair par SUPAIP (comme vous le faites actuellement)
  - Production du fichier Openair PXA
* Etape 2 : Prototype incluant
- optimisation de la détection et la revue 'mensuelle, hebdomadaire'
- optimisation de la création et la qualité du fichier au format Openair de chaque SUPAIP
- possibilité d'ajout de fichier openair adhoc avec un écran de saisie
- mise en place d'un standard pour le contenu du fichier Openair
- définir le processus de publication et de distribution  
* **Suivi :**
* [ ] **Zey-Adel** Penser à la norme du fichier Opentext ainsi ainsi que les critères de certification qualité (polygone fermé par exemple)

* **3. Tempête de cerveau sur processus global de fourniture du fichier Openair 'Espaces Aériens' :**
  * Un "One Pager" pour faciliter la communication
  * Des idées de vulgarisation sur le thème de la gestion de données qui est au coeur de ce processus
    
* **4. Mockup sur une application permettant d'alimenter à l'utilisateur de 'signer' son vol**

> [!WARNING]
> Définition de Prototype : une solution utilisable dans la vie réelle , développement rapide. Pas de regret si cela ne fonctionne pas. Nécessite souvent une réécriture pour passer au stade industriel

