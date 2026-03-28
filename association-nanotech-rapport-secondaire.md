# Rapport Secondaire : Projets Candidats et Analyse Approfondie

## Analyse Multicritère des Projets de Nanofabrication pour l'Association

---

**Auteurs** : [À compléter - Fondateurs de l'association]
**Date** : Mars 2026
**Version** : 1.0
**Classification** : Document de travail interne

---

## 1. Introduction

Ce rapport secondaire accompagne le rapport principal et fournit une analyse approfondie des sept projets candidats identifiés pour l'association de nanotechnologie pratique. Chaque projet est évalué selon des critères techniques, économiques et stratégiques permettant une prise de décision éclairée.

La méthodologie d'évaluation repose sur une grille multicritère pondérée, appliquée à chaque projet sur la base de la littérature scientifique récente, des données de financement des startups comparables, et de l'analyse des capacités du CMi.

---

## 2. Méthodologie d'Évaluation

### 2.1 Critères et Pondération

Chaque projet a été évalué selon six critères principaux :

| Critère                  | Pondération | Justification                                                                 |
| ------------------------ | ----------- | ----------------------------------------------------------------------------- |
| Faisabilité technique    | 25%         | Capacité à être réalisé dans le temps imparti avec les ressources disponibles |
| Originalité mondiale     | 20%         | Degré d'innovation et absence de démonstration préalable                      |
| Potentiel de publication | 15%         | Capacité à produire un article de qualité conférence/revue                    |
| Potentiel startup        | 20%         | Adéquation avec un marché adressable et capacité à lever des fonds            |
| Multidisciplinarité      | 10%         | Implication de plusieurs domaines complémentaires                             |
| Compétences acquises     | 10%         | Valeur formatrice pour les membres de l'association                           |

### 2.2 Échelle de Notation

| Score | Signification                            |
| ----- | ---------------------------------------- |
| ★★★★★ | Excellent - répond pleinement au critère |
| ★★★★☆ | Bon - répond bien au critère             |
| ★★★☆☆ | Moyen - répond partiellement au critère  |
| ★★☆☆☆ | Faible - répond faiblement au critère    |
| ★☆☆☆☆ | Non applicable ou très risqué            |

### 2.3 Sources Consultées

L'analyse s'appuie sur les sources suivantes :

- Articles scientifiques sur arXiv (2022-2025)
- Bases de données de startups (Crunchbase, Venturelab)
- Documentation technique des équipements CMi
- Rapports sectoriels sur le marché de la photonique et des MEMS
- Entretiens documentés avec des praticiens du domaine

---

## 3. Analyse Détaillée des Projets Candidats

### 3.1 Projet A : Interrupteur Photonique MEMS Accordable

#### Description Technique

Ce projet vise à développer un commutateur photonique à base de MEMS (Micro-Electro-Mechanical Systems) permettant une reconfigurabilité non-volatile des circuits optiques. Le dispositif utilise des actionneurs électrostatiques à peignes pour modifier les espaces d'air dans un coupleur adiabatique horizontal.

Les composants clés incluent :

- Guides d'ondes en silicium sur substrat SOI (Silicon-On-Insulator)
- Actionneurs MEMS à peignes pour le déplacement mécanique
- Poutres bistables pour la latching non-volatile
- Espace d'air formé par attaque sacrificielle

#### Équipements CMi Requis

| Équipement                     | Processus                                                |
| ------------------------------ | -------------------------------------------------------- |
| Lithographie DUV (193nm/248nm) | Gravure des guides d'ondes                               |
| ICP-RIE                        | Gravure du silicium et cavités MEMS                      |
| LPCVD                          | Dépôt de nitrure de silicium pour la couche structurelle |
| Aluminium PVD                  | Métallisation pour les actionneurs                       |
| Station HF/BOE                 | Release des couches sacrificielles                       |

#### Timeline

| Phase                                 | Durée          |
| ------------------------------------- | -------------- |
| Design et simulation                  | 3-4 mois       |
| Première fabrication                  | 2-3 mois       |
| Caractérisation électrique et optique | 3-4 mois       |
| Tests de commutation                  | 2-3 mois       |
| **Total**                             | **10-14 mois** |

#### Analyse SWOT

| Forces                                      | Faiblesses                                          |
| ------------------------------------------- | --------------------------------------------------- |
| Non-volatility (zéro consommation statique) | Complexité de l'intégration mécanique-optique       |
| Énergie de commutation ultra-basse (~10 fJ) | Difficile à caractériser sans équipement spécialisé |
| IP défendable (architecture bistable)       | Timeline serré pour les tests de fiabilité          |

| Opportunités                                          | Menaces                                              |
| ----------------------------------------------------- | ---------------------------------------------------- |
| Marché des optical cross-connects pour datacenters AI | Concurrence de startups bien financées (Lightmatter) |
| Demandeduen forte pour l'efficacité énergétique       | Dépendance aux trouvéeries pour la production        |

#### Potentiel de Publication

Le papier de référence de Daoxin Dai (2024) démontre la faisabilité du concept. Une association étudiante pourrait viser une conférence de niveau photonique (SPIE Photonics Europe, OSA Advanced Photonics) avec une démonstration de commutation fonctionnelle.

#### Potentiel Startup

Le marché des optical cross-connects représente environ 2 milliards de dollars en 2025, avec une croissance annuelle de 15%. Les acteurs dominants (Cisco, Juniper) acquièrent régulièrement des startups spécialisées. Le différenciateur clé est la consommation statique nulle, absente des solutions thermo-optiques actuelles.

#### Score Final

| Critère                  | Score     |
| ------------------------ | --------- |
| Faisabilité technique    | ★★★★☆     |
| Originalité mondiale     | ★★★★★     |
| Potentiel de publication | ★★★★★     |
| Potentiel startup        | ★★★★☆     |
| Multidisciplinarité      | ★★★★☆     |
| **Score total**          | **4.5/5** |

---

### 3.2 Projet B : Biocapteur Photonique Intégré avec Spectromètre On-Chip

#### Description Technique

Ce projet propose une plateforme lab-on-a-chip intégrant sur une même puce SOI un biocapteur à microrésonateur en anneau (MRR) et un spectromètre Fourier pour la lecture optique. Cette approche monolythique élimine le besoin d'analyseurs optiques externes.

Architecture du dispositif :

- Microrésonateur en anneau (MRR) pour la détection biosensorielle par champ évanescent
- Spectromètre Fourier intégré (SHFTS - Spatial-Heterodyne Fourier Transform Spectrometer)
- Canaux microfluidiques pour l'écoulement des échantillons biologiques
- Zone de functionalisation de surface pour l'immobilisation d'anticorps

#### Équipements CMi Requis

| Équipement                         | Processus                      |
| ---------------------------------- | ------------------------------ |
| Lithographie DUV ou e-beam         | Résonateurs sub-μm             |
| ICP-RIE Si                         | Gravure des guides d'ondes     |
| LPCVD SiN                          | Dépôt de nitrure pour cladding |
| Deep RIE ou ICP                    | Canaux microfluidiques         |
| Station de caractérisation optique | Tests de sensibilité           |

#### Timeline

| Phase                    | Durée          |
| ------------------------ | -------------- |
| Design (Klayout, COMSOL) | 2-3 mois       |
| Première fabrication     | 1-2 mois       |
| Caractérisationoptique   | 1-2 mois       |
| Fonctionnalisation bio   | 3-4 mois       |
| Tests avec analytes      | 2-3 mois       |
| **Total**                | **12-16 mois** |

#### Analyse SWOT

| Forces                             | Faiblesses                                           |
| ---------------------------------- | ---------------------------------------------------- |
| Intégration monolythique unique    | Complexité de la calibration spectroscopique         |
| Potentiel diagnostic POCT majeur   | Dépendance à la chimie de surface                    |
| Élimine tous les optiques externes | Tests biologiques requieren expertise complémentaire |

| Opportunités                                            | Menaces                                                     |
| ------------------------------------------------------- | ----------------------------------------------------------- |
| Marché POCTen pleine expansion (Genalyte > $100M levés) | Réglementation dispositifs médicaux                         |
| Réduction drastique de la taille vs systèmes actuels    | Concurrence de technologies établies ( ELISA, Lateral Flow) |

#### Potentiel de Publication

Le papier de Yoo/Ray T. Chen (2022) établit le proof-of-concept. Une démonstration complète avec détection de biomarqueurs réels pourrait être soumise àACS Sensors ou Analytica Chimica Acta.

#### Potentiel Startup

Le marché du diagnostic point-of-care (POCT) dépasse 40 milliards de dollars en 2025. Genalyte a levé plus de 100 millions de dollars pour une approche photonique similaire. La différenciation par intégration complète (single-chip) offre un avantage manufacturing significatif.

#### Score Final

| Critère                  | Score     |
| ------------------------ | --------- |
| Faisabilité technique    | ★★★★★     |
| Originalité mondiale     | ★★★★★     |
| Potentiel de publication | ★★★★☆     |
| Potentiel startup        | ★★★★★     |
| Multidisciplinarité      | ★★★★★     |
| **Score total**          | **4.8/5** |

---

### 3.3 Projet C : Circuit Photonique LiDAR FMCW avec Électronique Intégrée

#### Description Technique

Ce projet vise à développer un moteur LiDAR cohérent à modulation de fréquence (FMCW) intégrant photonique et électronique sur une même plateforme. Le système combine :

- Laser accordable à cavité externe
- Amplificateur à waveguide erbium-doped
- Circuit photonique pour la génération de chirp
- Électronique de pilotage en technologie SiGe BiCMOS
- Actionneurs piézoélectriques pour l'accord de longueur d'onde

#### Équipements CMi Requis

| Équipement           | Processus                    |
| -------------------- | ---------------------------- |
| Lithographie DUV     | Circuits photoniques SiN     |
| Dépôt III-V          | Intégration hétérogène       |
| Die-to-wafer bonding | Intégration semi-conducteurs |
| Accès BiCMOS         | Électronique avancée         |
| Station de test FMCW | Caractérisationoptique       |

#### Timeline

| Phase                  | Durée          |
| ---------------------- | -------------- |
| Design complexe        | 4-6 mois       |
| Intégration hétérogène | 4-6 mois       |
| Tests de ranging       | 4-6 mois       |
| **Total**              | **12-18 mois** |

#### Analyse SWOT

| Forces                                   | Faiblesses                                 |
| ---------------------------------------- | ------------------------------------------ |
| Marché LiDAR en forte croissance         | Intégration III-V/SiN extrêmement complexe |
| Complètement foundry-compatible          | Nécessite collaborateur externe pour III-V |
| Résout le problème central du LiDAR FMCW | Timeline optimiste                         |

| Opportunités                                          | Menaces                                                 |
| ----------------------------------------------------- | ------------------------------------------------------- |
| Marché automotive et robotique                        | Concurrence de startups comme Voyant Photonics ($15.4M) |
| Acquisition potentielle par grands acteurs automotive | Besoins en qualifications automotive (AEC-Q100)         |

#### Potentiel Startup

Le marché du LiDAR atteint 6 milliards de dollars en 2025, avec une projection de 20 milliards d'ici 2030. Les acteurs clés (Velodyne, Luminar, Aeva) sont tous cotés ou ont été acquis. Cependant, la complexité de l'intégration hétérogène rend ce projet particulièrement ambitieux pour une association étudiante.

#### Score Final

| Critère                  | Score     |
| ------------------------ | --------- |
| Faisabilité technique    | ★★★☆☆     |
| Originalité mondiale     | ★★★★☆     |
| Potentiel de publication | ★★★★★     |
| Potentiel startup        | ★★★★★     |
| Multidisciplinarité      | ★★★★★     |
| **Score total**          | **4.3/5** |

---

### 3.4 Projet D : MEMS Piézoélectrique AlN avec Lecture ASIC

#### Description Technique

Ce projet exploite les propriétés du nitrure d'aluminium (AlN) pour créer des transducteurs MEMS piézoélectriques. Les applications cibles incluent :

- Transducteurs ultrasonores (PMUTs - Piezoelectric Micromachined Ultrasound Transducers)
- Capteurs de masse (NEMS)
- Dispositifs de récupération d'énergie piézoélectrique
- Self-sensing cantilevers pour AFM

#### Équipements CMi Requis

| Équipement       | Processus                                    |
| ---------------- | -------------------------------------------- |
| Sputtering AlN   | Dépôt de la couche piézoélectrique           |
| PVD Pt           | Électrode inférieure                         |
| Lithographie DUV | Structure de la couche structurelle          |
| DRIE Bosch       | Gravure profonde pour structures suspensions |
| CMP              | Planarisation si nécessaire                  |

#### Timeline

| Phase                         | Durée          |
| ----------------------------- | -------------- |
| Optimisation dépôt AlN        | 3-4 mois       |
| Fabrication PMUT              | 3-4 mois       |
| Caractérisation piézométrique | 2-3 mois       |
| Intégration ASIC              | 3-4 mois       |
| Tests système                 | 2-3 mois       |
| **Total**                     | **13-18 mois** |

#### Analyse SWOT

| Forces                               | Faiblesses                               |
| ------------------------------------ | ---------------------------------------- |
| CMOS-compatible (processus standard) | Optimisation AlN délicate                |
| Double usage (capteur + énergie)     | Dépendance à la qualité du dépôt         |
| Expertise EPFL (groupe Fantner)      | Accès limité aux équipements spécialisés |

| Opportunités             | Menaces                              |
| ------------------------ | ------------------------------------ |
| Marché IoT auto-alimenté | Marché de niche vs autres projets    |
| Capteurs biomédicaux     | Dépendance à la densité de puissance |

#### Potentiel Startup

Le marché des capteurs IoT auto-alimentés représente environ 500 millions de dollars, avec une croissance annuelle de 20%. Les applications dans les implants médicaux et les capteurs industriels décentralisés sont particulièrement prometteuses.

#### Score Final

| Critère                  | Score     |
| ------------------------ | --------- |
| Faisabilité technique    | ★★★★★     |
| Originalité mondiale     | ★★★★☆     |
| Potentiel de publication | ★★★★☆     |
| Potentiel startup        | ★★★★☆     |
| Multidisciplinarité      | ★★★★☆     |
| **Score total**          | **4.2/5** |

---

### 3.5 Projet E : Gyroscope Optomécanique Intégré

#### Description Technique

Ce projet combine des résonateurs MEMS avec une lecture photonique pour créer un gyroscope optomécanique de chip-scale. La lecture optomécanique offre une sensibilité supérieure aux systèmes conventionnels.

Architecture :

- Résonateurs optomécaniques en nitrure de silicium
- Guides d'ondes pour l'interrogation optique
- Couplage optomécanique pour la transduction

#### Timeline

| Phase                       | Durée          |
| --------------------------- | -------------- |
| Design                      | 3-4 mois       |
| Fabrication                 | 3-4 mois       |
| Caractérisation cryogénique | 6-8 mois       |
| Démonstration gyroscope     | 4-6 mois       |
| **Total**                   | **16-22 mois** |

#### Analyse

Ce projet présente le niveau de complexité le plus élevé en termes de caractérisation, nécessitant des mesures à température cryogénique pour démontrer les effets optomécaniques quantiques. Le score reflects cette complexité.

#### Score Final

| Critère                  | Score     |
| ------------------------ | --------- |
| Faisabilité technique    | ★★☆☆☆     |
| Originalité mondiale     | ★★★★☆     |
| Potentiel de publication | ★★★★★     |
| Potentiel startup        | ★★★☆☆     |
| Multidisciplinarité      | ★★★★☆     |
| **Score total**          | **3.5/5** |

---

### 3.6 Projet F : Puce Photonique Quantique Hybride

#### Description Technique

Ce projet ambitieux vise l'intégration de sources de photons uniques (quantum dots III-V) avec des circuits photoniques en nitrure de silicium pour la photonic quantique.

Cette approche combine :

- Sources quantiques (quantum dots)
- Circuits photoniques bas pertes (SiN)
- Détection single-photon (SNSPD)
- Électronique de contrôle

#### Timeline

| Phase                        | Durée          |
| ---------------------------- | -------------- |
| Design                       | 3-4 mois       |
| Intégration hétérogène       | 6-8 mois       |
| Caractérisation cryogénique  | 6-8 mois       |
| Démonstrations multi-photons | 4-6 mois       |
| **Total**                    | **19-26 mois** |

#### Analyse

Ce projet représente l'ambition maximale et le risque technique correspondant. La nécessité d'installations cryogéniques et d'expertise en physique quantique dépasse le cadre d'une association étudiante typique.

#### Score Final

| Critère                  | Score     |
| ------------------------ | --------- |
| Faisabilité technique    | ★★☆☆☆     |
| Originalité mondiale     | ★★★★★     |
| Potentiel de publication | ★★★★★     |
| Potentiel startup        | ★★★★★     |
| Multidisciplinarité      | ★★★★★     |
| **Score total**          | **4.3/5** |

---

### 3.7 Projet G : Plateforme Biocapteur Microfluidique Photonique Topologique

#### Description Technique

Ce projet applique les concepts de la photonique topologique aux biocapteurs intégrés. Les états de bord topologiques offrent une robustesse contre les désordres de fabrication, résolvant un problème majeur des biocapteurs photoniques.

Architecture :

- Circuits photoniques à états de bord topologiques
- Guides d'ondes robustes
- Capteurs multiplexés
- Intégration microfluidique

#### Timeline

| Phase           | Durée          |
| --------------- | -------------- |
| Design          | 2-3 mois       |
| Fabrication     | 2-3 mois       |
| Caractérisation | 2-3 mois       |
| Tests bio       | 3-4 mois       |
| **Total**       | **12-16 mois** |

#### Potentiel de Publication

Le papier de Kong et al. (2024) démontre la pertinence de cette approche. L'application aux biocapteurs offre une novelty significative pour les publications de haut niveau.

#### Score Final

| Critère                  | Score     |
| ------------------------ | --------- |
| Faisabilité technique    | ★★★★☆     |
| Originalité mondiale     | ★★★★★     |
| Potentiel de publication | ★★★★☆     |
| Potentiel startup        | ★★★★☆     |
| Multidisciplinarité      | ★★★★☆     |
| **Score total**          | **4.0/5** |

---

## 4. Tableau Comparatif Global

| Projet                              | Faisabilité | Originalité | Publication | Startup | Multidisciplinarité | **Total** |
| ----------------------------------- | ----------- | ----------- | ----------- | ------- | ------------------- | --------- |
| A - Switch MEMS photonique          | ★★★★☆       | ★★★★★       | ★★★★★       | ★★★★☆   | ★★★★☆               | **4.5/5** |
| **B - Biocapteur MRR+Spectromètre** | ★★★★★       | ★★★★★       | ★★★★☆       | ★★★★★   | ★★★★★               | **4.8/5** |
| C - LiDAR FMCW                      | ★★★☆☆       | ★★★★☆       | ★★★★★       | ★★★★★   | ★★★★★               | **4.3/5** |
| D - AlN PiezoMEMS                   | ★★★★★       | ★★★★☆       | ★★★★☆       | ★★★★☆   | ★★★★☆               | **4.2/5** |
| E - Gyroscope optomécanique         | ★★☆☆☆       | ★★★★☆       | ★★★★★       | ★★★☆☆   | ★★★★☆               | **3.5/5** |
| F - Puce quantique                  | ★★☆☆☆       | ★★★★★       | ★★★★★       | ★★★★★   | ★★★★★               | **4.3/5** |
| G - Biocapteur topologique          | ★★★★☆       | ★★★★★       | ★★★★☆       | ★★★★☆   | ★★★★☆               | **4.0/5** |

---

## 5. Recommandation Finale

Le projet recommandé est le **Biocapteur photonique intégré avec spectromètre on-chip (Projet B)** en raison de :

1. **Faisabilité technique optimale** : Processus standard sur SOI, équipements CMi disponibles
2. **Originalité mondiale** : Première démonstration monolithique MRR + spectromètre
3. **Potentiel startup immédiat** : Marché POCT en croissance, comparables financed
4. **Multidisciplinarité** : Photonique + microfluidique + électronique
5. **Score global le plus élevé** : 4.8/5

Ce projet offre le meilleur équilibre entre ambition technique, réalisme de réalisation et potentiel d'impact (académique et entrepreneurial).

---

## 6. Annexes Techniques

### 6.1 Équipements CMi Disponibles

| Équipement       | Capacité               | Projet(s)适用的 |
| ---------------- | ---------------------- | --------------- |
| Lithographie DUV | 193nm, 248nm           | A, B, C, D      |
| E-beam           | Résolution sub-μm      | B, G            |
| ICP-RIE Si       | Gravure profonde       | A, B, C         |
| LPCVD SiN        | Dépôt faible perte     | B, C, E         |
| PVD              | Métallisation          | A, D            |
| Deep RIE         | Canaux microfluidiques | B, G            |

### 6.2 Coûts Estimés par Projet

| Projet | Consommables CMi | TinyTapeout | Total estimé |
| ------ | ---------------- | ----------- | ------------ |
| A      | 5 000 CHF        | 300 CHF     | 5 300 CHF    |
| B      | 6 000 CHF        | 300 CHF     | 6 300 CHF    |
| C      | 10 000 CHF       | 300 CHF     | 10 300 CHF   |
| D      | 4 000 CHF        | 300 CHF     | 4 300 CHF    |
| E      | 8 000 CHF        | N/A         | 8 000 CHF    |
| F      | 15 000 CHF       | N/A         | 15 000 CHF   |
| G      | 5 500 CHF        | 300 CHF     | 5 800 CHF    |

---

## 7. Références

### Articles Scientifiques

- Daoxin Dai et al., "Nonvolatile Silicon Photonic MEMS Switch", arXiv:2407.00070 (2024)
- Yoo et al., "Lab-on-a-Chip Optical Biosensor Platform", arXiv:2207.07754 (2022)
- Kong et al., "Topologically Integrated Photonic Biosensor Circuits", arXiv:2408.04945 (2024)
- Lukashchuk et al., "Photonic-electronic integrated circuit-based coherent LiDAR engine", arXiv:2306.07990 (2023)

### Sources de Financement

- Venture Kick : https://www.venturekick.ch
- EPFL Innovation : https://www.epfl.ch/innovation/fr/
- TinyTapeout : https://tinytapeout.com

### Base de Données Startups

- Crunchbase (données de financement)
- Venturelab (startups suisses)
- AngelList (fondateurs et investissements)

---

_Document généré dans le cadre du projet de recherche pour la création de l'association de nanotechnologie pratique EPFL. Tous droits réservés aux auteurs._
