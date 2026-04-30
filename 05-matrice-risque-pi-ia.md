# 05 — Matrice de risque PI / IA

Objectif : disposer d’une vue simple par usage IA afin d’identifier les risques de propriété intellectuelle, de documentation et de preuve.

Copier-coller le tableau ci-dessous dans un outil de suivi interne ou compléter directement dans ce fichier.

| Usage IA | Outil / fournisseur | Modèle utilisé | Données / contenus utilisés | Type de sortie | Risque PI identifié | Documentation disponible | Clause contractuelle utile | Responsable interne | Action à mener |
|---|---|---|---|---|---|---|---|---|---|
| Exemple : génération de synthèses commerciales | Fournisseur X | Modèle Y | Données CRM + prompts utilisateurs | Texte | Réutilisation de contenus clients ; similarité avec contenus tiers | Documentation fournisseur partielle | Clause de non-réutilisation des données client ; garantie PI | DSI / Juridique | Obtenir politique copyright + vérifier indemnisation |
| Exemple : assistance à la rédaction de code | Fournisseur X | Modèle Y | Prompts développeurs + code interne | Code | Reproduction de code tiers ; confidentialité code interne | À compléter | Clause confidentialité prompts ; garantie usage commercial | CTO | Vérifier logs, réutilisation, droits sur sorties |
| Exemple : génération d’images marketing | Fournisseur X | Modèle Y | Prompts marketing | Images | Similarité avec œuvres protégées ; droit des marques | À compléter | Garantie PI ; procédure de retrait | Marketing / Juridique | Définir validation avant publication |
| Exemple : chatbot documentaire interne | Fournisseur X | Modèle Y | Base documentaire interne | Réponses texte | Réutilisation de documents confidentiels ; hallucinations | À compléter | Clause confidentialité ; SLA ; assistance incident | DSI / Métier | Prévoir supervision humaine |

## Critères d’évaluation rapide

### Risque faible

- Usage interne limité.
- Données bien identifiées.
- Pas de contenus tiers sensibles.
- Documentation fournisseur suffisante.
- Clauses contractuelles robustes.

### Risque moyen

- Usage interne large ou usage client limité.
- Données provenant de plusieurs sources.
- Documentation partielle.
- Clauses PI ou garanties imprécises.
- Sorties utilisées avec validation humaine.

### Risque élevé

- Usage commercial externe.
- Sorties publiées ou intégrées dans un produit.
- Contenus protégés potentiellement concernés.
- Données d’entraînement ou sources peu documentées.
- Absence de garantie fournisseur.
- Absence de procédure de réclamation.

## Questions à traiter pour chaque ligne

- L’usage est-il nécessaire ?
- Les données sont-elles maîtrisées ?
- Les sorties peuvent-elles être utilisées commercialement ?
- Le fournisseur donne-t-il une garantie exploitable ?
- Existe-t-il une procédure en cas de réclamation ?
- Le dossier de preuve est-il suffisant ?

[← Retour à l’accueil du kit](index.html)
