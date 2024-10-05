# Projet Serval

**Version actuelle** : 1.1  
**Auteur** : Jacques MAUS

## Description

Le projet Serval est une solution de sécurité automatisée basée sur la reconnaissance faciale, Arduino, et une interface pilotable depuis une application mobile Android. Il utilise une passerelle PC pour la gestion des caméras, du système de tourelle de défense airsoft, et des échanges vocaux avec une IA.

## Phases du projet

### Phase 1 : Pilotage de l'Arduino via une application Android
- **Description** : Le premier objectif est d'allumer et d'éteindre une LED via une application mobile Android.
- **Statut** : Réussi

### Phase 2 : Mise à jour de l'interface utilisateur (UI)
- **Objectif** : Mettre à jour l'UI après réception des commandes Arduino (ALLUMER/ETEINDRE la LED).
- **En cours** : Ajout d'une représentation graphique de l'état de la LED.

## Technologies utilisées
- **Arduino** : Pour le contrôle des composants électroniques (LED, capteurs, etc.).
- **Android (Kotlin)** : Pour le développement de l'application mobile.
- **PC comme passerelle** : Communication avec l'Arduino via USB.
- **Reconnaissance faciale** : Pour identifier les visiteurs via deux caméras.
- **Tourelle Airsoft** : Dispositif de défense utilisant la reconnaissance.

## Objectifs à venir
- Amélioration de l'UI et intégration de l'interface de dialogue vocal.
- Gestion des caméras et de la tourelle airsoft.
- Version incrémentée avec suivi des tests et modifications.

## Structure du projet
- **Android_App/** : Code source de l'application Android.
- **Arduino_Scripts/** : Scripts pour la gestion des composants électroniques.
- **PC_Gateway/** : Scripts et configuration pour la passerelle PC.

## Versions du projet
- **Version 1.0** : Première version avec commandes basiques pour la LED.
- **Version 1.1** : Incrémentation avec corrections des doubles requêtes.

## Installation
1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/username/Projet-Serval.git
   ```
2. **Configurer l'Arduino** : Téléversez le script à partir du dossier `Arduino_Scripts/`.
3. **Lancer l'application Android** : Installez l'APK depuis `Android_App/`.

## Contribuer au projet
Pour contribuer au projet, vous pouvez :
- Forker le dépôt.
- Proposer des modifications via des pull requests.
