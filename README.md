# Kassis Creator Studio — Prototype V0.1

## Ouvrir
Ouvrir `index.html` dans un navigateur récent. Aucun build ni abonnement n'est nécessaire.

## Ce qui fonctionne dans ce prototype
- Navigation responsive PC/mobile
- Tableau de bord
- Création, consultation, changement de statut et suppression des idées
- Création et suivi des tâches
- Calendrier hebdomadaire initial avec les horaires de live définis
- Ajout de sources manuelles
- Saisie et analyse simple des résultats
- Export/import JSON
- Préférences locales

## Limites importantes
- Les données sont enregistrées dans le navigateur via localStorage. Elles ne sont pas partagées entre appareils ou utilisateurs.
- L'interface ne dispose PAS encore d'une authentification. La page Équipe est une maquette, pas un système d'invitations réel.
- Aucun scraping ni appel API n'est effectué.
- Les concepts d'exemple ne sont pas des tendances vérifiées.
- Les collectes planifiées, la connexion aux plateformes, la synchronisation et les notifications serveur nécessitent un backend.

## Étape suivante
Créer les comptes GitHub, Cloudflare et Supabase, puis déployer le frontend et connecter Supabase Auth/Database avec des règles d'accès par utilisateur et rôle. Ne jamais mettre de clé secrète dans le code frontend.
