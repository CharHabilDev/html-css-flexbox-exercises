# Exercice 6. Carte profil

## Objectif

Créer une carte profil contenant :
- une image à gauche
- un bloc de texte à droite

Puis adapter la mise en page pour mobile afin que l’image passe au-dessus du texte.

## Compétences travaillées
- `display: flex`
- `flex-direction`
- `align-items`
- `media query`

## Structure HTML
````html
<div class="card">
  <img src="assets/image.jpg" alt="Photo de profil">
  <div class="content">
    <h2>Nom Prénom</h2>
    <p>Petite description du profil.</p>
  </div>
</div>
````

## Contraintes
- sur écran large, l'image doit être affichée à gauche et le texte à droite
- sur écran mobile, l'image doit passer au-dessus du texte
- utiliser Flexbox pour la mise en page
- changer la direction avec une media query