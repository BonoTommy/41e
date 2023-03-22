# Historique des commandes du Tp1

### Création d'un dépôt
- Initialise un dépôt vide, cette commande est exécuté une seule fois
- Si exécuté une seconde fois, on détruit le dépôt
- `git init`

---

### Vérifier le statut
- `git status`

---

### Afficher l'historique des commits

- `git log`
- `git log --oneline`

---

### Naviguer dans les branches

- Pour changer le nom d'une branche
  - `git branch -m «nom nouvelle branche»`
  - `git branch -m main` // change le nom de la branche courante pour main

- Pour créer une nouvelle branche
  - `git branch «nom nouvelle branche»`

- Pour changer de branche
  - `git checkout «nom branche»`
  - On ne peut pas changer de branche si la branche courante n'a pas été «commit»(valider)
  - `git checkout « id du commit »`
  - `git checkout « étiquette(label) du commit »`

---

### Étapes pour add, commit, et push

  #### Add
  - `git add -all` ou `git add .`

  #### Commit
    - `git add -all` ou `git add .`


---

### Pour créer une étiquette
  - `git tag v1.0.0` // Création de l'étiquette v1.0.0
  - `git tag` // Permet d'afficher l'ensemble des tags(étiquettes)
  - `git checkout v1.0.0` // Pour se déplacer dans le commit v1.0.0 (déplace le pointeur «head»)



- git checkout exemple:e8217af
- pour revenir: git checkout main

-alias:
>git remote add 41e https://github.com/BonoTommy/41e.git

-verification:
>git remote -v

- voir branche:
>git branch

- changement de branche:
  >git checkout tb_entete

