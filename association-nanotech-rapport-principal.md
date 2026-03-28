# Rapport Principal : Association de Nanotechnologie Pratique EPFL

## Création de la Première Association Estudiantine de Nanotechnologie avec Accès Salle Blanche

---

**Auteurs** : [À compléter - Fondateurs de l'association]
**Date** : Mars 2026
**Version** : 2.0
**Classification** : Document de travail interne

---

## Résumé Exécutif

Ce rapport présente l'analyse complète menant à la recommandation de créer la première association étudiante de nanotechnologie pratique au monde disposant d'un accès autonome à une infrastructure de microfabrication de niveau recherche. L'association proposée, basée à l'EPFL et utilisant les installations du Center of MicroNanotechnology (CMi), vise à combler un vide identifié dans le paysage mondial : aucune association étudiante ne propose actuellement une plateforme intégrée permettant la conception, la fabrication et la caractérisation de dispositifs micro et nanotechnologiques par des étudiants.

Le projet recommandé est un biocapteur photonique intégré combinant microrésonateurs en anneau et spectromètre Fourier sur une même plateforme SOI, avec une durée de développement de 18 mois et un potentiel de publication ainsi que de création de startup.

---

## I. Le Projet Recommandé

### 🥇 Biocapteur photonique intégré avec spectromètre on-chip

**Domaines :** Nanophotonique + Bio-MEMS + ASIC

**Pourquoi celui-là et pas un autre :**

| Critère                | Score | Détail                                                                         |
| ---------------------- | ----- | ------------------------------------------------------------------------------ |
| Faisabilité en 18 mois | ★★★★★ | Process flow standard sur SOI — CMi a tout l'équipement                        |
| Originalité mondiale   | ★★★★★ | Premier Lab-on-chip monolithiquement intégré avec spectromètre Fourier on-chip |
| Potentiel publication  | ★★★★☆ | Comparable aux meilleurs travaux de conférence photonique/microfluidique       |
| Potentiel startup      | ★★★★★ | Marché POCT (diagnostic point-of-care) — Genalyte a levé $100M+                |
| Multidisciplinarité    | ★★★★★ | Photonique + microfluidique + électronique de lecture                          |
| Compétences acquises   | ★★★★★ | Design PIC, lithographie avancée, caractérisation, fonctionalisation bio       |

**Ce que vous construiriez :**

```
Puce SOI unique contenant :
├── Microrésonateur en anneau (MRR)  → biocapteur évanescent
├── Spectromètre Fourier intégré (SHFTS) → lecture optique on-chip
└── Canaux microfluidiques → flow cell pour échantillon biologique

= Plus besoin d'analyseur optique externe = chip autonome
```

**Timeline réaliste :**

| Phase                         | Durée          | Objectif                               |
| ----------------------------- | -------------- | -------------------------------------- |
| Design + simulation           | 2-3 mois       | Klayout layout + COMSOL simulation     |
| Fab 1ère itération            | 1-2 mois       | CMi (lithographie DUV, ICP-RIE, dépôt) |
| Caractérisation opt.          | 1-2 mois       | Setup de test, mesure de sensibilité   |
| Fonctionalisation + tests bio | 3-4 mois       | Anticorps, IgG, CRP                    |
| **Prototype fonctionnel**     | **12-14 mois** | Preuve de concept démontrable          |
| Publication / Pitch startup   | 14-18 mois     | Conference + Venture Kick              |

**Coût estimé :** CHF 3 000–8 000 en consommables (hors accès CMi subventionné EPFL) + CHF 150-300/étudiant pour TinyTapeout si vous intégrez un ASIC de lecture.

---

## II. Analyse du Paysage Mondial

### 2.1 État des Lieux des Associations Existantes

La recherche a permis d'identifier plusieurs types d'organisations étudiantes liées à la nanotechnologie :

**Associations avec fabrication réelle (très rare)**

- **SEMMI** (Université de Chicago) : Seul club étudiant qui gère un MPW MEMS réel
- **SiliconJackets** (Georgia Tech) : Tapeout RISC-V avec OpenROAD, mais sans accès cleanroom

**Associations éducatives sans fabrication**

- **EPFL Photonics Chapter, Dynamic, QET** : Tous sociaux/éducatifs, zéro fabrication
- **Chapitres SPIE/OPTICA** (300+ dans le monde) : Événements et networking

**Le vide identifié**

| Ce qui existe                 | Ce qui n'existe PAS                                |
| ----------------------------- | -------------------------------------------------- |
| SEMMI (Chicago) — MPW MEMS    | Aucune association student-led multi-technologique |
| SiliconJackets — ASIC digital | Aucun équivalent européen/suisse                   |
| iGEM — Bio hardware           | Pas d'équivalent photonique/MEMS/nanofab           |

**Conclusion :** Vous pouvez être les **premiers au monde** à créer une vraie association de nanotechnologie pratique avec accès cleanroom.

---

## III. Modèles de Startups deeptech Issues de Projets Étudiants

### 3.1 Cas de Réussite Documentés

| Startup               | Origine             | Funding           | Domaine                        |
| --------------------- | ------------------- | ----------------- | ------------------------------ |
| **Lightmatter** (MIT) | Thèse PhD 2017      | $822M             | Calcul photonique IA           |
| **Ayar Labs** (MIT)   | Recherche RLE 2015  | $870M             | Optical interconnects          |
| **Corintis** (EPFL)   | Thèse PhD 2017-2022 | $24M Series A     | Refroidissement microfluidique |
| **Insolight** (EPFL)  | Mémoire master 2012 | $13.3M            | Microlentilles optiques        |
| **Pi Imaging** (EPFL) | Recherche EPFL      | Acquise par Zeiss | Caméra SPAD mégapixel          |

### 3.2 Facteurs de Succès

| Facteur                    | Description                                     |
| -------------------------- | ----------------------------------------------- |
| Timing optimal             | Année diplôme = année création entreprise       |
| Performance moat           | "World's first" ou ordre de grandeur meilleur   |
| Investisseurs stratégiques | NVIDIA, Microsoft comme investisseurs + clients |
| Protection IP proactive    | Brevets avant publications                      |

---

## IV. Opportunités de Financement

### 4.1 Programmes EPFL

| Programme      | Montant           | Éligibilité                        |
| -------------- | ----------------- | ---------------------------------- |
| VPA Subsidy    | Variable (ad hoc) | Associations étudiantes EPFL       |
| Ignition Grant | CHF 30 000 max    | Vision startup + labo EPFL         |
| InnoGrant      | CHF 100 000       | Démonstration tech + incorporation |

### 4.2 Programmes Nationaux Suisses

| Programme        | Montant                | Notes                        |
| ---------------- | ---------------------- | ---------------------------- |
| **Venture Kick** | CHF 150 000 (3 étapes) | Accepte pré-incorporation    |
| **TalentKick**   | CHF 5 000              | Master/PhD étudiants suisses |

### 4.3 Coûts Pratiques

- **TinyTapeout MPW** : $150-300 par design étudiant
- **Consommables CMi** : CHF 3 000-8 000 pour projet de 6 mois
- **Total estimé** : CHF 5 000-15 000 selon complexité

---

## V. Tout Ce Que Vous N'Avez Pas Encore Pensé

Voici les **27 dimensions critiques** manquantes, groupées par catégorie :

### A. Structure Juridique et Gouvernance (CRITIQUE)

| #   | Élément manquant                  | Pourquoi c'est critique                                    | Action concrète                           |
| --- | --------------------------------- | ---------------------------------------------------------- | ----------------------------------------- |
| 1   | **Forme juridique de l'asso**     | Influence capacité à signer contrats, obtenir financements | Demander à Cyrill + VPA EPFL              |
| 2   | **Régime de responsabilité**      | Si accident en cleanroom, qui est responsable ?            | Clarifier avec Rechtsdienst EPFL          |
| 3   | **Accord de gouvernance interne** | Qui décide ? Que se passe-t-il en cas de conflit ?         | Rédiger un MoU entre fondateurs           |
| 4   | **Propriété intellectuelle (IP)** | Qui owns les designs/brevets ?                             | Discuter avec EPFL TTO AVANT de commencer |

### B. Gestion du Savoir et Transmission

| #   | Élément manquant               | Pourquoi c'est critique                          | Action concrète              |
| --- | ------------------------------ | ------------------------------------------------ | ---------------------------- |
| 5   | **Documentation systématique** | Projets meurent quand gens partiront             | Créer Lab Notebook numérique |
| 6   | **Pipeline de formation**      | Intégrer nouveaux membres sans perdre temps      | Programme 3 niveaux          |
| 7   | **Runsheets et recettes**      | Procédures en mémoire ne survivent pas           | Repository avec runsheets    |
| 8   | **Charte de documentation**    | "Pas de run sans photo, pas de photo sans entry" | Chief Documentation Officer  |

### C. Sécurité et Risques (NON-NÉGOCIABLE)

| #   | Élément manquant                     | Pourquoi c'est critique                            | Action concrète                       |
| --- | ------------------------------------ | -------------------------------------------------- | ------------------------------------- |
| 9   | **Plan de gestion des risques**      | HF, Cl₂, haute température = risques réels         | HAZOP avec Cyrill AVANT premier run   |
| 10  | **Protocole d'urgence**              | Que faire si inhalation Cl₂ ? Feu ?                | Safety briefing équipe sécurité CMi   |
| 11  | **Certification formation sécurité** | Accès machines dangereuses nécessite certification | Identifier certifications avec Cyrill |
| 12  | **Inventaire chemicals**             | Règles strictes stockage/élimination               | Travailler avec service HSE EPFL      |

### D. Relations avec le CMi et EPFL

| #   | Élément manquant              | Pourquoi c'est critique                       | Action concrète                       |
| --- | ----------------------------- | --------------------------------------------- | ------------------------------------- |
| 13  | **Accord d'accès formalisé**  | "Cyrill est d'accord" n'est pas un document   | Demander accord écrit à Cyrill        |
| 14  | **Conflict of interest**      | Startup issue du projet = conflit accès CMi ? | Clarifier avec TTO EPFL               |
| 15  | **Continuity si Cyrill part** | Sponsor actuel peut partir                    | Identifier faculty advisor alternatif |
| 16  | **Communication admin EPFL**  | Orders, budgets : passent par admin           | Identifier contact clé                |

### E. Structure de l'Association

| #   | Élément manquant             | Pourquoi c'est critique                 | Action concrète                       |
| --- | ---------------------------- | --------------------------------------- | ------------------------------------- |
| 17  | **Membership structure**     | Qui peut être member ? Free-riders ?    | Structure 2 niveaux : core + extended |
| 18  | **Attractivité**             | Pourquoi rejoindre vs autre club ?      | Value proposition claire              |
| 19  | **Gouvernance décisions**    | Comment choisir/arrêter projet ?        | Technical Decision Framework          |
| 20  | **Compensation/recognition** | Attestations ? Co-authorships ? Parts ? | Définir early                         |

### F. Stratégie de Projet

| #   | Élément manquant            | Pourquoi c'est critique          | Action concrète         |
| --- | --------------------------- | -------------------------------- | ----------------------- |
| 21  | **Critères choix projet**   | Sans critères, décision bloquée  | Matrice critères        |
| 22  | **Gated development**       | Pas ressources pour 3 projets // | Gates : design/fab/test |
| 23  | **IP strategy**             | Breveter ? Open source ?         | En discuter avec TTO    |
| 24  | **Publications vs startup** | Publier = IP publique            | Définir priorité        |

### G. Ressources et Budget

| #   | Élément manquant               | Pourquoi c'est critique                | Action concrète        |
| --- | ------------------------------ | -------------------------------------- | ---------------------- |
| 25  | **Plan financement 2 ans**     | Consommables, composants, conf         | VPA + Venture Kick     |
| 26  | **Coûts cachés**               | Wafers test, reagents, caractérisation | Budget détaillé Cyrill |
| 27  | **Ressources non-financières** | Licences COMSOL, Klayout, espace       | Lister avec Cyrill     |

---

## VI. Recherches à Effectuer pour Clarifier le Projet

### Recherche 1 : Capability CMi exacte

**Qui:** Cyrill directement

- CMi fait du dépôt SiN (LPCVD ou PECVD) ?
- CMi a un système e-beam ?
- CMi peut faire du release HF vapor ou BOE ?
- CMi a station caractérisation optique ?

### Recherche 2 : Supervisor / Faculty Advisor

**Qui:** Vous — en parlant avec Cyrill

- Quel professeur EPFL pour co-superviser ?
- Groupe Kippenberg (photonique) ? Brugger (microfab) ?

### Recherche 3 : Analyse patent landscape

**Qui:** EPFL TTO + searches brevets

- MRR + SHFTS sur même puce déjà breveté ?
- Licences disponibles ?

### Recherche 4 : Marché applicatif biocapteur

**Qui:** Vous + recherches

- Taille marché POCT photonique
- Clients potentiels (hôpitaux, Roche ?)
- Regulatory pathway (FDA 510(k)?)

### Recherche 5 : Analyse concurrence

**Qui:** Recherches

- Genalyte : qu'est-ce qu'ils font ?
- Autres startups biosensor photoniques

### Recherche 6 : TinyTapeout + ASIC workflow

**Qui:** Vous + formation

- Cours Zero to ASIC Matt V.
- ASIC lecture sur TinyTapeout

### Recherche 7 : Regulatory dispositifs médicaux

**Qui:** Recherches + EPFL MedTech club

- Classe dispositif ? Certification ?
- Realistic dans le timeframe ?

### Recherche 8 : Mentors industriels

**Qui:** Vous, avec aide Cyrill

- 1-2 mentors industrie photonique/MEMS
- Advisory sessions trimestrielles

---

## VII. Feuille de Route sur 24 Mois

```
MOIS 1-2 : FONDATIONS
├── Finaliser forme juridique (VPAA, service juridique EPFL)
├── Signer accord accès formalisé CMi (via Cyrill)
├── Identifier 1 faculty advisor EPFL
├── Rédiger MoU entre fondateurs
├── Budget + recherche financement (VPA deadline nov 2025)
└── 1ère réunion info / pitch recrutement

MOIS 3-4 : RECRUTEMENT + DESIGN
├── Recruter 4-6 membres (core team)
├── Formation : safety CMi + Klayout + COMSOL
├── Lancer design biocapteur
├── Appliquer Venture Kick stage 1 (CHF 10K)
└── Valider design par Cyrill + faculty

MOIS 5-8 : PREMIÈRE FABRICATION
├── Gate 1 : Design review
├── 1ère itération fab CMi
├── Tests optiques + caractérisation
├── Gate 2 : Est-ce que ça marche ?
└── Recruter 2e vague

MOIS 9-14 : ITERATION + FONCTIONNALISATION
├── 2ème itération fab si nécessaire
├── Fonctionnalisation bio (anticorps)
├── Caractérisation complète
├── Rédaction publication/brevet
└── Appliquer Venture Kick stage 2 (CHF 40K)

MOIS 15-18 : VALIDATION + PRÉSENTATION
├── Gate 3 : Démonstration fonctionnelle
├── Soumettre publication ou brevet
├── Pitch Venture Kick stage 3 (CHF 100K)
├── Présentation EPFL TTO
└── Préparer seed deck startup

MOIS 19-24 : CONSOLIDATION
├── Finalisation publication
├── Recrutement + formation relève
├── Passage relais nouveaux leaders
└── Si startup : incorporation + InnoGrant
```

---

## VIII. Conclusion

La création de cette association représente une opportunité historique de combler un vide mondial et de démontrer qu'une organisation étudiante peut mener des projets de recherche de niveau mondial en nanofabrication. Le projet de biocapteur photonique intégré offre un équilibre optimal entre ambition technique, faisabilité temporelle et potentiel entrepreneurial.

Les facteurs de succès reposent sur :

- La qualité de l'encadrement par Cyrill et le faculty advisor
- La rigueur de la documentation et de la transmission
- L'engagement prolongé des membres fondateurs
- La capacité à naviguer les processus institutionnels EPFL

**Le chemin vers la première association mondiale de nanotechnologie pratique est tracé. Il ne reste plus qu'à l'emprunter.**

---

## Annexe A : Équipements CMi Requis

| Équipement                   | Utilisation         | Disponibilité |
| ---------------------------- | ------------------- | ------------- |
| Lithographie DUV             | Gravure guides onde | Disponible    |
| E-beam                       | Résonateurs sub-μm  | Disponible    |
| ICP-RIE Si                   | Gravure silicium    | Disponible    |
| LPCVD SiN                    | Dépôt nitrure       | À confirmer   |
| Station caractérisation opt. | Tests optiques      | Accès requis  |

## Annexe B : Contacts Clés

| Fonction        | Contact        | Action                   |
| --------------- | -------------- | ------------------------ |
| Process CMi     | Cyrill         | Accord accès, validation |
| Faculty Advisor | [À identifier] | Patronage                |
| VPA             | [À identifier] | Soutien asso             |
| TTO EPFL        | [À identifier] | IP                       |

---

_Document généré dans le cadre du projet de recherche pour la création de l'association de nanotechnologie pratique EPFL. Tous droits réservés aux auteurs._
