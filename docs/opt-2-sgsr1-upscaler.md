# Optimisation 2 : Upscaler SGSR1 en une seule passe (`upscaler = UPSCALE_SGSR1`)

- **Gain attendu :** Élevé (~1,0 à 1,7 ms de temps GPU par frame par rapport à FSR 1 à deux passes, soit un gain de ~4 à 5 fps).
- **Principe :** Effectue l'upscaling spatial en une seule passe shader optimisée pour les architectures mobiles Adreno/Mali.
- **Compatibilité :** 100% compatible avec les versions **1.0.0, 1.6.0, 1.8.2 et 1.9.0**.
