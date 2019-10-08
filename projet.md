# Evaluation

L'évaluation se déroule en deux étapes :
+ Une évaluation d'une dizaine de minutes sur les connaissances
+ Un projet

Le CM : https://drive.google.com/file/d/16aGFlLrdP7UtyJsVZ2LtNTsUPFHU8aVx/view?usp=sharing

Les TPs :
+ TP1 : https://www.github.com/corentinMar/android-tp1
+ TP2 : https://www.github.com/corentinMar/android-tp2
+ TP3 : https://www.github.com/corentinMar/android-tp3
+ TP4 : https://www.github.com/corentinMar/android-tp4

# Evaluation

A venir

# Projet

Le but du projet est de réutiliser les connaissances acquises durant les 4 TPs.

## Partie 1

⚠️⚠️ CREER VOTRE REPO : https://classroom.github.com/a/2ADODNIt ⚠️⚠️

### Travail à faire
Vous devez créer une application mobile 📱  :
+ qui possède une interface de connexion 
    + identifiant + mot de passe
+ qui possède une interface de création de comptes
    + nom, prénom, âge, email, mot de passe, adresse, ville, pays (liste en dur dans le viewmodel (pas besoin de 200 pays 😉) : https://code.luasoftware.com/tutorials/android/android-two-way-data-binding-with-spinner/), sélection du sexe
        + les champs sont obligatoires et doivent respecter les formats.
+ une base de données pour les utilisateurs

L'utilisateur doit pouvoir accéder à une interface de connexion, s'il n'a pas d'identifiant, il doit pouvoir choisir de s'inscrire.

Pensez aux petits détails (affichage message erreur comme Toast ou Snackbar) si erreur connexion/inscription, à l'ergonomie, au design...

Après connexion, on effectue la partie 2.

### Bonus
+ Sécuriser la sauvegarde du mot de passe en base
+ Utiliser un Picker pour l'âge : https://github.com/material-components/material-components-android/blob/master/docs/components/Picker.md


![meme](https://scontent-mrs2-1.xx.fbcdn.net/v/t1.0-9/71071242_2896011177084493_8482162506649829376_n.jpg?_nc_cat=108&_nc_oc=AQmIiyU1SgReg3YYc9U7MS4nCMM6lowqoV5N-54tRRzea0TGVsY0WYmkejuV2uWjZ9M&_nc_ht=scontent-mrs2-1.xx&oh=e394646f78cd13f1f556175b4c90a269&oe=5E2A08A6)

## Partie 2

Pour réaliser la partie 2, vous trouverez toutes les informations et les codes d'aide dans le TP4.

### Travail à faire
+ En sélectionnant l'API de votre choix, vous devez récupérer des données puis les afficher dans une liste (RecyclerView)
+ Lors du clic sur un élément, cela ouvre une vue détaillée de l'élément

Pensez aux petits détails, à l'ergonomie, au design...

### Bonus
+ Filtrer les résultats / Rafraichissement : https://codelabs.developers.google.com/codelabs/kotlin-android-training-internet-filtering/index.html?index=..%2F..android-kotlin-fundamentals#0

### Exemples d'API
+ Bières : https://data.opendatasoft.com/explore/dataset/open-beer-database%40public-us/table/?flg=fr
+ Séries
+ Autres: https://data.opendatasoft.com/explore/?disjunctive.language&disjunctive.source_domain_title&disjunctive.theme&disjunctive.semantic.classes&disjunctive.semantic.properties&sort=explore.popularity_score
