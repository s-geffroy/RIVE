# Changelog

Toutes les modifications notables apportées au RIVE Blue Book sont documentées dans ce fichier.

Le format suit [Keep a Changelog](https://keepachangelog.com/fr/1.1.0/) et le projet adhère au [Semantic Versioning](https://semver.org/lang/fr/).

## [Unreleased]

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

[Unreleased]: https://github.com/s-geffroy/RIVE/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/s-geffroy/RIVE/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/s-geffroy/RIVE/releases/tag/v1.0.0
