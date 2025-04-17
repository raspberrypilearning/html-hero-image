Ajoute un nouvel élément `<div>` avec un attribut de classe `hero-image`.

## --- code ---

language: html
filename: index.html
----------------------------------------------------

<header>
    <div class="hero-image"></div>
</header>

\--- /code ---

Dans `style.css`, ajoute un nouveau sélecteur pour la classe `hero-image`.

Au lieu d'ajouter un élément `<img>` au code HTML, tu peux utiliser la propriété CSS `background-image` pour ajouter ton image.

Définis la hauteur de ton `<div>` afin que l'image ait de l'espace à remplir.

L'image doit remplir l'élément `<div>` (en définissant la propriété `background-size` à `cover`) et être centrée.

## --- code ---

language: css
filename: style.css
---------------------------------------------------

/\* Image Hero - page d'accueil \*/
.hero-image {
min-height: 50vh;
background-image: url('antarctic-northern-lights.jpg');
background-size: cover;
background-position: center;
}

\--- /code ---
