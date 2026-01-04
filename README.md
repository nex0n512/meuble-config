# Configurateur de Meuble Modulaire 3D

Outil de configuration visuelle pour meubles modulaires avec plateaux bois et tubes acier.

## Fonctionnalités

- **Visualisation 3D temps réel** (Three.js)
- **Plateaux modulaires** en forme de L (rectangles A et B combinables)
- **Tubes acier** avec hauteurs configurables (13, 24, 35 cm)
- **Tubes compensatoires** automatiques pour les étages sautés
- **Pièce virtuelle** avec sol et murs personnalisables
- **Positionnement** du meuble dans la pièce (contraintes murs)
- **Vues** : perspective/orthographique, hauteur caméra, rotation
- **Export** : JSON (configuration) et PNG (image 3D)
- **Sauvegarde automatique** dans localStorage

## Utilisation

Ouvrir `index.html` dans un navigateur moderne (Chrome, Firefox, Edge).

Aucune installation requise - tout est dans un seul fichier HTML autonome.

## Structure du meuble

```
      ← Larg. A →← Largeur B →
    ┌─────────┬───────────────┐  ↑
    │         │               │  │ Prof. A
    │  Rect A │    Rect B     │  │
    │         ├───────────────┘  ↓
    │         │ ↑ Prof. B
    └─────────┘
  ▲ FOND (mur) - A+B = 1 pièce en L
```

## Licence

Usage personnel.
