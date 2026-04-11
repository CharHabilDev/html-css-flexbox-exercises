# Exercice 16. Page complète en Flexbox

## Objectif

Créer une page complète contenant :
- un header
- une zone principale avec une sidebar et un contenu
- un footer

## Compétences travaillées
- `display: flex`
- `justify-content`
- `align-items`
- `flex-direction`
- `gap`
- `media query`

## Structure HTML

```html
<div class="page">
    <header>Header</header>

    <main class="main-layout">
        <aside>Sidebar</aside>
        <section class="content">Contenu principal</section>
    </main>

    <footer>Footer</footer>
</div>
```

## Contraintes

### Version desktop

- le header doit être placé en haut
- le footer doit être placé en bas
- la sidebar doit être affichée à gauche
- le contenu principal doit être affiché à droite
- la zone principale doit utiliser Flexbox

### Version mobile

- la sidebar doit passer au-dessus ou au-dessous du contenu principal
- la mise en page doit être adaptée avec une media query
- l’ensemble doit rester lisible et bien espacé

## Remarque

La page peut être organisée en colonne pour la structure générale, puis utiliser Flexbox à l’intérieur de la zone principale pour placer la sidebar et le contenu.