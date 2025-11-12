# 📁 STRUCTURE MODÈLE DES SÉQUENCES PÉDAGOGIQUES

## Vue d'ensemble

Ce document définit la structure standardisée pour toutes les séquences pédagogiques du Lycée Younoussa Bamana. Cette structure garantit la cohérence, la réutilisabilité et la qualité des ressources pédagogiques.

---

## 🎯 Principes directeurs

1. **Cohérence** : Toutes les séquences suivent la même organisation
2. **Clarté** : Nomenclature explicite et numérotation logique
3. **Complétude** : Documents enseignant ET élèves
4. **Évolutivité** : Possibilité d'améliorer sans tout casser
5. **Archivage** : Conservation des anciennes versions

---

## 📂 Structure type d'un dossier de séquence

```
XXX.Nom_de_la_Sequence/
│
├── 📄 README.md                          # Présentation rapide de la séquence
├── 📄 FICHE_SEQUENCE_ENSEIGNANT.md      # Fiche pédagogique complète
│
├── 📁 00_Documents_Generaux/
│   ├── XXX_S00_LIVRET_Sequence.pdf      # Livret élève complet (imprimable)
│   ├── XXX_S00_Progression_sequence.odt  # Planning détaillé enseignant
│   ├── XXX_S00_Image_illustration.png/jpg # Image de couverture
│   └── XXX_S00_Grilles_evaluation.pdf    # Toutes les grilles en un document
│
├── 📁 01_Seances/
│   ├── XXX_S01_Titre_activite.pdf        # Document séance 1
│   ├── XXX_S01_Titre_activite_WS.pdf     # Worksheet si applicable
│   ├── XXX_S02_Titre_activite.pdf        # Document séance 2
│   ├── XXX_S03_Titre_activite.pdf        # etc.
│   └── ...
│
├── 📁 02_Evaluations/
│   ├── XXX_EVAL_CE_Sujet.pdf             # Sujet d'évaluation CE
│   ├── XXX_EVAL_CE_Correction.pdf        # Correction CE
│   ├── XXX_EVAL_EE_Consignes.pdf         # Consignes tâche finale
│   ├── XXX_EVAL_EE_Grille.pdf            # Grille d'évaluation EE
│   ├── XXX_EVAL_CO_Sujet.pdf             # Si évaluation CO
│   └── XXX_EVAL_Vocabulaire.pdf          # Test de vocabulaire
│
├── 📁 03_Corrections/
│   ├── XXX_S01_Correction.pdf            # Corrections séance 1
│   ├── XXX_S02_Correction.pdf            # Corrections séance 2
│   └── ...
│
├── 📁 04_Ressources_Complementaires/
│   ├── Vocab_list_XXX.pdf                # Liste vocabulaire complète
│   ├── Vocab_list_XXX_audio.mp3          # Prononciation (si dispo)
│   ├── Grammar_sheets.pdf                # Fiches grammaire
│   ├── Images/                           # Dossier images
│   └── Audio_Video/                      # Dossier médias
│
├── 📁 05_Differenciation/
│   ├── XXX_Adaptation_Dys.pdf            # Documents adaptés dys
│   ├── XXX_Aide_Difficulte.pdf           # Fiches d'aide simplifiées
│   └── XXX_Approfondissement.pdf         # Activités pour élèves avancés
│
├── 📁 06_Sources/
│   ├── Sources_LaTeX/                    # Fichiers .tex si utilisés
│   ├── Sources_originales/               # Articles bruts, liens
│   └── Licences.txt                      # Crédits et droits d'auteur
│
└── 📁 07_Archives/
    └── Ancienne_version_XXX/             # Versions précédentes
```

---

## 🏷️ Nomenclature des fichiers

### Règles générales
- **Préfixe** : Code de la séquence (ex: `AI`, `NZ`, `HWP`)
- **Numéro** : `S00` à `S99` pour les séances (S00 = documents généraux)
- **Titre** : Descriptif clair en anglais ou français
- **Extension** : `.pdf` pour distribution, `.odt`/`.docx` pour édition

### Format type
```
[CODE]_[TYPE][NUMERO]_[TITRE_DESCRIPTIF].[extension]

Exemples :
AI_S01_What_is_AI_text_and_WS.pdf
AI_S03_Deepfake_Morgan_Freeman.pdf
AI_EVAL_CE_Teacher_Bans_AI.pdf
NZ_S02_Maori_Culture_Worksheet.pdf
```

### Codes types
- `S00` à `S99` : Séances de cours
- `EVAL_CE` : Évaluation Compréhension Écrite
- `EVAL_CO` : Évaluation Compréhension Orale
- `EVAL_EE` : Évaluation Expression Écrite
- `EVAL_EO` : Évaluation Expression Orale
- `EVAL_VOC` : Évaluation Vocabulaire
- `WS` : Worksheet (feuille d'exercices)
- `CORR` : Correction

---

## 📝 Documents obligatoires

### Pour chaque séquence

#### 1. README.md
Document de présentation rapide (1 page)
- Titre et thème
- Niveau et durée
- Objectifs principaux
- Liste des fichiers
- Problématique

#### 2. FICHE_SEQUENCE_ENSEIGNANT.md
Document pédagogique complet (10-15 pages)
- Informations générales
- Problématique et objectifs
- Compétences CECRL
- Progression détaillée séance par séance
- Évaluations
- Différenciation
- Ressources et prolongements

#### 3. LIVRET_Sequence.pdf
Document élève complet imprimable
- Page de garde avec espace nom/classe
- Table des matières
- Toutes les activités de la séquence
- Espaces pour les réponses
- Vocabulaire et aides
- Consignes tâche finale

#### 4. Au moins 1 évaluation sommative
- Sujet
- Correction
- Grille d'évaluation

---

## 🎨 Charte graphique des documents

### Livret élève
- **Police** : Arial ou Calibri 11pt pour le corps, 14-16pt pour les titres
- **Marges** : 2cm minimum de chaque côté
- **En-tête** : "Lycée Younoussa Bamana" (gauche) + "Mr Pierres" (droite)
- **Numérotation** : Pages numérotées en bas de page
- **Sections** : Clairement séparées avec des titres apparents

### Documents enseignant
- **Format** : Markdown privilégié (facilement éditable)
- **PDF** : Pour les documents de distribution
- **Structure** : Titres hiérarchisés (# ## ### etc.)

---

## 📊 Organisation des évaluations

### Types d'évaluations

#### Évaluations formatives
- Non notées ou bonus
- Feedback formatif
- Conservées dans `02_Evaluations/Formatives/`

#### Évaluations sommatives
- Notées (coefficient /20)
- Avec barème détaillé
- Avec correction complète
- Conservées dans `02_Evaluations/Sommatives/`

### Grilles d'évaluation
Toutes les grilles doivent inclure :
- Critères clairs et observables
- Niveaux CECRL (A2, A2+, B1, B1+, etc.)
- Points par critère
- Total sur 20

---

## 🔄 Workflow de création d'une nouvelle séquence

### Étape 1 : Préparation
1. Créer le dossier avec la structure type
2. Copier le template README.md et FICHE_SEQUENCE_ENSEIGNANT.md
3. Définir la problématique et les objectifs

### Étape 2 : Conception
1. Sélectionner les documents supports (articles, vidéos, etc.)
2. Créer les worksheets et activités
3. Concevoir les évaluations
4. Préparer les corrections

### Étape 3 : Compilation
1. Assembler le livret élève
2. Créer les PDF finaux
3. Tester avec une classe (si possible)

### Étape 4 : Documentation
1. Compléter la fiche séquence enseignant
2. Rédiger le README
3. Archiver les sources

### Étape 5 : Validation
1. Relecture orthographe/grammaire
2. Vérification cohérence pédagogique
3. Test impression
4. Validation par l'équipe

---

## 💾 Gestion des versions

### Principe
- Conserver les anciennes versions dans `07_Archives/`
- Dater les versions archivées
- Documenter les changements majeurs

### Nommage des versions archivées
```
07_Archives/
├── v2024_Version_originale/
├── v2025_Revision_janvier/
└── CHANGELOG.md
```

### CHANGELOG.md
```markdown
# Historique des modifications

## Version 2025.2 (Novembre 2025)
- Ajout d'une activité sur les deepfakes
- Modification de la tâche finale
- Mise à jour des articles

## Version 2025.1 (Septembre 2025)
- Création initiale de la séquence
```

---

## 🎯 Checklist de validation d'une séquence

### Contenu pédagogique
- [ ] Problématique claire et pertinente
- [ ] Objectifs SMART (Spécifiques, Mesurables, Atteignables, Réalistes, Temporels)
- [ ] Progression logique des séances
- [ ] Activités variées (CE, CO, EE, EO)
- [ ] Au moins une évaluation sommative
- [ ] Différenciation prévue

### Documents
- [ ] README.md complété
- [ ] FICHE_SEQUENCE_ENSEIGNANT.md complète
- [ ] Livret élève finalisé et paginé
- [ ] Tous les documents numérotés correctement
- [ ] Corrections disponibles
- [ ] Grilles d'évaluation créées

### Qualité
- [ ] Orthographe et grammaire vérifiées (EN + FR)
- [ ] Mise en page soignée et cohérente
- [ ] Images de bonne qualité
- [ ] Liens/sources documentés
- [ ] Respect des droits d'auteur

### Technique
- [ ] Tous les fichiers PDF s'ouvrent correctement
- [ ] Médias (audio/vidéo) testés
- [ ] Impression test effectuée
- [ ] Fichiers sources sauvegardés

---

## 🌟 Bonnes pratiques

### À faire
✅ Utiliser des documents authentiques récents
✅ Varier les activités et les supports
✅ Prévoir de la différenciation
✅ Créer des corrections complètes
✅ Tester avec les élèves avant de finaliser
✅ Demander des retours aux collègues
✅ Archiver les anciennes versions

### À éviter
❌ Surcharger le livret élève (max 15 pages)
❌ Utiliser des documents trop difficiles sans adaptation
❌ Oublier les corrections
❌ Négliger la mise en page
❌ Ignorer les élèves en difficulté
❌ Supprimer définitivement d'anciennes versions

---

## 📚 Templates disponibles

Dans le dossier `_TEMPLATES/` :
- `README_template.md` : Modèle de README
- `FICHE_SEQUENCE_template.md` : Modèle de fiche séquence
- `Page_de_garde_livret.odt` : Modèle de page de garde
- `Grille_evaluation_CE.odt` : Modèle grille CE
- `Grille_evaluation_EE.odt` : Modèle grille EE
- `Grille_evaluation_CO.odt` : Modèle grille CO
- `Grille_evaluation_EO.odt` : Modèle grille EO

---

## 🔧 Outils recommandés

### Création de documents
- **LibreOffice** : Pour les .odt (gratuit, multiplateforme)
- **LaTeX** : Pour les évaluations (qualité professionnelle)
- **Canva** : Pour les visuels attractifs
- **Markdown** : Pour la documentation enseignant

### Gestion de médias
- **Audacity** : Édition audio
- **VLC** : Découpage vidéo
- **HandBrake** : Compression vidéo
- **TinyPNG** : Compression images

### Pédagogie
- **Crossword Labs** : Création de mots croisés
- **Quizlet** : Flashcards vocabulaire
- **Padlet** : Tableau collaboratif
- **Kahoot** : Quiz interactifs

---

## 📞 Support et questions

Pour toute question sur cette structure :
- Consulter les exemples existants (séquence 203.AI)
- Demander aux collègues de l'équipe d'anglais
- Proposer des améliorations via les réunions d'équipe

---

## 🚀 Évolution de ce document

Ce document est évolutif et sera mis à jour en fonction :
- Des retours d'expérience
- Des nouvelles pratiques pédagogiques
- Des suggestions de l'équipe
- Des contraintes techniques

**Dernière mise à jour** : 12 novembre 2025
**Version** : 1.0

---

*Ce modèle de structure a été conçu pour optimiser la création, le partage et la réutilisation des séquences pédagogiques au Lycée Younoussa Bamana.*
