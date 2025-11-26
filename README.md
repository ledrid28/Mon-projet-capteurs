# Suivi automatisé de la dégradation du PHA dans le sol

## Description
Ce projet utilise une Raspberry Pi et un Arduino pour suivre la dégradation du PHA dans le sol en collectant automatiquement des données environnementales et en prenant des photos à intervalles réguliers.

## Objectifs
- Collecter les données chaque minute (température, humidité, etc.)
- Prendre une photo toutes les deux minutes
- Éviter les interférences et la duplication des données
- Stocker les mesures et images avec horodatage
- Assurer un suivi continu du processus de dégradation

##Matériel
- Raspberry Pi
- Arduino Uno/Nano
- Capteurs (DHT22, CO₂, conductivité…)
- Caméra Raspberry Pi
- Relais statique + tapis chauffant
- Câbles, alimentation…

## Fonctionnement général
- L’Arduino lit les capteurs et envoie les données via USB.
- La Raspberry Pi :
  - collecte les données toutes les minutes,
  - prend une photo toutes les deux minutes,
  - évite d’exécuter les deux actions simultanément,
  - stocke tout dans un CSV + dossier images.

## Documentation complète
Pour les détails techniques, consulter le dossier :

👉 `docs/`

ou le fichier de navigation :

👉 `SUMMARY.md`

## 📂 Structure du dépôt
