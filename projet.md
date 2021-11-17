# Evaluation

L'évaluation se déroule en deux étapes :
+ Une évaluation d'une vingtaine de minutes sur les connaissances
+ Un projet

Le CM : https://drive.google.com/file/d/1bJVJE60O_7VqiIcZ-gpQ6Qpt70c1dAqb/view?usp=sharing

Les TPs :
+ TP1 : https://www.github.com/corentinMar/android-tp1
+ TP2 : https://www.github.com/corentinMar/android-tp2
+ TP3 : https://www.github.com/corentinMar/android-tp3
+ TP4 : https://www.github.com/corentinMar/android-tp4

# Evaluation / Quiz

Le 26 novembre pour durant le dernier créneau

![meme](http://giphygifs.s3.amazonaws.com/media/3XG5igjvWe2wE/giphy.gif)

# Projet

## DEADLINE : 26 janvier 2022 - Cours de Système embarqué

Le but du projet est de réutiliser les connaissances acquises durant les 4 TPs.

## Partie 1

+ ⚠️⚠️ CREER VOTRE REPO : https://classroom.github.com/a/N00K57UK ⚠️⚠️
+ ⚠️⚠️ Renseignez vos noms (par deux) dans le NOM DU GROUPE et le READ ME ⚠️⚠️
+ ⚠️⚠️ PARTAGEZ-vous bien les tâches (pour ne pas avoir juste une personne qui a tout fait) ⚠️⚠️

### Travail à faire
Vous devez créer une application mobile 📱 :
+ qui possède une interface de connexion 
    + identifiant + mot de passe
+ qui possède une interface de création de comptes (adaptez ceci par rapport à votre serveur existant)
    + nom, prénom, âge, email, mot de passe, adresse, ville, sélection du sexe, pays (liste en dur dans le viewmodel (pas besoin de 200 pays 😉) : https://code.luasoftware.com/tutorials/android/android-two-way-data-binding-with-spinner/)
        + les champs sont obligatoires et doivent respecter les formats.

⚠️⚠️ Dans un premier temps et pour vous avancer, effectuez la connexion/inscription en local via une BDD avec une table utilisateur ⚠️⚠️
Bonus : La connexion/inscription s'effectue en relation avec votre API (pas de BDD).

L'utilisateur doit pouvoir accéder à une interface de connexion, s'il n'a pas d'identifiant, il doit pouvoir choisir de s'inscrire.

Pensez aux petits détails (affichage message erreur comme Toast ou Snackbar) si erreur connexion/inscription, à l'ergonomie, au design...

⚠️ NOTEZ que dans le TP4, un interlude vous explique comment changer le composant date (pour éviter les bugs sur certains smartphones)

Après connexion, on effectue la partie 2.

### Bonus
+ Utiliser un Picker pour l'âge : https://github.com/material-components/material-components-android/blob/master/docs/components/Picker.md

![meme](https://media4.giphy.com/media/L3bj6t3opdeNddYCyl/giphy.gif?cid=ecf05e470aboq2o93j5i9dye18dfv8y1domy7wjvcjydxltn&rid=giphy.gif)

## Partie 2

Pour réaliser la partie 2, vous trouverez toutes les informations et les codes d'aide dans le TP4.

### Travail à faire
+ Lorsque l'utilisateur est connecté, vous devez créer une interface pour intéragir avec votre API et vos objets connectés (nécessaire pour votre cours de système embarqué).
+ Lorsque que vous récupérez une donnée, vous devez la sauvegarder dans votre base de donnée locale.
    + Vous devez donc créer une vue liste (RecyclerView) historique qui récapitule l'ensemble des données récupérées en locale et les afficher dedans.
        + Lors du clic sur un élément, cela ouvre une vue détaillée de l'élément
        + Ceci est adaptable en fonction du type d'objet utilisé

TP4 avec le tuto Retrofit : https://www.github.com/corentinMar/android-tp4
Retrofit doc & tuto => https://square.github.io/retrofit/
Retrofit tuto => https://www.c-sharpcorner.com/article/how-to-use-retrofit-2-with-android-using-kotlin/

Pensez aux petits détails, à l'ergonomie, au design...

### Bonus
+ Filtrer les résultats / Rafraichissement : https://codelabs.developers.google.com/codelabs/kotlin-android-training-internet-filtering/index.html?index=..%2F..android-kotlin-fundamentals#0

### En attendant votre API
Si vous n'avez pas votre API de disponible, vous pouvez en attendant juste afficher la liste de vos données, voir celle du TP4
+ Bières : https://data.opendatasoft.com/explore/dataset/open-beer-database%40public-us/table/?flg=fr
+ Evenements publics : https://data.opendatasoft.com/explore/dataset/evenements-publics-cibul%40public/table/?disjunctive.tags&disjunctive.placename&disjunctive.city
+ Fromages : https://data.opendatasoft.com/explore/dataset/fromagescsv-fromagescsv%40public/table/?disjunctive.fromage
+ Autres: https://data.opendatasoft.com/explore/?disjunctive.language&disjunctive.source_domain_title&disjunctive.theme&disjunctive.semantic.classes&disjunctive.semantic.properties&sort=explore.popularity_score


## Résultats
⚠️ **EN RESULTAT, je vous demanderai une vidéo de votre projet qui comprend la connexion de l'utilisateur et l'accès à l'API puis l'intéraction avec votre objet connecté (montrez bien tout ce que vous avez fait)**

Egalement, je regarderai votre code et lancerai votre projet (sans API) de mon côté. Il faut alors penser à gérer la possibilité que votre API ne réponde pas (c'est à dire que l'application ne doit pas planter une fois la connexion utilisateur effectuer -> gestion d'exception).
