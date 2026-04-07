# Exercice 10. Galerie responsive

## Objectif

Créer une galerie responsive contenant 8 blocs.

## Compétences travaillées
- `display: flex`
- `flex-wrap`
- `gap`
- `flex`

## Structure HTML

```html
<div class="galerie">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
    <div class="item">5</div>
    <div class="item">6</div>
    <div class="item">7</div>
    <div class="item">8</div>
</div>
```

## Contraintes

- les blocs doivent aller à la ligne si l’écran devient trop petit
- l’espacement entre les blocs doit rester propre et régulier
- la largeur des blocs doit être flexible
- utiliser Flexbox pour organiser la galerie

## Remarque

La propriété `flex` est une version raccourcie de :
- `flex-grow`
- `flex-shrink`
- `flex-basis`