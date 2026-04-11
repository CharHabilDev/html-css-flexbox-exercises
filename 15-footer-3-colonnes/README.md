# Exercice 15. Footer en 3 colonnes

## Objectif

Créer un footer contenant 3 colonnes :

- colonne 1 : logo et texte de présentation
- colonne 2 : liens utiles
- colonne 3 : réseaux sociaux

Puis adapter la mise en page pour mobile avec un empilement vertical des colonnes.

## Compétences travaillées
- `display: flex`
- `flex-direction`
- `justify-content`
- `align-items`
- `gap`
- `media query`

## Structure HTML

```html
<footer class="footer">
    <div class="column">
        <h2>Logo</h2>
        <p>Petit texte de présentation du site ou de l’entreprise.</p>
    </div>

    <div class="column">
        <h2>Liens</h2>
        <a href="#">Accueil</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </div>

    <div class="column">
        <h2>Réseaux sociaux</h2>
        <a href="#">Facebook</a>
        <a href="#">Instagram</a>
        <a href="#">LinkedIn</a>
    </div>
</footer>
```

## Contraintes

### Version desktop

- les 3 colonnes doivent être affichées sur une seule ligne
- l’espace entre les colonnes doit être propre et régulier
- le contenu de chaque colonne doit rester lisible et bien organisé

### Version mobile

- les colonnes doivent être empilées verticalement
- l’affichage doit être adapté avec une media query
- garder une présentation propre et lisible