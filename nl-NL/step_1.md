Voeg een nieuw `<div>`-element toe met een klasse-kenmerk van `hero-image`.

## --- code ---

language: html
filename: index.html
----------------------------------------------------

<header>
    <div class="hero-image"></div>
</header>

\--- /code ---

Voeg in `style.css` een nieuwe selector toe voor de `hero-image` klasse.

In plaats van een `<img>` element toe te voegen aan de HTML, kun je ook de CSS `background-image` eigenschap gebruiken om je afbeelding toe te voegen.

Stel de hoogte van je `<div>` in zodat voldoende ruimte is voor de afbeelding.

De afbeelding moet het element `<div>` vullen (door de eigenschap `background-size` in te stellen op `cover`) en gecentreerd zijn.

## --- code ---

language: css
filename: style.css
---------------------------------------------------

/\* Hero image - startpagina \*/
.hero-image {
min-height: 50vh;
background-image: url('antarctic-northern-lights.jpg');
background-size: cover;
background-position: center;
}

\--- /code ---
