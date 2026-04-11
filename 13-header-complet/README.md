# Exercice 13. Header complet

## Objectif

Créer un header contenant :
- un logo
- un menu de navigation
- un bouton “S’inscrire”

Puis adapter la mise en page pour mobile afin que les éléments se réorganisent verticalement ou que le menu passe sous le logo.

## Compétences travaillées
- `display: flex`
- `justify-content`
- `align-items`
- `flex-direction`
- `gap`
- `media query`

## Structure HTML

```html
<header class="header">
    <div class="logo">Logo</div>

    <nav class="menu">
        <a href="#">Accueil</a>
        <a href="#">Services</a>
        <a href="#">Blog</a>
        <a href="#">Contact</a>
    </nav>

    <button>S’inscrire</button>
</header>
```

## Contraintes

### Version desktop

- le logo doit être placé à gauche
- le menu doit être centré horizontalement dans le header
- le bouton doit être placé à droite
- les éléments doivent être alignés verticalement au centre

### Version mobile

- les éléments doivent être réorganisés pour rester lisibles sur petit écran
- le logo doit rester en haut
- le menu doit passer en dessous
- le bouton doit être placé sous le menu
- utiliser une media query pour adapter la mise en page