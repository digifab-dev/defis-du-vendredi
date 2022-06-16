# Ceci est le depot pour les défis de kévin le vendredi.

## Comment l'utiliser:

### Ouvrez votre terminal

- Créez une branche à votre nom:

  ```
  git branch VotreNom
  ```

- Positionnez-vous sur cette branche:

  ```
  git checkout VotreNom
  ```

- Mettez votre branche à jour:

  ```
  git pull
  ```

- Envoyez vos modifications avec un commit:

  ```
  git add fichierModifié
  git commit -m message du commit
  git push --set-upstream origin VotreNom
  ```

## Une fois le défis terminé:

### Allez sur la page du dépot github

- Sur la page du dépot de github, cliquez sur `Compare & pull request`
  ![](https://imgur.com/ydYMRaJ.jpg)

- Ajoutez un commentaire dans la zone de texte et cliquez sur `Create pull request`
  ![](https://imgur.com/hf5hxYh.jpg)

- Cliquez sur le bouton `Merge pull request`
  ![](https://imgur.com/N4Fh8hw.jpg)

- Puis sur `Confirm merge`
  ![](https://imgur.com/5uWTlJH.jpg)

- Puis encore sur `Delete branch`
  ![](https://imgur.com/coAKfFT.jpg)

## Maintenant que les fichiers sont envoyé sur le dépot github, il faut mettre à jour le dépot local et supprimer la branche.

### Retour sur le terminal

- positionnez-vous sur la branche main:

```
git checkout main
```

- supprimmez la branche à votre nom:

```
git branch -d VotreNom
```
