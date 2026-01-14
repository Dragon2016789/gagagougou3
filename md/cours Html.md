1. HTML

hyperText Markup Language *langage de balises hypertext*

un fichier `html` est un fichier de texte (comme le markdown). On ouvre un fichier de 2 façon :
- le developpeur => avec un editeur de code (ex Visualsudio.Code)
-   l'utilisateur => avec un navigateur (ex : firefox)

Le plus souvent les balises html sont en couple(ouvrante/fermante) mais il existe aussi des balises *orpheline*:
- `<MaBalise></MaBalise>`
- `<Mabalise>`

La structure minimale d'une page web est:

```html
<!DOCTYPE html>
<html>
<head></head>
<html></head>
<body></body>
</html>
```

Le site des référence pour els language du WEB est le site des dévlopper de Modzzila.
https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements

quelques balises a connaitre :
-`<body></body>` contient tout se qui est visible sur la page
-`<body></head>` contient se qui n'est pas visible sur les page (ex : `<title></title>`)
-`<h1></h1>` permet de faire des titre sur la page
-`<p></p>` permet de faire un paragraphe
-`<a href=""></a>` permet d'accrocher le curseur pour ouvrir un lien
-`<br>` pour casser la ligne
-`<img src="">` pour insérer une image
-`<ul></ul>` pour réaliser une liste sans ordre
-`<ol></ol>` pour réaliser une liste ordonné
-`<li></li>` pour insérer des items dans une liste

Les balises ouvrantes peuvetn contenir des attribut défini sur le site de référence ou l'attribut `classe""`;<br>
<Mabalise attribut=""></Mabalise>

----------------------------------
Pour donner le chemin vers un fichier, on utilise :
-`./` pour chercher dans le dossier courant
-`../` pour chercher dans le dossier du dessus


2. Le CSS
cascating Style Sheet "feuille de style en cascade"
Pour définir le style, il faut un sélecteur (élements Html ou classe), des acolades, uine propriétés, une valeur.

```CSS
selecteur{
    propriété valeur:
}
```
On peut écrire le CSS:
-dans le fichier Html entre les balises `<style></style>`
-dans le fichier avec l'extension css : il faut ajouter une balise '<link rel='
il existe plus de 500 propriété et encore d'avantage de valeurs possible mais souvent, les valeurs sont:
des couleurs, des noms et des code come rgb...
Des tailles, (plusieurs unités sont possibles)
  'px' pour pixels
  'em' relatif a la taille de la police
  '%' relatif a la taille du contenant


remarque quand le sélecteur CSS est un élément html (par exemple 'p') alors les propriétés s'applique a tout les éléments du même type 

Pour différencier des élements de même nature on peut utiliser l'attribut 'classe' ou 'id' . Dans se cas le selecteur est le nom d'une classe précédé par '.' ou le nom de l'identifiant précédé d'un '#'

Rem: le contenu d'un élément HTML suit le principe du modèle en boite .
[](https://www.w3schools.com/Css/css_boxmodel.asp)

Trois propriétés importantes sont liées a se modèle:
- 'border' pour le style de bordure
- 'padding' pou l'espace interne
- 'margin' pour la marge autour de la bordure

Rem: il existe des propriétés specifiques au texte, en particulier:
- 'text-align' pour justifier le texte.
- 'font' pour la police de caractères


Ils existe deux balises HTML universelles qui permet de grouper des éléments ou du texte 
-'<div></div>