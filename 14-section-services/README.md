# Exercice 14. Section “services”

## Objectif

Créer une section contenant 3 cartes de services.

- sur grand écran, les cartes doivent être affichées sur une seule ligne
- sur petit écran, les cartes doivent être empilées en colonne
- le contenu de chaque carte doit être centré

## Compétences travaillées
- `display: flex`
- `flex-direction`
- `justify-content`
- `align-items`
- `gap`
- `media query`

## Structure HTML

```html
<section class="services">
    <article class="card">
        <h2>Développement web</h2>
        <p>Création de sites modernes et responsives.</p>
    </article>

    <article class="card">
        <h2>Design UI</h2>
        <p>Interfaces propres, lisibles et agréables à utiliser.</p>
    </article>

    <article class="card">
        <h2>Maintenance</h2>
        <p>Correction de bugs et amélioration continue.</p>
    </article>
</section>
```

## Contraintes

- les 3 cartes doivent être sur une seule ligne en grand écran
- les cartes doivent passer en colonne sur petit écran
- le contenu de chaque carte doit être centré horizontalement
- utiliser Flexbox pour organiser les cartes
- utiliser une media query pour adapter l’affichage