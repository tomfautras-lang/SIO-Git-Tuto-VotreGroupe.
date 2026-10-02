
p {
  display: block; /* Le paragraphe commence sur une nouvelle ligne
                     et occupe généralement toute la largeur disponible. */
}

a {
  display: inline; /* Le lien reste dans la ligne avec le texte. */
}

a {
  display: inline-block; /* Le lien reste dans la ligne, mais on peut
                            notamment lui appliquer une largeur et une hauteur. */

}

Élément en bloc (block) : il occupe généralement toute la largeur disponible et commence sur une nouvelle ligne.


Exemples : <p>, <div>, <h1>.

Élément en ligne (inline) : il reste dans le flux du texte et n'effectue pas automatiquement de retour à la ligne.

Exemples : <a>, <span>, <strong>.


display : propriété CSS permettant notamment de modifier le mode d'affichage d'un élément.
display: block;
display: inline;
display: inline-block;
<p> est un élément block : il occupe généralement toute la largeur disponible et commence sur une nouvelle ligne.
<a> est un élément inline : il reste dans le flux du texte et n'occupe que la largeur de son contenu.
