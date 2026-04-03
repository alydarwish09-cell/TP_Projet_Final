# Projet Final : Analyse de Sécurité IoT

## Introduction

Ce dépôt contient l'ensemble des livrables pour le projet final d'analyse de sécurité IoT, réalisé dans le cadre du Mastère Cybersécurité. L'objectif de ce projet est de simuler le rôle d'un consultant expert en cybersécurité IoT pour auditer une solution domotique fictive, identifier ses vulnérabilités et proposer des mesures de sécurisation.

## Structure du Dépôt

```
./
├── rapport/
│   └── rapport_professionnel.pdf
├── slides/
│   └── presentation_iot_securite/
│       ├── slide_1_titre_introduction.html
│       ├── ... (autres slides HTML)
│       └── slide_15_demonstration_live_conclusion.html
├── exploits/
│   └── mqtt_exploit.sh
├── flags/
│   └── flags.txt
└── README.md
```

## Livrables

### 1. Rapport Professionnel (PDF)

Le rapport `rapport_professionnel.pdf` détaille l'analyse complète de sécurité, incluant :

*   **Contexte & Périmètre :** Description de la solution IoT auditée.
*   **Architecture Sécurisée :** Proposition d'une architecture Edge-Gateway-Cloud avec diagramme Mermaid.
*   **Reconnaissance :** Analyse du firmware (Binwalk) et de l'APK (simulation).
*   **Threat Model :** Application de STRIDE et scoring CVSS v3.1 des vulnérabilités.
*   **Scénarios d'Attaque :** Les 3 scénarios les plus critiques.
*   **Préconisations de Sécurisation :** Recommandations concrètes avec délais.
*   **Conclusion & Annexes :** Synthèse et preuves.

### 2. Présentation PPT (HTML)

Le dossier `slides/presentation_iot_securite/` contient les 15 diapositives HTML de la soutenance. Ces slides synthétisent les points clés du rapport, incluent des schémas et des captures d'écran simulées.

### 3. Scripts d'Exploitation (Démonstration Live)

Le dossier `exploits/` contient le script `mqtt_exploit.sh` qui simule l'exploitation d'un broker MQTT non sécurisé, ainsi que les commandes pour démontrer la correction.

### 4. Flags et Preuves

Le fichier `flags/flags.txt` contient les preuves fictives de la réussite de l'exploitation, sous forme de flags.

## Instructions pour la Soutenance

*   **Durée :** 10 min de présentation, 5 min de démo live, 5 min de Q&A.
*   **Démo Live :** Rejouer 1-2 exploits clés (ex: `mqtt_exploit.sh`).
*   **Explication :** Justifier les choix techniques et les recommandations.

## Auteur

Manus AI (en tant que consultant expert en cybersécurité IoT)
