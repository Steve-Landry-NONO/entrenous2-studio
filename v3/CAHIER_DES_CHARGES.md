# EntreNous2 — Showroom V3 / Phase 0

## Statut
Base expérimentale, distincte du site publié. Aucune modification de `main`.

## Hypothèses de surfaces
- Airbnb KONOS SUITES : 20 m², rectangle **5 × 4 m** (hypothèse).
- Place Michelet : **salon mesuré environ 3,75 × 2,77 m = 10,39 m²** (croquis transmis le 30 octobre 2026). Zone ouverte sur cuisine et entrée, surface théorique du salon, pas nécessairement intégralement exploitable. Terrasse et fenêtre sur le côté gauche, canapé le long du côté bas, bureau/TV côté haut, chauffage à proximité du canapé. Vérifier les dimensions nettes, meubles et dégagements.
- Studio idéal prospectif : 25 m², rectangle **5 × 5 m** (hypothèse).
- Hauteur provisoire : 2,50 m, non mesurée.
- Place Michelet : plan schématique utilisateur disponible, ouvrants et mobilier identifiés approximativement. À confirmer : position exacte des prises, hauteurs, dimensions du canapé, dégagements, seuils et acoustique. Autres espaces : non relevés.

Ces hypothèses n'autorisent **aucun achat dimensionnant ni travaux**.

## Intentions par lieu
- **Airbnb :** décor réversible, équipements mobiles, rangement, aucune fixation permanente.
- **Place Michelet :** **mini-plateau salon réversible** pour duo en priorité, trio seulement après simulation d'encombrement, table ronde à quatre déconseillée dans cette zone de 10,4 m². Utiliser idéalement canapé et table existants, supports compacts et lumières hors champ. Ne pas obstruer entrée, terrasse, fenêtre, circulation vers la cuisine, chauffage.
- **Idéal :** espace prospectif, sans prétendre représenter un logement actuel.

## Scènes à tester
1. Duo Steve / Michèle, deux micros.
2. Duo + invité, trois micros.
3. Table ronde quatre intervenants, quatre micros.
4. Salon table basse, deux micros.

Les éléments permanents du studio (caméras, éclairages, panneaux, rideaux et autres structures) doivent résister aux changements de scène.

## Décision d'architecture
Blender pour la modélisation fidèle, glTF/GLB pour les modèles exportés, Three.js / React Three Fiber avec Vite pour le configurateur web. GitHub Pages peut distribuer une compilation statique, avec configuration correcte de `base`. Aucun backend nécessaire à la phase 0.

## Jalon 0 — Critères de recette
- Sélection des trois surfaces, avec affichage explicite des dimensions *provisoires*.
- Sélection des quatre configurations, sans disparition du décor ni du matériel fixe.
- Navigation 360°, vues rapides, inspection des objets.
- Interface suffisamment claire pour identifier modes, caméras et éclairages.
- Fidélité photoréaliste **non acquise** : sera livrée seulement après création et validation des modèles Blender d'après les rendus de référence.
- Aucun écrasement de la maquette V1 ou de la visite V2.

## Informations à recueillir lors du relevé
Longueur, largeur, hauteur, porte(s), fenêtre(s), prises, radiateur(s), mobilier existant, contraintes de bruit/voisinage, photos des quatre côtés, lumière naturelle. Mesures des surfaces réellement utilisables, et non seulement surface totale du logement.

## Avant publication en production
Validation par Steve et Michèle, test des trois scénarios de locaux et des quatre formats, test sur ordinateur et téléphone, audit de la taille des modèles, et contrôle de la lisibilité des budgets.

## Règle de budget
Budget et prix indicatifs, aucun prix non vérifié ne doit être présenté comme un devis. Pour quatre voix, enregistreur à quatre entrées au minimum ; capacité à recalculer pour chaque scénario.
