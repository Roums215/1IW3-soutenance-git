# Guide pour contribuer

Merci de contribuer à ce projet ! Voici les règles principales :

1. Avant de travailler sur un issue, **vérifiez qu’elle existe sur GitHub**.  
2. Créez une **branche spécifique** :  
   `git checkout -b feature/issue-xx`  
3. Faites vos modifications, **committez avec un message clair et lié à l’issue** :  
   `git commit -m "docs: amélioration de la doc (#xx)"`  
4. Poussez votre branche :  
   `git push -u origin feature/issue-xx`  
5. Ouvrez une Pull Request et ajoutez `Closes #xx` dans la description pour fermer automatiquement l’issue.

### Bonnes pratiques

- Travaillez toujours sur **des branches séparées**  
- Relisez vos modifications avant de créer la PR  
- Respectez le format des commits : `type: description (#issue)`  
- Assurez-vous que le **workflow GitHub Actions** passe avant le merge