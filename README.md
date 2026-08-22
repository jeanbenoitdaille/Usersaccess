# Usersaccess

Prototype front-end de formulaire de création de compte utilisant HTML, CSS, JavaScript et jQuery.

## Fonctionnalités

- formulaire avec nom, e-mail, mot de passe, date de naissance et commentaire ;
- champs obligatoires via l’attribut HTML `required` ;
- textes d’aide générés dynamiquement avec jQuery ;
- affichage de l’aide au focus ;
- animations du formulaire et des titres.

## Technologies

- HTML ;
- CSS ;
- JavaScript ;
- jQuery 3.4.1 chargé depuis un CDN.

## Limites historiques

Les règles affichées à l’utilisateur ne sont pas réellement validées par le JavaScript. Par exemple, les contraintes de longueur, format d’e-mail, majorité ou contenu du mot de passe sont uniquement présentées sous forme de texte d’aide.

Le formulaire ne possède pas non plus de traitement serveur : aucune création de compte, authentification ou persistance n’est effectuée.

## Fichiers

- `index.html` : structure du formulaire ;
- `style.css` : mise en forme ;
- `script.js` : interactions jQuery et textes d’aide.

## Exécution

Ouvrir `index.html` dans un navigateur avec accès au CDN jQuery utilisé par la page.

## Statut

Mini-projet d’apprentissage historique.

## Consolidation prévue

Candidat à une future fusion dans `learning-javascript/forms/jquery-user-form/`.
