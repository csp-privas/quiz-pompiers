# Quiz SSUAP 🚑

Site d'entraînement sur le GDO **« Secours et soins d'urgence aux personnes »** (DGSCGC, novembre 2022, V1.1) pour les sapeurs-pompiers de la caserne.

## Fonctionnalités
- 107 questions issues exclusivement du GDO SSUAP, organisées selon les 5 chapitres du guide
- Questions à choix unique et **à réponses multiples**
- Mode entraînement par chapitre ou sous-catégorie, avec corrigé immédiat et source (chapitre du GDO)
- Mode examen chronométré (10 / 20 / toutes les questions)
- Scores et statistiques sauvegardés localement sur l'appareil

## Maintenance des questions
Les questions sont pilotées depuis un Google Sheet : chaque modification (ajout, édition, suppression) est reprise automatiquement par le site au rechargement. La colonne « Bonne réponse » accepte une lettre (question simple) ou plusieurs (ex. `ABD` pour une question à réponses multiples).

> `index.html` embarque aussi une banque de questions intégrée : le site fonctionne même si le sheet est inaccessible (hors réseau, intranet isolé).

## Publication
Site publié via GitHub Pages : **Settings → Pages → branche main**.

---
Document de doctrine : à adapter au cas par cas — il ne remplace ni les procédures de votre SDIS ni la réglementation en vigueur.
