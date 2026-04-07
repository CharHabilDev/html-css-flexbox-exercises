# Exercice 7. Colonnes inégales

## Objectif

Créer une ligne contenant 3 colonnes :
- la première prend 1 part de l’espace disponible
- la deuxième prend 2 parts
- la troisième prend 1 part

## Compétences travaillées
- `display: flex`
- `flex-grow` ou `flex`

## Structure HTML

```html
<div class="layout">
  <aside>Sidebar gauche</aside>
  <main>Contenu principal</main>
  <aside>Sidebar droite</aside>
</div>
```

## Contraintes

- les 3 colonnes doivent être affichées sur une seule ligne
- la colonne centrale doit être deux fois plus large que les colonnes latérales
- utiliser Flexbox pour répartir l’espace
- utiliser `flex-grow` ou la propriété raccourcie `flex`