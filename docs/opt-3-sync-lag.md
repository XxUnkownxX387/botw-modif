# Optimisation 3 : Synchronisation décalée / Lag de synchro (`sync_lag = true`)

- **Gain attendu :** Modéré (~2 à 4 fps supplémentaires).
- **Principe :** Permet au CPU de lire les résultats GPU de la frame précédente (`nvnSyncWait` non bloquant), éliminant les bulles d'attente (*stalls*) entre le processeur et le processeur graphique.
- **Compatibilité :** 100% compatible avec les versions **1.0.0, 1.6.0, 1.8.2 et 1.9.0**.
