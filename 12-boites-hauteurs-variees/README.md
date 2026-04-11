# Exercice 12. Tableau de boîtes avec hauteurs variées

## Objectif

Créer plusieurs blocs de hauteurs différentes dans un conteneur Flexbox avec retour à la ligne, afin d’observer visuellement l’effet de différentes valeurs de `align-items`.

## But

Comprendre comment l’alignement vertical change selon la valeur appliquée à `align-items`.

## Compétences travaillées
- `display: flex`
- `flex-wrap`
- `align-items`

## Structure HTML

```html
<section>
    <h2>align-items: stretch</h2>
    <div class="container stretch">
        <div class="item petit">1</div>
        <div class="item grand">2</div>
        <div class="item moyen">3</div>
        <div class="item petit">4</div>
        <div class="item grand">5</div>
        <div class="item moyen">6</div>
    </div>
</section>

<section>
    <h2>align-items: center</h2>
    <div class="container center">
        <div class="item petit">1</div>
        <div class="item grand">2</div>
        <div class="item moyen">3</div>
        <div class="item petit">4</div>
        <div class="item grand">5</div>
        <div class="item moyen">6</div>
    </div>
</section>

<section>
    <h2>align-items: flex-start</h2>
    <div class="container start">
        <div class="item petit">1</div>
        <div class="item grand">2</div>
        <div class="item moyen">3</div>
        <div class="item petit">4</div>
        <div class="item grand">5</div>
        <div class="item moyen">6</div>
    </div>
</section>
```

## Contraintes

- le conteneur doit utiliser Flexbox
- les blocs doivent revenir à la ligne avec `flex-wrap: wrap`
- les blocs doivent avoir des hauteurs différentes
- créer un test avec `align-items: stretch`
- créer un test avec `align-items: center`
- créer un test avec `align-items: flex-start`

## Notes

- `align-items` agit sur l’alignement des éléments sur l’axe secondaire
- avec `flex-direction: row`, l’axe secondaire est vertical