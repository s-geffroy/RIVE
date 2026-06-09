# Changelog

Toutes les modifications notables apportées au RIVE Blue Book sont documentées dans ce fichier.

Le format suit [Keep a Changelog](https://keepachangelog.com/fr/1.1.0/) et le projet adhère au [Semantic Versioning](https://semver.org/lang/fr/).

## [Unreleased]

### Added

- Publication du Blue Book via GitHub Pages : configuration Jekyll minimale (`_config.yml`, thème `jekyll-theme-cayman`). Site accessible à l'adresse https://s-geffroy.github.io/RIVE/.
- Mise à jour du `.gitignore` pour ignorer les artefacts Jekyll (`_site/`, `.jekyll-cache/`, `.jekyll-metadata`, `Gemfile.lock`).

### Changed

- Refonte intégrale de la rédaction du Blue Book pour atteindre une voix unifiée de note d'instruction (haut fonctionnaire), sans signaux IA : suppression des tirets cadratins, conversion des listes à puces et tables récapitulatives en prose, retrait des tics lexicaux récurrents.
- Suppression de toute mention de version (v1, v1.1, v1.2, v1.3) dans le corps des documents (`00_avant_propos.md`, `00_index.md`, `README.md`, `EXEC_BRIEF.md`, `DOSSIER_POLITIQUE.md`, chapitres 01 à 26). Les versions restent suivies par Git et par le présent fichier `CHANGELOG.md`.
- Renommage du chapitre 04 « Périmètre de la V1 » en « Périmètre du projet ».
- Renommage du chapitre 03 « Principes non négociables » en « Principes structurants ».

### Added

- `27_plan_de_transition.md` : nouveau chapitre proposant une voie possible de transition entre la situation française actuelle et le déploiement de RIVE, organisée en quatre temps (pré-engagement, implantation pilote, consolidation et maillage de bassin, diffusion réglée).

## [1.3.0] - 2026-06-09

Révision après auto-challenge dur de la v1.2. Cible : honnêteté complète, sources auditables, lisibilité par niveau.

### Added

- **EXEC_BRIEF.md** : brief exécutif 1 page pour ministre / président d’EPCI / décideur (lecture 2 min).
- **DOSSIER_POLITIQUE.md** : dossier politique court 5 pages pour cabinet / DGS / chef de bureau (lecture 15 min).
- **ch. 23.7 — Voie infra-législative « RIVE_lite »** : section dédiée à ce que RIVE peut être SANS loi de programmation. Trajectoire double piste explicite (cible + lite). Conditions de bascule.
- **ch. 24.3 bis — Surcoût d’intégration ventilé** : justification ligne par ligne (amplitude horaire, cellule santé, inclusion, parcours, pauses, Pôle Lycée Bassin, direction unifiée) remplaçant le « +10–30 % » global de la v1.2.
- **ch. 10.6.1 — AESH et refonte PIAL précisées** : modèle visé (équipe AESH RIVE, titularisation progressive, co-pilotage DG/recteur) ; reconnaissance que la cible n’est atteignable qu’avec loi.
- **ch. 10.6.2 — Pôle Santé Bassin** : explicité dans le ch. 10 (incohérence v1.2 corrigée).
- **ch. 14.1 — Pôle SI Bassin** : explicité dans le ch. 14 (incohérence v1.2 corrigée).
- **ch. 13.5 — Conditions de travail amplitude 07:30–19:00** : trois plages de poste, compensations, statut de l’agent de vie éducative.
- **ch. 16.2 — Indicateurs primaires complétés** : composition sociale publiée annuellement, décrochage post-16, accès aux parcours sérieux par décile.
- **ch. 18 — Horizon trans-mandats** : portage par l’infra-politique, verrous de réversibilité, doctrine trans-partisane.
- **ch. 8.3 bis — Résolution tension calendrier propre vs zones académiques** : grandes pauses alignées sur zones A/B/C, été raccourci par les deux bouts, semaine éducative supplémentaire en option, semaines d’instruction allégées.
- **ch. 6.7.4 — Mutualisation à 4 échelles** des spécialités pro pour couvrir le maximum : Pôle local, inter-bassins, alternance, partenariat EN.
- **ch. 6.7.4 bis — Spécialisation différenciée** des Pôles Lycée Bassin entre eux (carte régionale des spécialités).

### Changed

- **ch. 20.10 — Sources budgétaires** : remplacement des hashtags par des références citables [REF-1] à [REF-23] avec édition, indicateur principal, localisation (chapitre / tableau).
- **ch. 24 — Ratios sourcés** : chaque ligne du § 24.2, 24.3, 24.4, 24.5 porte des références [REF-N] vers le ch. 20.10.
- **ch. 24.5 — Ratios EAJE corrigés** : critère « marche acquise » (décret 30/08/2021) au lieu d’un seuil d’âge approximatif.
- **ch. 24.4 bis — Fonds d’égalité localisé** : 3–5 % en bassin moyen, **7–10 % en bassin en quartier populaire**. Justification quantifiée.
- **ch. 25.4 — Tirage au sort et base légale** : remplacement des quotas par revenu (juridiquement fragile) par une mixité par zone d’habitation (modèle AFFELNET-Lycée Paris). Bases légales citées pour chaque règle d’accès.
- **ch. 6.6 / 6.7 — Frontière 14–16 / 16–18 clarifiée** : la Maison Horizon prend le relais à l’entrée en seconde, pas à l’âge biologique 16.

### Documentation

- Index `00_index.md` et `README.md` portés à v1.3 avec les trois entrées documentaires en tête.

## [1.2.0] - 2026-06-09

Révision de rigueur d'instruction politique après auto-challenge dur de la v1.1. Cible : tenir devant un chef de bureau ministériel ou un DGS exigeant.

### Fixed (les 4 critiques)

- **Sourçage budgétaire (ch. 24)** : chaque ratio porte désormais une référence courte vers une source publique. Méthode explicite (coût actuel + surcoût intégration estimé). Fonds d'égalité revu à 3–5 % (vs 1–2 % en v1.1) sur justification quantifiée.
- **Sources publiques étoffées (ch. 20)** : refonte du chapitre en 12 sections couvrant cadres pédagogiques, juridiques, petite enfance, périscolaire, santé/inclusion, numérique/IA, restauration, sport, protection de l'enfance, **données budgétaires** (DEPP/RERS, INSEE, CNAF, HCFEA, Cour des Comptes, OCDE, France Stratégie/CNESCO, Injep), cadres expérimentaux.
- **Chaîne juridique EN (ch. 23)** : reconnaissance que L401-1 seul est insuffisant. Chaîne complète à 9 instruments (loi de programmation + L401-1 + L421-19-17 + décret d'application + arrêté calendrier + convention nationale enseignants + accord-cadre dialogue social + convention bipartite Académie/RIVE + convention santé scolaire/inclusion).
- **Portage juridique (ch. 22)** : recommandation V1 repivotée. GIP seul abandonné comme option principale. Nouvelle reco : **EP expérimental par la loi** en principal, **GIP + EPLE expérimental couplés** en repli. Matrice véhicule × scénario EN ajoutée pour tracer les compatibilités.
- **Lycée mathématiquement faisable (ch. 6.7, ch. 5)** : architecture à double étage. Maison Horizon par RIVE = tronc commun lycée + voie générale courante. **Pôle Lycée Bassin** mutualisé = spécialités rares + voies technologique et professionnelle + plateaux techniques. Une RIVE seule ne porte plus les 3 voies.

### Added

- **Principe 3.8 — Présence individuelle bornée** : plafond quotidien par tranche d'âge (9 h petite enfance, 10 h primaire, 11 h secondaire) pour empêcher l'institution totale malgré l'ouverture 07:30–19:00.
- **Vague 3 (ch. 18)** : passage explicite de 2 RIVEs (Vagues 1+2) au maillage complet du bassin (8 RIVEs), avec Pôles bassin et véhicule juridique définitif.
- **Pôles bassin (ch. 5.5, ch. 13)** : Pôle Lycée Bassin, Pôle Santé Bassin, Pôle Cuisine Bassin, Pôle SI Bassin, Pôle Partenaires Bassin. Architecture de mutualisation explicitée.
- **Règles d'accès opérationnelles contre la capture sociale (ch. 25.4)** : sectorisation, quotas par décile de revenu, tirage au sort en cas de sursouscription, indicateur de composition sociale publié annuellement.

### Changed

- **ch. 2 — table de nommage** : ajout du niveau « Bassin éducatif RIVE » (maillage) et du niveau « Pôle bassin RIVE » (mutualisation). Distinction RIVE/bassin rendue inéquivoque.
- **ch. 25 — honnêteté doctrinale** : tensions 17–19h et capture sociale reformulées sans dissimulation. RIVE *réduit* l'inégalité d'accès aux parcours sérieux, ne la supprime pas. Pendant la V1, RIVE est par définition en îlot — c'est traité par règles d'accès, pas dissous dans une cible lointaine.
- **ch. 24 — ratios m²/enfant** : ventilation intérieur / extérieur ajoutée, ligne dédiée Pôle Lycée Bassin (plateaux techniques voie pro).
- **ch. 24 — décomposition par bloc** : RH ramenée à 58–63 % (vs 60–65 %) ; fonds d'égalité 3–5 % (vs 1–2 %). Références comparatives DEPP ajoutées pour chaque bloc.

### Documentation

- Index `00_index.md` et `README.md` portés à v1.2.

## [1.1.0] - 2026-06-08

### Added

- `22_portage_juridique.md` — Matrice des 6 véhicules juridiques candidats (EPLE expérimental, GIP, EPCC étendu, régie intercommunale, SCIC, EP par la loi), critères d'évaluation, recommandation argumentée (GIP pour la V1, EP par la loi pour la cible bassin).
- `23_articulation_education_nationale.md` — 3 scénarios d'articulation avec l'EN (absorption via dérogation L401-1 / partenariat structuré / parallèle), conséquences RH (détachement, mise à disposition), recommandation (absorption + repli sur partenariat).
- `24_ratios_budgetaires.md` — Ratios chiffrés €/enfant/an par tranche d'âge × bloc de coût, ETP/enfant, m²/enfant, coûts évités, trajectoire pluriannuelle.
- `25_coherence_doctrinale.md` — Tranchage des 4 tensions doctrinales internes (17-19h, 16→18 ans, capture sociale, profilage vs personnalisation).
- `26_vacances_pauses_educatives_et_droits.md` — Reformulation du « droit aux vacances éducatives » en obligation positive d'un débiteur identifié, vocabulaire stabilisé (vacances familiales vs pauses éducatives), régime centre de loisirs intégré.

### Changed

- **Horaires** : ouverture à 07:30 (et non plus 08:00) pour les familles qui travaillent, accueil échelonné 07:30–09:00 distinct du noyau 09:00–17:00 (`07_la_journee_08_00_19_00.md`, `15_budget_et_financement.md`, `19_annexes_operationnelles_integrees.md`).
- **Borne d'âge** : continuité jusqu'au baccalauréat (≈ 18 ans), voies générale + technologique + professionnelle, ajout de la « Maison Horizon » (16–18 ans) (`01_resume_executif.md`, `04_perimetre_de_la_v1.md`, `05_forme_territoriale_le_campus_reseau.md`, `06_organisation_par_age.md`, `11_travail_personnel_et_devoirs.md`, `12_familles_fratries_et_mobilite.md`, `13_rh_metiers_et_gouvernance.md`).
- **Échelle territoriale** : une RIVE = unité locale de 500–900 enfants ; un bassin = maillage de ≈ 8 RIVEs (pour 7 000 enfants) (`01_resume_executif.md`, `04_perimetre_de_la_v1.md`, `05_forme_territoriale_le_campus_reseau.md`, `18_feuille_de_route.md`).
- **Calendrier annuel propre** : semaines allégées + été ramené à 5–6 semaines, distinction « vacances familiales » vs « pauses éducatives » (`01_resume_executif.md`, `08_periodes_scolaires_et_vacances.md`).
- **Activités extrascolaires** : conservatoires, clubs sportifs, compagnies de théâtre deviennent partenaires hébergés intégralement dans RIVE sous convention exigeante (`01_resume_executif.md`, `09_sport_musique_theatre_arts_et_clubs.md`).
- **Santé et inclusion** : cellule santé intégrée explicite (infirmerie, médecin référent, PMI, psychologue, médecine scolaire), AESH mutualisés, UPE2A intégrée, lien MDPH (`01_resume_executif.md`, `10_restauration_et_sante_quotidienne.md`, `13_rh_metiers_et_gouvernance.md`).
- **Petit-déjeuner** : service introduit pour les enfants arrivés tôt à 07:30 (`10_restauration_et_sante_quotidienne.md`, `15_budget_et_financement.md`).
- **Principe 3.4 reformulé** : « rien d'essentiel exclusivement après 17:00 » (au lieu de « rien d'essentiel après 17:00 ») pour permettre l'hébergement des parcours sérieux structurellement tardifs (`03_principes_non_negociables.md`).
- **Risques majeurs** : ajout des risques 17.10 (désalignement calendrier), 17.11 (dépendance à l'absorption EN), 17.12 (lycée pro) (`17_risques_majeurs.md`).
- **Feuille de route** : explicitation de la cible doctrinale couverture totale du bassin par maillage à terme (`18_feuille_de_route.md`).
- **Annexes** : matrice des décisions et glossaire mis à jour en cohérence (`19_annexes_operationnelles_integrees.md`).
- **Conclusion** : transition vers les chapitres 22–26 d'instruction politique (`21_conclusion.md`).

### Documentation

- Index `00_index.md` et `README.md` réorganisés pour distinguer corps doctrinal et chapitres d'instruction politique.

## [1.0.0] - 2026-06-08

### Added
- Mise sous gestion de version du Blue Book (dépôt git initialisé, publié sur `git@github.com:s-geffroy/RIVE.git`).
- `.gitignore` excluant `RIVE.code-workspace` et `.DS_Store`.
- `CHANGELOG.md` (ce fichier).
- Corpus initial du Blue Book v1 (23 documents Markdown) :
  - `README.md`, `00_index.md`, `00_avant_propos.md`
  - `01_resume_executif.md`
  - `02_le_nom_rive_et_son_architecture_institutionnelle.md`
  - `03_principes_non_negociables.md`
  - `04_perimetre_de_la_v1.md`
  - `05_forme_territoriale_le_campus_reseau.md`
  - `06_organisation_par_age.md`
  - `07_la_journee_08_00_19_00.md`
  - `08_periodes_scolaires_et_vacances.md`
  - `09_sport_musique_theatre_arts_et_clubs.md`
  - `10_restauration_et_sante_quotidienne.md`
  - `11_travail_personnel_et_devoirs.md`
  - `12_familles_fratries_et_mobilite.md`
  - `13_rh_metiers_et_gouvernance.md`
  - `14_si_donnees_et_llm.md`
  - `15_budget_et_financement.md`
  - `16_evaluation_independante.md`
  - `17_risques_majeurs.md`
  - `18_feuille_de_route.md`
  - `19_annexes_operationnelles_integrees.md`
  - `20_references_publiques_a_verifier_avant_instruction.md`
  - `21_conclusion.md`

[Unreleased]: https://github.com/s-geffroy/RIVE/compare/v1.3.0...HEAD
[1.3.0]: https://github.com/s-geffroy/RIVE/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/s-geffroy/RIVE/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/s-geffroy/RIVE/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/s-geffroy/RIVE/releases/tag/v1.0.0
