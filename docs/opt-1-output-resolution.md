# Optimisation 1 : Résolution de sortie automatique (`out_lines = OUT_AUTO`)

- **Gain attendu :** Très élevé (~4,2 à 5,2 ms de temps GPU en moins par frame, passage de ~22,8 ms à ~17,6 ms sur les écrans haute définition 3200x1440).
- **Principe :** Limite le pipeline de présentation final aux lignes nécessaires (ex. 1080p) tout en maintenant la résolution interne 3D, réduisant la surcharge de remplissage de pixels et de composition finale.
- **Compatibilité :** 100% compatible avec les versions **1.0.0, 1.6.0, 1.8.2 et 1.9.0** (géré au niveau du runtime NVN/Vulkan).
