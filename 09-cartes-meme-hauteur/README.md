# Exercice 9. Liste de cartes de même hauteur

## Objectif

Afficher 3 cartes sur une seule ligne.  
Le contenu texte de chaque carte est différent, mais toutes les cartes doivent garder la même hauteur.

## Compétences travaillées
- `display: flex`
- `flex`
- `align-stretch` ou hauteur égale par comportement flex

## Structure HTML

```html
<div class="cards">
    <div class="card">
        <p>Contenu court</p>
    </div>
    <div class="card">
        <p>Contenu un peu plus long pour créer une différence de hauteur apparente.</p>
    </div>
    <div class="card">
        <p>Contenu encore plus long pour tester l’alignement et vérifier que toutes les cartes gardent la même hauteur malgré des textes différents.</p>
    </div>
</div>
```

## Contraintes

- les 3 cartes doivent être affichées sur une seule ligne
- le contenu texte doit être différent dans chaque carte
- toutes les cartes doivent avoir la même hauteur visuelle
- utiliser Flexbox sur le parent
- ajouter du padding, une bordure et éventuellement un fond pour bien voir les cartes