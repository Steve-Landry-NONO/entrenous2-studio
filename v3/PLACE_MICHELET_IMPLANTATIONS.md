# EntreNous2 V3 — Place Michelet : implantation à l'échelle (révision 2026-10-30)

## Données mesurées
- Salon : **3,75 × 2,77 m = 10,3875 m²**.
- Mur du bas du croquis : canapé, entrée à proximité.
- Mur opposé : meuble TV et bureau.
- Côté gauche : fenêtre / accès terrasse.
- Côté droit : ouverture vers cuisine.
- Hauteur sous plafond, porte, emplacement prises et dimensions exactes des meubles : non encore mesurés.

## Scénarios
### PM-1 — canapé conservé
- Canapé à emplacement d'origine (mur du bas).
- Deux micros dynamiques, table basse et deux caméras en priorité.
- Une lumière diffuse principale et un appoint si espace disponible.
- Fond Signature à installer sans fixer durablement au logement.

### PM-2 — fauteuils d'occasion
- Canapé déplacé/hors plateau si faisable, **sans supposer un rangement qui n'existe pas**.
- Deux fauteuils : gabarit de conception provisoire **64 × 60 cm chacun**, non une cote fabricant.
- Petite table, deux micros, caméras sur petits pieds et lumière diffuse.
- Objectif d'achat : **100 € la paire**, sous réserve d'offres locales réelles.
- Vérifier la circulation entrée → cuisine et fenêtre/terrasse, la stabilité des pieds et la sécurité des câbles.

## Contraintes
- Les 10,39 m² mesurés ne sont pas entièrement libres : meubles existants et accès réduisent la surface utile.
- Les pieds des softboxes et des caméras peuvent imposer des décalages hors du rectangle du salon, si autorisés par les accès.
- Aucun achat sur simple rendu 3D. Relever dimensions des fauteuils recherchés et des trépieds, puis reproduire leurs empreintes au sol.
- Une table ronde à quatre n'est pas validée dans le salon de Place Michelet.

## Qualité visuelle
Le prototype `v3/index.html` reste une **étude volumétrique interactive**, avec mobilier paramétrique simplifié. Le rendu photoréaliste (tissus, textures, éclairage, géométrie détaillée) nécessite un modèle Blender et des tests navigateur.

## Recette indispensable avant fusion
1. Tester le rendu réel sur desktop et smartphone.
2. Vérifier les cinq vues rapides et la rotation 360°.
3. Changer les configurations : aucun éclairage ni caméra ne doit disparaître involontairement.
4. Mesurer les dégagements et corriger les objets s'interpénétrant.
5. Valider les deux scénarios PM-1 et PM-2 avec des photos prises depuis les angles réels.
6. Mettre les références de fauteuils à jour : prix, photos et disponibilité vérifiés avant achat.
