### b. Template de Pull Request (`PULL_REQUEST_TEMPLATE.md`)

**Action :** Créez le fichier `.github/PULL_REQUEST_TEMPLATE.md`.

```markdown
## Contexte

*(Décrivez le problème résolu ou la fonctionnalité ajoutée. Référencez l'issue correspondante.)*

**Lien vers l'issue :** Fixes # (Ex: Fixes #42)

---

## Solution Proposée

*(Expliquez brièvement comment ce code résout le problème ou implémente la fonctionnalité. Mentionnez les changements majeurs ou les choix techniques importants.)*

---

## Tests Réalisés

*(Décrivez les tests manuels ou automatiques que vous avez effectués pour vous assurer que tout fonctionne correctement.)*

* J'ai lancé les tests unitaires et d'intégration : `npm test`.
* J'ai testé manuellement le scénario suivant : (ex: connexion, ajout d'article au panier, etc.).

---

## Checklist de Vérification

*(Cochez les cases appropriées avant de demander la revue.)*

* [ ] Le code respecte les standards de style du projet (ESLint, Prettier, etc. si utilisés).
* [ ] J'ai mis à jour la documentation (si nécessaire).
* [ ] Les **Tests sont passés** (unitaires, intégration, E2E).
* [ ] Le **Code est relu par un pair** (laisser à un autre développeur).
* [ ] Un lien vers l'issue est présent : **Fixes #**