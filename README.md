## VueJS

**ATTENTION : pour ce tp nous n'utilisons pas la norme SFC (https://vuejs.org/guide/scaling-up/sfc.html), nous n'aurons donc pas de fichier .vue**

- VueJS
  - https://vuejs.org/
- Affichage de variable dans le code HTML
  - https://vuejs.org/guide/essentials/template-syntax.html#text-interpolation
- Affichage itératif
  - https://vuejs.org/guide/essentials/list.html#v-for
- Binding classe/style
  - https://vuejs.org/guide/essentials/class-and-style.html#binding-html-classes
- Events
  - https://vuejs.org/guide/essentials/event-handling.html
  - https://vuejs.org/guide/components/events.html
- Modèle
  - https://vuejs.org/guide/components/v-model.html
- Composant
  - https://vuejs.org/guide/components/registration.html#global-registration
- Cycle de vie
  - https://vuejs.org/api/options-lifecycle.html
- Composant : les props
  - https://vuejs.org/guide/components/props.html

## Sujet du TP

1) Intégrer VueJS (via CDN) au sein de votre page index.html
2) Mettre en place une balise H1 qui sera alimentée par une variable VueJS
3) Initialiser la balise TITLE à la création de l'application
4) Créer un composant form-add-article composer d'un champ *title*, d'un champ *description* et d'un bouton *Submit* et l'afficher sur la page
5) A la validation du formulaire, il faut récupérer le contenu des champs et créer un objet json composé d'un attribut *title* et d'un attribut *description* et le log
6) Afficher un message d'erreur si l'un des 2 champs n'est pas correct
7) Une fois la news créée, la faire remonter au composant parent via un l'event add-news qui ajoutera la news dans un tableau allNews accessible par la vue
8) Afficher le contenu présent dans la variable allNews
9) Créer un composant article, qui affichera un titre et une description qui seront reçu depuis les props.
10) Utiliser ce composant depuis le fichier `index.html`. Les éléments affichés par le composant seront passés par la vue.
11) Rajouter un évènement au clic sur le titre d'un article qui inversera la valeur de l'attribut `isRead`.
12) Si un article a son attribut `isRead` à true alors il faut afficher la mention *(lu)* à droite du titre de l'article.

## Ressources

- Lien des slides : https://drive.google.com/drive/folders/1tFK4F2RrTWAvqqEG-RpGvnTMCGohaNcz?usp=share_link
- Lien vers la documentation : https://developer.mozilla.org/fr/docs/Web/JavaScript