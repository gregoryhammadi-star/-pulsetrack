# PulseTrack V2.1

Version de transition orientée confidentialité.

- Données stockées localement dans le navigateur.
- Données du coffre chiffrées côté appareil avec AES-GCM + PBKDF2.
- Export/import d'une sauvegarde chiffrée.
- Aucun enregistrement des données de santé dans GitHub.
- Architecture préparée pour une migration vers une vraie app iOS V2.2.

## Important
Cette PWA n'accède pas directement à Apple Health/HealthKit. L'intégration HealthKit nécessite une application iOS avec la capacité HealthKit et les autorisations Apple correspondantes. Garmin nécessite l'intégration officielle Garmin Connect Developer Program/API et le consentement utilisateur.

La V2.2 native pourra utiliser le trousseau sécurisé iOS pour les secrets et HealthKit pour les données Apple Santé.
