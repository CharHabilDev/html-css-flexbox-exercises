# Exercice 11. Différence entre `align-items` et `align-content`

## Objectif

Créer un conteneur Flexbox avec suffisamment de blocs pour forcer un retour à la ligne, afin d’observer la différence entre `align-items` et `align-content`.

## But

Comprendre que :
- `align-items` aligne les éléments à l’intérieur de chaque ligne
- `align-content` aligne l’ensemble des lignes dans le conteneur

## Compétences travaillées
- `display: flex`
- `flex-wrap`
- `align-items`
- `align-content`

## Structure HTML

```html
<div class="container">
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

- le conteneur doit utiliser Flexbox
- les blocs doivent aller à la ligne avec `flex-wrap: wrap`
- le conteneur doit avoir une hauteur suffisante pour rendre l’alignement visible
- faire un premier test avec `align-items`
- faire un second test avec `align-content`

## Notes

- `align-items` agit sur les éléments dans chaque ligne
- `align-content` agit sur l’ensemble des lignes
- `align-content` ne fonctionne visiblement que s’il y a plusieurs lignes et de l’espace disponible sur l’axe secondaire