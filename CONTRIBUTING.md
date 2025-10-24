Ajout de `CONTRIBUTING.md` (Charte de collaboration)

Ce fichier définit les règles pour toute personne souhaitant contribuer au code.

**Action :** Créez un fichier nommé `CONTRIBUTING.md` à la racine de votre dépôt et insérez le contenu suivant :

```markdown
# Charte de Contribution à Liverooo!

Nous apprécions toute contribution ! Pour garantir un processus de développement fluide et cohérent, veuillez suivre ces lignes directrices.

## 1. Gestion des Branches

* **`main` :** La branche principale est **protégée**. Elle contient la dernière version stable et déployable. Les commits directs sur `main` sont interdits.
* **Branches de travail :** Toutes les modifications doivent être effectuées dans une nouvelle branche, nommée selon le format : `<type>/<description-courte-de-la-tache>`.
    * Exemples :
        * `feat/ajout-page-restaurants`
        * `fix/bug-login-mobile`
        * `docs/maj-readme`

## 2. Conventions de Commit

Nous utilisons la convention **Conventional Commits**. Chaque message de commit doit commencer par un **type** suivi de deux-points.

| Type | Description | Exemple |
| :--- | :--- | :--- |
| **feat:** | Ajout d'une nouvelle fonctionnalité. | `feat: ajouter la possibilité de payer la commande` |
| **fix:** | Correction d'un bug. | `fix: corriger l'affichage des prix négatifs` |
| **docs:** | Changements dans la documentation uniquement. | `docs: mise à jour de la section Lancer le Projet` |
| **style:** | Formatage (points-virgules, espaces, etc.). | `style: corriger l'indentation dans le fichier user.js` |
| **refactor:** | Changement de code qui ne corrige pas de bug et n'ajoute pas de fonctionnalité. | `refactor: simplifier la fonction de calcul de budget` |
| **test:** | Ajout ou correction de tests. | `test: ajouter un test unitaire pour la connexion` |
| **chore:** | Mises à jour des tâches de construction ou des dépendances. | `chore: mettre à jour la dépendance axios` |

## 3. Workflow de Pull/Merge Request (PR/MR)

1.  **Créer une branche :** Basée sur la dernière version de `main`.
2.  **Commits :** Effectuez vos modifications en respectant les conventions ci-dessus.
3.  **Push :** Poussez votre branche sur le dépôt distant.
4.  **Ouvrir une PR/MR :** Ciblez la branche `main`. Remplissez le template de PR/MR.
5.  **Revue de Code :** Obtenez au moins un approbateur. Consultez la [Checklist de Revue de Code](docs/code-review-checklist.md).
6.  **Merge :** Une fois approuvée, la PR peut être fusionnée.

## 4. Rappel sur la Qualité

Les contributions doivent respecter les définitions de *Definition of Ready (DoR)* et *Definition of Done (DoD)* définies lors de l'Atelier A (à insérer ici ou y faire référence).
* **DoR (Ready) :** (Ex: User story comprise, AC clairs, estimation faite).
* **DoD (Done) :** (Ex: Code revu, tests passés, documentation mise à jour, déployé en staging).