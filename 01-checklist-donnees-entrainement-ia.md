# 01 — Checklist des données et contenus utilisés dans un projet IA

Objectif : identifier ce que le système IA utilise, à quel moment, avec quelles garanties et avec quelle documentation.

## 1. Description générale du projet

- Quel est le cas d’usage exact ?
- Le système est-il utilisé en interne ou intégré à un produit destiné à des clients ?
- Le système génère-t-il du texte, du code, des images, de l’audio, de la vidéo ou des recommandations ?
- L’usage est-il expérimental, pilote, en production ou commercialisé ?
- Le système est-il développé en interne, fourni par un tiers ou intégré via API ?

## 2. Données et contenus utilisés

- Quelles données sont utilisées en entrée ?
- Les données proviennent-elles de sources internes ?
- Les données proviennent-elles de sources externes ?
- Des contenus protégés par droit d’auteur ou droits voisins peuvent-ils être concernés ?
- Des contenus clients sont-ils utilisés ?
- Des contenus collaborateurs sont-ils utilisés ?
- Des contenus publics en ligne sont-ils collectés ou moissonnés ?
- Des données personnelles sont-elles traitées ?
- Des données sensibles ou confidentielles sont-elles concernées ?

## 3. Finalité et nécessité

- Pourquoi ces données sont-elles nécessaires ?
- Le même objectif pourrait-il être atteint avec moins de données ?
- Certaines catégories de données peuvent-elles être exclues ?
- Les données sont-elles utilisées pour l’entraînement, le fine-tuning, le prompt, l’évaluation, la supervision ou l’amélioration continue ?
- Les données sont-elles utilisées uniquement par l’entreprise ou également par le fournisseur ?

## 4. Sources et droits associés

- Les sources des données sont-elles identifiées ?
- Existe-t-il une licence applicable ?
- Les conditions d’utilisation de la source autorisent-elles l’usage envisagé ?
- Des opt-out, exclusions ou restrictions doivent-ils être respectés ?
- Le fournisseur fournit-il une information sur les sources ou catégories de sources utilisées ?
- Le fournisseur dispose-t-il d’une politique copyright documentée ?

## 5. Traçabilité

- Qui a validé l’usage de ces données ?
- Quand la validation a-t-elle été réalisée ?
- Quelles hypothèses juridiques ont été retenues ?
- Les arbitrages sont-ils documentés ?
- Existe-t-il une trace des versions du modèle ou du système utilisées ?
- Existe-t-il une trace des jeux de données ou catégories de données utilisés ?

## 6. Mesures de réduction des risques

- Des filtres ou exclusions sont-ils prévus ?
- Des contrôles humains sont-ils mis en place ?
- Des tests de similarité ou de reproduction sont-ils réalisés ?
- Les sorties du modèle sont-elles vérifiées avant publication ou exploitation ?
- Une procédure existe-t-elle en cas de réclamation d’un titulaire de droits ?
- Une procédure existe-t-elle en cas de demande d’un client, partenaire ou autorité ?

## 7. Questions de synthèse

- Peut-on expliquer pourquoi ces données sont utilisées ?
- Peut-on produire une documentation fournisseur suffisante ?
- Peut-on démontrer que les risques PI ont été identifiés ?
- Peut-on démontrer que les risques données personnelles ont été examinés ?
- Peut-on suspendre ou modifier l’usage si une difficulté apparaît ?
